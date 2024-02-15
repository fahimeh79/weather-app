<template>
    <div class="flex flex-col gap-[16px]">
      <h2 class="font-Montserrat font-medium text-[20px] leading-[24.3px] text-[#FFFFFF]">Today </h2>
      <div class="flex flex-col h-[226px]">
        <div class="flex flex-row justify-between items-center bg-[#AECADF] rounded-t-3xl h-[52px] p-[16px]">
          <span class="font-Montserrat font-semibold text-[16px] leading-[19.5px] text-[#0F0F11]"> friday</span>
          <span class="font-Montserrat font-semibold text-[16px] leading-[19.5px] text-[#0F0F11]">12:44 AM</span>
        </div>
        <div class="bg-[#BBD7EC] w-[257px]  rounded-b-3xl ">
          <div class="flex flex-row gap-[35px]">
            <span class=" font-semibold font-Montserrat p-[16px] text-[64px] leading-[78.02px]"> 16</span>
            <!-- <img :src=" 'http://openweathermap.org/img/w/' + weatherData.weather[0].icon + '.png'" alt="weather" > -->
          </div>
          <div class="p-[16px] grid grid-cols-2 gap-x-[50px]">
            <div class="text-[#4F5658] font-Montserrat leading-[18px] text-[12px] font-normal ">Feels like<span class="text-[#0F0F11] font-Montserrat leading-[18px]  font-semibold text-[12px]">18&deg;</span></div>
            <div class="text-[#4F5658] font-Montserrat leading-[18px] text-[12px] font-normal "> Sunrise <span class="text-[#0F0F11] font-Montserrat leading-[18px]  font-semibold text-[12px]">05:30</span></div>
            <div class="text-[#214c58] font-Montserrat leading-[18px] text-[12px] font-normal ">Pressure  <span class="text-[#0F0F11] font-Montserrat leading-[18px]  font-semibold text-[12px]">100MB</span></div>
            <div class="text-[#4F5658] font-Montserrat leading-[18px] text-[12px] font-normal ">Sunset  <span class="text-[#0F0F11] font-Montserrat leading-[18px]  font-semibold text-[12px]"> 18:45</span></div>

          </div>
        </div>
      </div>
    </div>
</template>

<script>
export default{
  name:'Today',
  components:{

  },
  data(){
    return{
    
    }
  },
  
  }
</script>
<style scoped>
 
</style>
