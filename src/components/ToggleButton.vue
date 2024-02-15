<template>
    <div>
      <input type="checkbox" id="toggle" v-model="isToggled" class="toggle-checkbox">
      <label for="toggle" class="toggle-label">
        <div class="toggle-inner"></div>
        <div class="toggle-slider"> <span class="p-[20%]"> &deg;f</span></div>
      </label>
    </div>
  </template>
  
  <style scoped>
  .toggle-checkbox {
    display: none;
  }
  
  .toggle-label {
    /* display: block; */
    /* width: 24px;
    height: 24px; */
    position: relative;
    /* border-radius: 24px; */
    /* background-color: #ccc; */
  }
  
  .toggle-inner {
    /* width: 100%;
    height: 100%; */
    width: 80px;
    height: 40px;
    border:1px solid #626161;
    border-radius: 24px;
    /* background-color: #fff; */
    transition: background-color 0.3s;
  }
  
  .toggle-slider {
    position: absolute;
    top:20%;
    left: 0;
    width: 32px;
    height: 32px;
    border-radius: 50%;
    background-color: #D8E9F9;
    transition: left 0.3s;
  }
  
  input[type="checkbox"]:checked + .toggle-label .toggle-inner {
    background-color: #19191B; /* Color when toggle is on */
  }
  
  input[type="checkbox"]:checked + .toggle-label .toggle-slider {
    left: 50px;
  }
  </style>
  
  <script>
  export default {
    data() {
      return {
        isToggled: false
      }
    }
  }
  </script>
  