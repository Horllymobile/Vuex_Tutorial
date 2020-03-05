<template>
    <div class="content">
        <h2>Alter name:</h2>
        <input type="text" v-model="name"/>
        <br>
        <button type="submit">Swap name</button>
    </div>
</template>


<script>
    export default {
        data(){
            return {
                name:''
            }
        },
        methods:{
            swapName(){

            }
        }
    }

</script>