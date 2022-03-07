<template>
    <div class="content-wrapper">
        <section class="call-to-action text-white">
            <div class="container">
                <div class="content">
                    <div>
                        <div class="col-xl-9 pl-0">
                            <h2 class="mb-4">Get our pro offers</h2>
                        </div>
                        <div>
                            <p>Create a visual identity for your company, and an overall brand</p>
                        </div>
                    </div>
                    <div class="col-md-10 col-lg-8 col-xl-12 wrapper">
                    <form action="">
                        <div class="row">
                            <div class="col-xl-12 col-md-12 mb-2 mb-md-0 p-0">
                                <input type="email" class="form-control form-control-lg form-wrapper" placeholder="Type your email here">
                            </div>
                            <div class="button">
                                <button type="submit" class="btn btn-block btn-lg btn-dark text-white btn-wrapper">Subscribe</button>
                            </div>
                        </div>
                    </form>
                    </div>
                </div>
            </div>
        </section>
    </div>
</template>

<script>
import "../css/custom.css"
export default {
  
}
</script>

<style scoped>
.content-wrapper {
    display: grid;
    justify-content: center;
}
.content {
    display: grid;
    grid-template-columns: 1.5fr 2fr;
    column-gap: 5rem;
}
.wrapper {
    display: grid;
    align-items: end;
    position: relative;
}
.button {
    position: absolute;
    right: 0.7rem;
    top: 4.3rem;
}
.form-wrapper {
  padding: 2rem 1rem;
}

@media (max-width: 1024px) {
    .call-to-action {
        width: 59rem !important;
    }
    .content {
        display: unset;
    }
    .button {
        right: 0.5rem;
        top: 0.8rem;
    }
    .btn-wrapper {
        font-size: 1rem;
    }
    .form-wrapper {
        padding: 2rem 1rem;
        font-size: 1rem;
    }
}

@media (max-width: 912px) {
    .call-to-action {
        width: 43rem !important;
    }
    .content {
        display: unset;
    }
}


@media (max-width: 600px) {
  .call-to-action {
    width: 22rem !important;
  }
  .content {
      display: unset;
  }
}

@media (max-width: 540px) {
  .call-to-action {
    width: 31.5rem !important;
  }
  .content {
      display: unset;
  }
}

@media (max-width: 415px) {
  .call-to-action {
    width: 23.5rem !important;
  }
  .content {
      display: unset;
  }
}

@media (max-width: 394px) {
  .call-to-action {
    width: 22.5rem !important;
  }
  .content {
      display: unset;
  }
}

@media (max-width: 360px) {
  .call-to-action {
    width: 20.5rem !important;
  }
  .content {
      display: unset;
  }
}

@media (max-width: 280px) {
  .call-to-action {
    width: 15.5rem !important;
  }
  .content {
      display: unset;
  }
}

</style>