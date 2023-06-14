<template>
    <section class="hero">
        <div class="container h-100 d-flex align-items-center">
            <div class="row">
                <div class="col-6 d-flex flex-column justify-content-center align-items-start">
                    <div class="hero-text w-100">
                        <h1 class="display-5 fw-bolder mb-3 lh-sm">
                            Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standar
                        </h1>
                        <p class="text-secondary">
                            "Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit..."
                            "There is no one who loves pain itself, who seeks after it and wants to have it, simply because it is pain..."
                        </p>
                        
                    </div>
                    <button class="btn btn-hero btn-primary rounded-pill px-5 mt-5">masuk</button>
                </div>
                
                <div class="col-6 d-flex justify-content-end">
                    <img class="ilustration" src="../assets/hero.png" alt="ilustration">
                    
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

    button.btn-hero {
        background-color: black;
        border: 0;
    }
</style>