<template>
    <section class="hero">
        <div class="container h-100 d-flex align-items-center">
            <div class="row">
                <div class="col-6 d-flex flex-column justify-content-center align-items-start">
                    <div class="hero-text w-100">
                        <h1 class="display-5 fw-bolder mb-3 lh-sm">
                            Bingung mau berlangganan aplikasi, tapi harga mahal?
                        </h1>
                        <p class="text-secondary">
                            Premiuminaja, toko serba ada, tapi sering kosong stoknya. Harga merakyat (bagian jakarta selatan). Tunggu apalagi klik “lihat produk”
                            dibawah ini sekarang juga.
                        </p>
                        
                    </div>
                    <button class="btn btn-hero btn-primary rounded-pill px-5 mt-5">Lihat Produk</button>
                </div>
                
                <div class="col-6 d-flex justify-content-end">
                    <img class="logo-spotify mb-lg-5" src="../assets/spotify-logo.svg" alt="logo-spotify">
                    <img class="logo-netflix mb-lg-5" src="../assets/Netflix-logo.svg" alt="logo-netflix" width="83">
                    <img class="logo-wetv" src="../assets/Tencent-Video.svg" alt="logo-wetv" width="202">
                    <img class="ilustration" src="../assets/hero-object.svg" alt="ilustration" width="375.92">
                    
                </div>
            </div>
            
        </div>
    </section>
  </template>

<style>
    .hero-text h1{
        font-family: nohemi;
        font-weight: 600;
        color: #1E1E1E;
        font-size: 50px;
        /* line-height: 60px; */
    }

    section.hero {
        height: 85vh;
        background-image: url("../assets/hero-back.svg");
        background-repeat: no-repeat;
        background-size: 100% 200%;
        background-position: 0 -100px;
        
    }

    button.btn-hero {
        background-color: black;
        border: 0;
    }

    .logo-wetv{
        margin-right: -60px;
        margin-bottom: 300px;
        margin-top: 10px;
        rotate:10deg;
        
    }

    .logo-netflix{
        margin-top: 20%;
        margin-right: -11em;
        rotate: 2deg;
    }

    .logo-spotify{
        width: 9vw;
        margin-right: -30em;
        margin-top: -22em;
    }
</style>