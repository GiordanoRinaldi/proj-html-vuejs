<template>
    <div class="header">
        <div class="logo">
            <img src="../assets/img/logotype.png" alt="logo">
        </div>
        <div class="navbar">
            <ul>
                <li v-for="(name, index) in navbar" :key="index"><a :href="name.href">{{name.name}}</a></li>
            </ul>
        </div>

    </div>
</template>

<script>
export default {
    name: "header",
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

<style>

</style>