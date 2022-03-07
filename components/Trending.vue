<template>
    <section class="team section-padding" id="team">
          <div class="container">
            <div class="row">
                <div class="col-md-12">
                    <div class="section-header text-center pb-5">
                        <h2>Trending cites</h2>
                        <p>The most searched for cities on TripGuide</p>
                    </div>
                </div>
            </div>
            <div class="row grid">
                <div class="col-xl-11 col-md-6 col-lg-3 p-0">
                    <div class="card">
                        <div class="card-body">
                            <img src="../img/team-1.jpg" alt="" class="img-fluid">
                            <div class="card-wrapper pl-4">
                                <h3 class="card-title py-2">Manila</h3>
                                <p class="card-text">$250.00 / night</p>
                                <button class="btn btn-block btn-lg btn-primary btn-wrapper">Book Now</button>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-xl-11 col-md-6 col-lg-3 p-0">
                    <div class="card">
                        <div class="card-body">
                            <img src="../img/team-1.jpg" alt="" class="img-fluid">
                            <div class="card-wrapper pl-4">
                                <h3 class="card-title py-2">San Francisco</h3>
                                <p class="card-text">$250.00 / night</p>
                                <button class="btn btn-block btn-lg btn-primary btn-wrapper">Book Now</button>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-xl-11 col-md-6 col-lg-3 p-0">
                    <div class="card">
                        <div class="card-body">
                            <img src="../img/team-1.jpg" alt="" class="img-fluid">
                            <div class="card-wrapper pl-4">
                                <h3 class="card-title py-2">Frankfurt main</h3>
                                <p class="card-text">$250.00 / night</p>
                                <button class="btn btn-block btn-lg btn-primary btn-wrapper">Book Now</button>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-xl-11 col-md-6 col-lg-3 p-0">
                    <div class="card">
                        <div class="card-body">
                            <img src="../img/team-1.jpg" alt="" class="img-fluid">
                            <div class="card-wrapper pl-4">
                                <h3 class="card-title py-2">Washington</h3>
                                <p class="card-text">$250.00 / night</p>
                                <button class="btn btn-block btn-lg btn-primary btn-wrapper">Book Now</button>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-xl-11 col-md-6 col-lg-3 p-0">
                    <div class="card">
                        <div class="card-body">
                            <img src="../img/team-1.jpg" alt="" class="img-fluid">
                            <div class="card-wrapper pl-4">
                                <h3 class="card-title py-2">Stockholm</h3>
                                <p class="card-text">$250.00 / night</p>
                                <button class="btn btn-block btn-lg btn-primary btn-wrapper">Book Now</button>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-xl-11 col-md-6 col-lg-3 p-0">
                    <div class="card">
                        <div class="card-body">
                            <img src="../img/team-1.jpg" alt="" class="img-fluid">
                            <div class="card-wrapper pl-4">
                                <h3 class="card-title py-2">Seattle</h3>
                                <p class="card-text">$250.00 / night</p>
                                <button class="btn btn-block btn-lg btn-primary btn-wrapper">Book Now</button>
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

.grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    grid-template-rows: 1fr 1fr;
    column-gap: 1rem;
    row-gap: 3rem;
}

.text-space {
    padding: 0 17.2rem;
}

.card-title {
    font-size: 1.4rem;
}

.card {
    border-radius: 1rem;
}

.card-body {
    display: flex;
    width: 100%;
}

.card-wrapper {
    width: 100%;
}

.btn-wrapper {
    font-size: 0.7rem;
    width: 6rem;
}

.img-fluid {
    border-radius: 1rem;
    height: fit-content;
}

@media (max-width: 912px) {
    .grid {
        display: unset;
    }
}

</style>