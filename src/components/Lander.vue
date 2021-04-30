<template>
    <div>
        <section class="section" id="background">
            <div class="container-fluid" id="background">
                <img alt="ghostie" class="rounded-circle" width="150" src="@/assets/ghostie.jpg">
                <h1>Quality Engineer</h1>
                <p>I'm also a writer, programmer and language enthusiast.</p>
                <button type="button" class="btn btn-primary btn-lg" data-toggle="modal" data-target=".bd-example-modal-lg">Contact</button>

            </div>
        </section>

        <section class="portfolio">
            <h1>Portfolio</h1>
            <p>These are some of the things I have done:</p>
            <div class="container">
                <div class="row">

                    <div class="col-md-4">
                            <div class="card">
                                <div class="card-head">
                                    <img alt="Drawing app" class="rounded-circle img-custom" src="@/assets/drawing.jpg">
                                    <h2>Drawing Application</h2>
                                </div>
                                <hr>
                                <div class="card-body">
                                  <p>
                                      A drawing app written for university project.
                                  </p>
                                    <p>
                                        <a href="https://hedonisticopportunist.github.io/drawing_app/">Here's a link to my drawing application.</a>
                                    </p>
                                </div>
                            </div>
                            <br>
                    </div>

                    <div class="col-md-4">
                            <div class="card">
                                <div class="card-head">
                                    <img alt="Cats in Neath site" class="rounded-circle img-custom" src="@/assets/catsneath.jpg">
                                    <h2>Cats in Neath - Website</h2>
                                </div>
                                <hr>
                                <div class="card-body">
                                  <p>
                                    A site built for a uni project that focuses on Cats in the Neath area.
                                  </p>
                                    <p>
                                      <a href="https://hedonisticopportunist.github.io/cats_in_neath/">Visit the site.</a>
                                    </p>
                                </div>
                            </div>
                        <br>
                    </div>

                    <div class="col-md-4">
                        <div class="card">
                            <div class="card-head">
                                <img alt="Side scroller game" class="rounded-circle img-custom" src="@/assets/game.jpg">
                                <h2>Game Project</h2>
                            </div>
                            <hr>
                            <div class="card-body">
                                <p>
                                    A side scroller written for a uni project.
                                </p>
                                <p>
                                    <a href="https://hedonisticopportunist.github.io/game_project_v2/index">Play the game here!</a>
                                </p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <section class="">
            <div class="modal fade bd-example-modal-lg" tabindex="-1" role="dialog" aria-labelledby="myLargeModalLabel" aria-hidden="true">
                <div class="modal-dialog modal-lg">
                    <div class="modal-content">
                        <talk/>
                    </div>
                </div>
            </div>
        </section>

    </div>
</template>

<script lang="ts">
import talk from './Contact.vue'
export default {
    name:'Lander',
    components:{
        talk
    }
}
</script>

<style lang="css" scoped>
    .section{
        padding-top: 10%;
        padding-bottom: 10%;
    }

    .portfolio{
        background-color: #7b6079;
        padding-top: 8%;
        padding-bottom: 15%;
    }

    .img-custom{
        width: 180px;
        height: 140px;
        margin-top: 15px;
    }

    #background{
      background-color: #87a7b3;
      color: #a7d0cd;
    }

</style>
