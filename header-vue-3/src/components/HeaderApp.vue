<template>
    <div>
        <p v-for="testo in navbar">
            {{ testo }}
        </p>
    </div>
</template>

<script>
    import NavLink from './NavLink.vue'

    export default{
        name: "HeaderApp,",
    
        data() {
            return {
               navbar:[
                {
                    name: Home,
                    link: www.google.com,
                }
               ]
            };
        },
    }
</script>

<style lang="scss" scoped>

</style>