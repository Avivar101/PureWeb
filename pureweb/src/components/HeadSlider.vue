<template>
<section>
    <div class="slide">
        <div class="slider1">
            <div class="img-slidr">
                <div class="container">
                    <h4>STAY AHEAD OF THE DIGITAL GAME</h4>
                    <h2>
                        WE ARE
                        <span>PUREWEB</span>
                    </h2>
                    <p>
                        Delivering digital transformation that will enable you to power efficiently,
                        <br />divine growth and build credibility for your business
                    </p>
                    <nav>
                        <ul>
                            <router-link to tag="li">Contact Us</router-link>

                            <router-link to tag="li">Get Quote</router-link>
                        </ul>
                    </nav>
                </div>
                <div class="imgs">
                    <span class="img1">
                        <img src="../assets/images/sliders/women.png" alt="woman" />
                    </span>
                    <div class="img2">
                        <img src="../assets/images/sliders/itab.png" alt="tab" />
                    </div>
                    <span class="img3">
                        <img src="../assets/images/sliders/fruit_bowl.png" alt="cup" />
                    </span>
                </div>
            </div>
        </div>
    </div>
    <div class="pad slidr-botm">
        <div class="hovers">
            <div class="hovr hovrBlck1">
                <h3>CUSTOMERS</h3>
                <p>
                    2,281+ Happy
                    Customers
                </p>
            </div>
            <div class="hovr hovrBlck2">
                <h3>Projects</h3>
                <p>
                    2000+ Projects
                    Completed
                </p>
            </div>
            <div class="hovr hovrBlck3">
                <h3>experience</h3>
                <p>
                    15+ years of
                    Experience
                </p>
            </div>
        </div>
        <div class="text">
            <div class="txt">
                <h6>LETS GROW YOUR BUSINESS</h6>
                <p>With our software and web solutions</p>
            </div>
            <router-link to tag="li">Get a free Quote</router-link>
        </div>
    </div>
</section>
</template>

<script>
export default {
    name: "HeadSlide",
};
</script>
