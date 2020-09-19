<template>
<header>
    <div class="pad hd-top">
        <ul>
            <li class="fb">
                <img src="../assets/icons/facebook-f-brands.svg" alt="fb" />
            </li>
            <li class="inst">
                <img src="../assets/icons/instagram-brands.svg" alt="inst" />
            </li>
            <li class="twtt">
                <img src="../assets/icons/twitter-brands.svg" alt="twtt" />
            </li>
        </ul>
    </div>
    <div class="pad headr">
        <div class="hdr_logo">
            <img src="../assets/images/LOGO11.png" alt="logo_pureweb" />
        </div>
        <div class="search">
            <ul>
                <li>
                    <img class="search_ico" src="../assets/icons/search-solid.svg" alt="search" />
                </li>
                <li>
                    <img class="lock_ico" src="../assets/icons/lock-solid.svg" alt="search" />
                </li>
            </ul>
        </div>
    </div>
    <div class="pad hd-bottom">
        <nav>
            <ul>
                <router-link to tag="li">Home</router-link>
                <router-link to tag="li">About Us</router-link>
                <router-link to tag="li">Our Solution</router-link>
                <router-link to tag="li">Our Clients</router-link>
                <router-link to tag="li">Events</router-link>
                <router-link to tag="li">Careers</router-link>
                <router-link to tag="li">Get Quote</router-link>
                <router-link to tag="li">Contact Use</router-link>
            </ul>
        </nav>
    </div>
</header>
</template>

<script>
export default {
    name: "Header",
};
</script>
