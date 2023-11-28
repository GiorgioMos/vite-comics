<script>
export default {
    name: "MenuLinks",
    data() {
        return {
            menuLinks: [
                {
                    text: "Characters",
                    url: "#",
                },
                {
                    text: "Comics",
                    url: "#",
                },
                {
                    text: "Movies",
                    url: "#",
                },
                {
                    text: "TV",
                    url: "#",
                },
                {
                    text: "Games",
                    url: "#",
                },
                {
                    text: "Collectibles",
                    url: "#",
                },
                {
                    text: "Videos",
                    url: "#",
                },
                {
                    text: "Fans",
                    url: "#",
                },
                {
                    text: "News",
                    url: "#",
                },
                {
                    text: "Shop",
                    url: "#",
                },
            ]
        }
    }
}
</script>

<template>
    <div id="header-flex">
        <img src="../assets/dc-logo.png" alt="DC logo">
        <a v-for="link in menuLinks" :href="link.url">{{ link.text }}</a>
    </div>
</template>

<style scoped>
a {
    text-decoration: none;
    margin: 0 1rem;
    color: black;
}

a:hover {
    color: rgb(0, 119, 255);
}

img {
    height: 80px;
    margin-right: 400px;
}

#header-flex {
    display: flex;
    align-items: center;
    padding: 10px 0;
    margin: 0 15%;
}
</style>
