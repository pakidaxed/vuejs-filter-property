<template>
    <div class="filter">
        <p>Filter:</p>
    </div>
</template>

<script>
    export default {
        name: "Filter",
        data(){
            return {
                filters: [{
                    vln: 'Vilnius',
                    kns: 'Kaunas',
                    klp: 'Klaipėda'
                }]
            }
        }
    }
</script>

<style scoped>

</style>