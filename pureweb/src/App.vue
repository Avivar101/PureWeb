<template>
<div id="app">
    <Header />
    <HeadSlide />
</div>
</template>

<script>
import Header from "./components/Header";
import HeadSlide from "./components/HeadSlider";

export default {
    name: "App",
    components: {
        Header,
        HeadSlide,
    },
};
</script>
