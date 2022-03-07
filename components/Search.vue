<template>
    <section class="team section-padding" id="team">
          <div class="container">
            <div class="row">
                <div class="col-md-12">
                    <div class="section-header text-center pb-5">
                        <h2>Search a best place in the world</h2>
                        <p class="text-space">Whether you're looking for a vacation. We are here to Guide you about the details you need to check in and ease your trips in advance</p>
                    </div>
                </div>
            </div>
            <div class="row grid">
                <div class="col-xl-12 col-md-6 col-lg-3 p-0">
                    <div class="card">
                        <div class="card-body">
                            <img src="../img/team-1.jpg" alt="" class="img-fluid">
                            <div class="card-wrapper">
                                <h3 class="card-title pt-3 m-0">Batu, East Java</h3>
                                <p class="card-text">86 Destinations</p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-xl-12 col-md-6 col-lg-3 p-0">
                    <div class="card">
                        <div class="card-body">
                            <img src="../img/team-1.jpg" alt="" class="img-fluid">
                            <div class="card-wrapper">
                                <h3 class="card-title pt-3 m-0">Kuta</h3>
                                <p class="card-text">86 Destinations</p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-xl-12 col-md-6 col-lg-3 p-0">
                    <div class="card">
                        <div class="card-body">
                            <img src="../img/team-1.jpg" alt="" class="img-fluid">
                            <div class="card-wrapper">
                                <h3 class="card-title pt-3 m-0">Surabaya, East Java</h3>
                                <p class="card-text">86 Destinations</p>
                            </div>
                        </div>
                    </div>
                </div> 
                <div class="col-xl-12 col-md-6 col-lg-3 p-0">
                    <div class="card">
                        <div class="card-body">
                            <img src="../img/team-1.jpg" alt="" class="img-fluid">
                            <div class="card-wrapper">
                                <h3 class="card-title pt-3 m-0">Malang, East Java</h3>
                                <p class="card-text">86 Destinations</p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-xl-12 col-md-6 col-lg-3 p-0">
                    <div class="card">
                        <div class="card-body">
                            <img src="../img/team-1.jpg" alt="" class="img-fluid">
                            <div class="card-wrapper">
                                <h3 class="card-title pt-3 m-0">Dieng, Central Java</h3>
                                <p class="card-text">86 Destinations</p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-xl-12 col-md-6 col-lg-3 p-0">
                    <div class="card">
                        <div class="card-body">
                            <img src="../img/team-1.jpg" alt="" class="img-fluid">
                            <div class="card-wrapper">
                                <h3 class="card-title pt-3 m-0">Nusa Dua, Lombok</h3>
                                <p class="card-text">86 Destinations</p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-xl-12 col-md-6 col-lg-3 p-0">
                    <div class="card">
                        <div class="card-body">
                            <img src="../img/team-1.jpg" alt="" class="img-fluid">
                            <div class="card-wrapper">
                                <h3 class="card-title pt-3 m-0">Bandung, West Java</h3>
                                <p class="card-text">86 Destinations</p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-xl-12 col-md-6 col-lg-3 p-0">
                    <div class="card">
                        <div class="card-body">
                            <img src="../img/team-1.jpg" alt="" class="img-fluid">
                            <div class="card-wrapper">
                                <h3 class="card-title pt-3 m-0">Wakatobi, Sumatera</h3>
                                <p class="card-text">86 Destinations</p>
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
@media (max-width: 912px) {
    .header-text {
        text-align: center;
    }
}
</style>

<style scoped>

.grid {
    display: grid;
    grid-template-columns: 1fr 1fr 1fr 1fr;
    grid-template-rows: 1fr 1fr;
    column-gap: 1rem;
    row-gap: 3rem;
}

.text-space {
    padding: 0 0;
}

.card-title {
    font-size: 1.2rem;
}

.card {
    border-radius: 1rem;
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