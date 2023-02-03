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

    <div >

        <div >
            <img :src="img" alt="">
        </div>

        <h5>
            {{series}}
        </h5>

    </div>

</template>

<style lang="scss" scoped>


img {
    width: 200px;
    height: 200px;
    object-fit: cover;
    object-position: top;
    
    
    
    
    
    
}


img:hover {
    cursor: pointer;


}

h5 {
    
    padding-top: 15px ;
    padding-right: 15px;
    
    
}
    
</style>
