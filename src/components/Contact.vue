<template>
    <div>
        <div class="container" style="padding:10%">
            <h2>Get in Touch!</h2>
            <form action="mailto:fujitahibaraki@gmail.com" method="post" enctype="text/plain">
                <div class="form-group">
                    <input type="email" class="form-control" v-model="contact.email" placeholder="Enter email">
                </div>
                <div class="form-group">
                    <textarea class="form-control" v-model="contact.message" rows="3" placeholder="write message"></textarea>
                </div>
            </form>

            <button type="button" @click="submit" class="btn btn-primary btn-lg">Contact</button>
        </div>
    </div>
</template>

<script lang="ts">
export default {
    data(){
        return {
            contact:{
                email:'',
                message:''
            }
        }
    },
    methods:{
        submit(){
            if(this.contact.email != "" && this.contact.message != "")
            /* eslint no-empty: ["error", { "allowEmptyCatch": true }] */
            {
              //run the details form
            }
            else
            {
                alert("Please fill out the required fields.");
            }
        }
    }
}
</script>
