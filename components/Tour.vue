<template>
    <section id="portfolio" class="portfolio section-padding">
        <div class="container">
            <div class="row">
                <div class="col-md-12">
                    <div class="section-header header-text pb-5">
                        <h2>Top Tour</h2>
                        <p>Keep calm & Travel on</p>
                    </div>
                </div>
            </div>
            <div class="row">
                <div class="col-12 col-md-12 col-lg-4 pb-3 card-wrapper">
                    <div class="text-light bg-white">
                        <div class="card-body text-writh">
                            <div class="img-area">
                                <img src="../img/project-1.jpg" class="img-fluid" alt="">
                            </div>
                            <div class="text-wrapper">
                                <h3>Japan</h3>
                                <p class="sub-text mb-0">10 Popular Piaces</p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-12 col-md-12 col-lg-4 pb-3 card-wrapper">
                    <div class="text-light bg-white">
                        <div class="card-body text-writh">
                            <div class="img-area">
                                <img src="../img/project-2.jpg" class="img-fluid" alt="">
                            </div>
                            <div class="text-wrapper">
                                <h3>Bali</h3>
                                <p class="sub-text mb-0">10 Popular Piaces</p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-12 col-md-12 col-lg-4 pb-3 card-wrapper">
                    <div class="text-light bg-white">
                        <div class="card-body text-writh">
                            <div class="img-area">
                                <img src="../img/project-3.jpg" class="img-fluid" alt="">
                            </div>
                            <div class="text-wrapper">
                                <h3>Spain</h3>
                                <p class="sub-text mb-0">10 Popular Piaces</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
      </section>
</template>

<script>
import "../css/style.css"
export default {
  
}
</script>

<style scoped>

.card-wrapper {
    display: grid;
    justify-content: center;
}

.card-body {
    position: relative;
    padding: 0;
}

.text-wrapper {
    position: absolute;
    left: 1.5rem;
    top: 21.5rem;
}

.sub-text  {
    font-size: 1rem;
}

.section-padding {
    padding: 6rem 0 0 0;
}

img {
    border-radius: 1rem;
}

@media (max-width: 1024px) {
    .text-wrapper {
        left: 1.5rem;
        top: 17.5rem;
        z-index: 99;
    }
}

@media (max-width: 912px) {
    .text-wrapper {
        left: 1.5rem;
        top: 25.5rem;
        z-index: 99;
    }
    .header-text {
        text-align: center;
    }
}

@media (max-width: 540px) {
    .text-wrapper {
        left: 1.5rem;
        top: 24.5rem;
        z-index: 99;
    }
}

@media (max-width: 394px) {
    .text-wrapper {
        left: 1.5rem;
        top: 22.5rem;
        z-index: 99;
    }
}

@media (max-width: 376px) {
    .text-wrapper {
        left: 1.5rem;
        top: 21.5rem;
        z-index: 99;
    }
}

@media (max-width: 361px) {
    .text-wrapper {
        left: 1.5rem;
        top: 20.5rem;
        z-index: 99;
    }
}

@media (max-width: 280px) {
    .text-wrapper {
        left: 1.5rem;
        top: 14.5rem;
        z-index: 99;
    }
}

</style>