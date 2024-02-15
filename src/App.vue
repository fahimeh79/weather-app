<template>
  <AppHeader> </AppHeader>

<div class="flex flex-row justify-between px-[24px] pb-4">
  <CurrentWeather > </CurrentWeather>
  <ForecastWeather></ForecastWeather>
  <ChartDay></ChartDay>
</div>
<div class="pt-[10px] flex flex-row justify-between px-[24px] pb-4">
  <OverView></OverView>
  <Picture></Picture>
  <RecentCity></RecentCity>
</div>

</template>

<script >
import AppHeader from "./components/AppHeaderTOP.vue"
import CurrentWeather from "./components/ViweWheather.vue"
import ChartDay from "./components/Chart.vue"
import OverView from "./components/OverView.vue"
import Picture from "./components/Picture.vue"
import RecentCity from "./components/RecentlyCity.vue"
import axios from 'axios'
import ForecastWeather from "./components/ForecastWeather.vue"

export default{
name:'App',
components:{
  AppHeader,
  CurrentWeather, ForecastWeather, ChartDay,
  OverView, Picture, RecentCity,
  ForecastWeather
},
}

</script>
<style scoped>
*{
background:#111015;
margin: 0;
padding: 0;
}</style>