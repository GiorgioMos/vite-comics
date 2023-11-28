<script>
export default {
    name: "Icons",
    data() {
        return {
            Icons: [
                {
                    img: "../assets/buy-comics-digital-comics.png",
                    text: "Digital Comics",
                    link: "#",
                },
                {
                    img: "../assets/buy-comics-merchandise.png",
                    text: "DC Merchandise",
                    link: "#",
                },
                {
                    img: "../assets/buy-comics-subscriptions.png",
                    text: "Subscription",
                    link: "#",
                },
                {
                    img: "../assets/buy-comics-shop-locator.png",
                    text: "Comic Shop Locator",
                    link: "#",
                },
                {
                    img: "../assets/buy-dc-power-visa.svg",
                    text: "DC Power Visa",
                    link: "#",
                },
            ]
        }
    }
}
</script>

<template>
    <div id="Icons">
        <img v-for="Icon in Icons" :src="Icon.img" alt="Icon-image">
        <a v-for="Icon in Icons" :href="Icon.link">{{ Icon.text }}</a>
    </div>
</template>

<style>
#Icons {
    background-color: #0282f9;
    height: 200px;
    display: flex;
    align-items: center;
    justify-content: center;
}
</style>