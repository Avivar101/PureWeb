<template>
<div id="app">
    <Header />
    <HeadBody />
    <Footer />
</div>
</template>

<script>
import Header from "./components/Header";
import HeadBody from "./components/HeadBody";
import Footer from "./components/Footer";

export default {
    name: "App",
    components: {
        Header,
        HeadBody,
        Footer,
    },
};
</script>
