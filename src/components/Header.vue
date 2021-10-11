<template>
    <div class="header-             top pt-4">
        <div class="container-fluid new-container d-flex justify-content-between">
            <div class="logo">
                <img src="../assets/img/logotype.png" alt="logo">
            </div>
            <div class="navbar">
                <ul class="d-flex">
                    <li v-for="(name, index) in navbar" :key="index" class="d-inline-block ms-5"><a :href="name.href">{{name.name}}</a></li>
                </ul>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: "Header",
    data(){
        return{
            navbar:[
                {
                    name: "HOME",
                    href: "#"
                },
                {
                    name: "ABOUT",
                    href: "#"
                },
                {
                    name: "PROJECT",
                    href: "#"
                },
                {
                    name: "SERVICES",
                    href: "#"
                },
                {
                    name: "BLOG",
                    href: "#"
                },
                {
                    name: "CONTACT",
                    href: "#"
                },
            ]
        }
    }
}
</script>

<style lang="scss" scoped>
@import "../assets/style/common";
    .logo {
        height: 20px;

        img {
            height: 100%;
        }
    }

    a {
        color: $aColor;

        &:hover {
            color: $aColor;
        }
    }

</style>