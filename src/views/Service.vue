<template>

<section>

    <Caption/>
    <Card/>
</section>
</template>



<script>
import Caption from '../components/Service/Caption.vue'
import Card from '../components/Service/Cards.vue'
export default{
    name:"Sevice",
    components:{
        Caption,
        Card
    }
}
</script>