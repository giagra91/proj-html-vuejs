<template>
    <div>
        <MyJumbo />
        <SocietyInfo />
        <MainServices />
        <Logistics />
        <SubsciptionForm />
    </div>
</template>

<script>
import MyJumbo from "./MainFolder/Jumbo.vue"
import SocietyInfo from "./MainFolder/SocietyInfo.vue"
import MainServices from "./MainFolder/MainServices.vue"
import Logistics from "./MainFolder/Logistics.vue"
import SubsciptionForm from "./MainFolder/SubsciptionForm.vue"


export default {
    name: "HomeMain",
    components:{
        MyJumbo,
        SocietyInfo,
        MainServices,
        SubsciptionForm,
        Logistics
    },

}
</script>

<style lang="scss" scoped>


</style>