<script setup>
defineProps({
  msg: {
    type: String,
    required: true
  }
})
</script>

<template>
  
    <header>

  <nav class="navbar bg-body-tertiary">
  <div class="container-fluid">
    <a class="navbar-brand">
    <img class="logo" src="../assets/logo.png" alt="" style="width: 100px;">
    </a>
    <form class="d-flex" role="search">
      <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
      <button class="btn btn-outline-success" type="submit">Search</button>
    </form>
  </div>
</nav>

    </header>
    <section class="hero">
        <div class="container col-xxl-8 px-4 py-5">
            <div class="row flex-lg-row-reverse align-items-center g-5 py-5">
              <div class="col-10 col-sm-8 col-lg-6">
                
<img src="../assets/foto.jpg" alt="" style="width: 400px;">
<lottie-player src="https://assets3.lottiefiles.com/packages/lf20_sk5h1kfn.json" background="transparent" speed="1"
style="width: 100%; height: auto;" loop autoplay></lottie-player>
              </div>
              <div class="col-lg-6">
                <h1 class="display-5 fw-bold lh-1 mb-3">Terkadang kita diuji bukan untuk menunjukkan kelemahan kita, tetapi untuk menemukan kekuatan kita.</h1>
                <p class="lead">Quickly design and customize responsive mobile-first sites with Bootstrap, the world’s most popular front-end open source toolkit, featuring Sass variables and mixins, responsive grid system, extensive prebuilt components, and powerful JavaScript plugins.</p>
                <div class="d-grid gap-2 d-md-flex justify-content-md-start">
                  <button type="button" class="btn btn-primary btn-lg px-4 me-md-2" fdprocessedid="r1q9el">Primary</button>
                  <button type="button" class="btn btn-outline-secondary btn-lg px-4" fdprocessedid="pq0vp">Default</button>
                </div>
              </div>
            </div>
          </div>
    </section>
   
    <section class="produk text-center">
        <div class="container">
            <div class="align-items-center mb-3 row">
                <div class="col-lg-9 ms-auto me-auto">
                    <h1 class="h1 mb-1 text-dark">
                        Daftar Produk
                    </h1>
                    <p>Quickly design and customize responsive mobile-first sites with Bootstrap, the world’s</p>
                </div>
                
                <div class="row pt-5">
                    <div class="col-lg-3 col-sm-6">
                        <svg xmlns="http://www.w3.org/2000/svg" width="50" height="80" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-airplay"><path d="M5 17H4a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2h16a2 2 0 0 1 2 2v10a2 2 0 0 1-2 2h-1"/><polygon points="12 15 17 21 7 21 12 15"/></svg>
                        <h3 class="text-dark fw-normal pt-3">
                            Produk 1
                        </h3>
                        <p>
                            Quickly design and customize responsive mobile-first sites with Bootstrap, the world’s most popular front-end open source toolkit, featuring Sass variables and mixins, responsive grid system, extensive prebuilt components, and powerful JavaScript plugins.
                        </p>
                    </div>
                    <div class="col-lg-3 col-sm-6">
                        <svg xmlns="http://www.w3.org/2000/svg" width="50" height="80" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-airplay"><path d="M5 17H4a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2h16a2 2 0 0 1 2 2v10a2 2 0 0 1-2 2h-1"/><polygon points="12 15 17 21 7 21 12 15"/></svg>
                        <h3 class="text-dark fw-normal pt-3">
                            Produk 1
                        </h3>
                        <p>
                            Quickly design and customize responsive mobile-first sites with Bootstrap, the world’s most popular front-end open source toolkit, featuring Sass variables and mixins, responsive grid system, extensive prebuilt components, and powerful JavaScript plugins.
                        </p>
                    </div>
                    <div class="col-lg-3 col-sm-6">
                        <svg xmlns="http://www.w3.org/2000/svg" width="50" height="80" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-airplay"><path d="M5 17H4a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2h16a2 2 0 0 1 2 2v10a2 2 0 0 1-2 2h-1"/><polygon points="12 15 17 21 7 21 12 15"/></svg>
                        <h3 class="text-dark fw-normal pt-3">
                            Produk 1
                        </h3>
                        <p>
                            Quickly design and customize responsive mobile-first sites with Bootstrap, the world’s most popular front-end open source toolkit, featuring Sass variables and mixins, responsive grid system, extensive prebuilt components, and powerful JavaScript plugins.
                        </p>
                    </div>
                    <div class="col-lg-3 col-sm-6">
                        <svg xmlns="http://www.w3.org/2000/svg" width="50" height="80" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-airplay"><path d="M5 17H4a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2h16a2 2 0 0 1 2 2v10a2 2 0 0 1-2 2h-1"/><polygon points="12 15 17 21 7 21 12 15"/></svg>
                        <h3 class="text-dark fw-normal pt-3">
                            Produk 1
                        </h3>
                        <p>
                            Quickly design and customize responsive mobile-first sites with Bootstrap, the world’s most popular front-end open source toolkit, featuring Sass variables and mixins, responsive grid system, extensive prebuilt components, and powerful JavaScript plugins.
                        </p>
                    </div>
                </div>
            </div>

        </div>

    </section>
    
</template>

<script>
export default {
  name: 'TugasPW',
  props: {
    msg: String
  }
}
</script>

<style scoped>
h1 {
  font-weight: 500;
  font-size: 2.6rem;
  top: -10px;
}

h3 {
  font-size: 1.2rem;
}

.greetings h1,
.greetings h3 {
  text-align: center;
}
</style>
