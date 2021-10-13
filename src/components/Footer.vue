<template>
    <footer>
        <div class="d-flex justify-content-between">
            <div class="logo">
                <img src="../assets\img\logotype-2-150x25.png" alt="">
            </div>
            <div class="navbar">
                <ul class="d-flex">
                    <li v-for="(name, index) in navbar" :key="index" class="d-inline-block ms-5"><a :href="name.href">{{name.name}}</a></li>
                </ul>
            </div>
            <div class="social">
                <i class="fab fa-instagram"></i>
                <i class="fab fa-linkedin-in"></i>
                <i class="fab fa-facebook-f"></i>
                <i class="fab fa-twitter"></i>
            </div>
        </div>
        <hr>
        <div class="d-flex justify-content-between">
            <div>
                <a href="#">Terms of use</a>
                <br>
                <a href="#">Privacy Environmental Policy</a>
            </div>
            <div>
                Copriryght &copy; 2020 Phlox Consulting. All Rights Reserved.
            </div>
        </div>
    </footer>
</template>

<script>
export default {
    name: "Footer",
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
footer{
    height: 320px;
    background-color: $principalBackground;


}

</style>