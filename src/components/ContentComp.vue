<template>
  <div class="card">
    <img class="flex" v-bind:src="dettagliFumetto.thumb" :alt="dettagliFumetto.type">
    <h4 class="flex"> {{dettagliFumetto.series}}</h4>
    
  </div>

</template>

<script>
export default {
    
name: 'ContentComp',
props: {
    dettagliFumetto: Object
}

}
</script>

<style lang="scss" scoped>

    .flex{
        display: flex;
    }

    h4 {
        text-align: start;
    }


    .card {
        width: calc(100% / 6);
        padding: 10px 0;
    }

</style>

