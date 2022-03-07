<template>
    <section id="portfolio" class="portfolio section-padding">
        <div class="container">
            <div class="row">
                <div class="col-md-12">
                    <div class="section-header header-text pb-5">
                        <h2>Featured Destinations</h2>
                        <p>Popular destinations open to visitors from Indonesia</p>
                    </div>
                </div>
            </div>
            <div class="container-wrapper">
                <div class="card-body text-writh cell-1">
                    <div class="img-area">
                        <img src="../img/project-1.jpg" class="img-fluid" alt="">
                    </div>
                    <div class="text-wrapper text-white">
                        <h3>Japan</h3>
                        <p class="sub-text mb-0">10 Popular Piaces</p>
                    </div>
                </div>
                <div class="card-body text-writh cell-2">
                    <div class="img-area">
                        <img src="../img/project-2.jpg" class="img-fluid" alt="">
                    </div>
                    <div class="text-wrapper text-white">
                        <h3>Bali</h3>
                        <p class="sub-text mb-0">10 Popular Piaces</p>
                    </div>
                </div>
                <div class="card-body text-writh cell-3">
                    <div class="img-area">
                        <img src="../img/project-3.jpg" class="img-fluid" alt="">
                    </div>
                    <div class="text-wrapper text-white">
                        <h3>Spain</h3>
                        <p class="sub-text mb-0">10 Popular Piaces</p>
                    </div>
                </div>
                <div class="card-body text-writh cell-4">
                    <div class="img-area">
                        <img src="../img/project-1.jpg" class="img-fluid" alt="">
                    </div>
                    <div class="text-wrapper text-white">
                        <h3>Japan</h3>
                        <p class="sub-text mb-0">10 Popular Piaces</p>
                    </div>
                </div>
                <div class="card-body text-writh cell-5">
                    <div class="img-area">
                        <img src="../img/project-2.jpg" class="img-fluid" alt="">
                    </div>
                    <div class="text-wrapper text-white">
                        <h3>Bali</h3>
                        <p class="sub-text mb-0">10 Popular Piaces</p>
                    </div>
                </div>
                <div class="card-body text-writh cell-6">
                    <div class="img-area">
                        <img src="../img/project-3.jpg" class="img-fluid" alt="">
                    </div>
                    <div class="text-wrapper text-white">
                        <h3>Spain</h3>
                        <p class="sub-text mb-0">10 Popular Piaces</p>
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

.container-wrapper {
    display: grid;
    column-gap: 2rem;
    row-gap: 2rem;
    grid-template-columns: 1fr 1fr 1fr;
    grid-template-rows: 1fr 1fr;
}

.card-body {
    display: flex;
    justify-content: center;
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
    padding: 0 0;
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
        left: 10.5rem;
        top: 25.5rem;
        z-index: 99;
    }
    .header-text {
        text-align: center;
    }
    .container-wrapper {
        display: unset;
    }
    .card-body {
        padding-bottom: 2rem;
    }
}

@media (max-width: 540px) {
    .text-wrapper {
        left: 5.5rem;
        top: 25.5rem;
        z-index: 99;
    }
}

@media (max-width: 415px) {
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