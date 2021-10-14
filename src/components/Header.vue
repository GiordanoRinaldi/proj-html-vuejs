<template>
    <div class="header-top pt-4">
        <div class="container-fluid new-container d-flex justify-content-between">
            <div class="logo">
                <img src="../assets/img/logotype.png" alt="logo">
            </div>
            <div class="navbar">
                <ul class="d-flex">
                    <li v-for="(name, index) in navbar" :key="index" class="d-inline-block ms-5" ><a :class="name.active == true ? 'active' :  '' " :href="name.href">{{name.name}}</a></li>
                </ul>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: "Header",
    props: [ "navbar"]
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
        position: relative;
        color: $aColor;
        &:hover {
            color: white;
            transition: 0.4s;
        }
        &:hover:before {
            position: absolute;
            top: -35px;
            content: '';
            display: inline-block;
            width: 100%;
            border: 4px solid white;
        }
    }
    .active{
        color: white;
        &:before {
            position: absolute;
            top: -35px;
            content: '';
            display: inline-block;
            width: 100%;
            border: 4px solid white;
        }
    }

</style>