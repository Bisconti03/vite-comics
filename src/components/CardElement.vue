<script>
    export default {
        name: 'CardElement',
        props : {
            series : String,
            img : String,
        }
    }

</script>


<template>

    <div>

        <div>
            <img :src="img" alt="">
        </div>

        <h5>
            {{series}}
        </h5>

    </div>

</template>

<style lang="scss" scoped>

h5 {
    
    padding-top: 10px;
}
    
</style>
