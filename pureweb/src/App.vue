<template>
<div id="app">
    <Header />
    <HeadBody />
</div>
</template>

<script>
import Header from "./components/Header";
import HeadBody from "./components/HeadBody";

export default {
    name: "App",
    components: {
        Header,
        HeadBody,
    },
};
</script>
