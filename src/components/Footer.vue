<template>
    <footer>
        <div class="d-flex justify-content-between align-items-center">
            <div class="logo">
                <img src="../assets\img\logotype-2-150x25.png" alt="">
            </div>
            <div class="navbar">
                <ul class="d-flex">
                    <li v-for="(name, index) in navbar" :key="index" class="d-inline-block ms-5"><a :href="name.href">{{name.name}}</a></li>
                </ul>
            </div>
            <div class="social d-flex align-items-center">
                <div>
                    <i class="fab fa-instagram me-3"></i>
                </div>
                <div>
                    <i class="fab fa-linkedin-in me-3"></i>
                </div>
                <div>
                    <i class="fab fa-facebook-f me-3"></i>
                </div>
                <div>
                    <i class="fab fa-twitter me-3"></i>
                </div>
                
            </div>
        </div>
        <hr>
        <div class="d-flex justify-content-between">
            <div>
                <a href="#">Terms of use</a>
                <br>
                <a href="#">Privacy Environmental Policy</a>
            </div>
            <div class="Copriryght">
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
    padding: 80px 160px 0 160px;
    hr{
        margin-top: 60px;
        margin-bottom: 40px;
    }
    ul{
        margin-bottom: 0;
    }
    a{
        color: $aColor;
    }
    .Copriryght{
        color: $aColor;
    }
}

</style>