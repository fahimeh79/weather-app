<template>
    <div class="flex flex-row justify-between px-[24px] pt-4 pb-[40px]">
      <div class="flex flex-row justify-between gap-12 ">
        <div class="flex flex-row items-center">
          <img src="../assets/header/location.svg" alt="location" class="">
          <p class="font-Montserrat font-normal text-[16px] text-[#FEFEFE]" > Iran.Tehran</p>
        </div>
        
        <div class="flex flex-row gap-2 bg-[#1E1E1E] rounded-[10px] px-4 py-2 w-[500px] ">
            <!-- <i class="fas fa-search search"></i> -->
            <img src="../assets/header/searching.svg" alt="" class="">
            <input type="text" class=" text-[#EDEDED] bg-[#1E1E1E] font-normal text-sm w-[500px]" placeholder="Search City"
            v-model="city" @keyup.enter =  >
        </div>
      </div>
      
      <ToggleButton></ToggleButton>
    </div>
</template>

<script>
import axios from "axios";
import ToggleButton from './ToggleButton.vue';
export default {
    name:'header',
    components:{
        ToggleButton,

    },
    data() {
      return {
        city:'',
        weatherData:null,
      };
    },

    methods: {
   
  }
}


</script>
<style scoped>

i{
  color: white;
}
 span{
  display: flex;
  flex-direction: row;
}


</style>