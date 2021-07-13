<template>
    <div>
        <h1 >{{a}}</h1>
        <button v-on:click="increment()"> Increment</button>
    </div>
</template>
<script>

export default {
    name: "Increment",
    data(){
        return {a:0}
    },
    methods:{
        increment(){
            this.a++
          }
    }
}
</script>
