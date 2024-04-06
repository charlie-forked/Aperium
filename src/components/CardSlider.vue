<template>
    <div class="container w-full">
      <div class="moving-element flex justify-between">
        <Card 
          href="https://google.com"
          title="Card Title"
          role="CEO"
          body="Content of the card."
          image="https://cdn.discordapp.com/avatars/795996972758204426/1fedd8ab05818df52c73fc621bb8f816?size=1024"
        />
        <Card 
          href="https://google.com"
          title="Card Title"
          role="CEO"
          body="Content of the card."
          image="https://cdn.discordapp.com/avatars/795996972758204426/1fedd8ab05818df52c73fc621bb8f816?size=1024"
        /> 
      </div>
    </div>
  </template>
  
  <script>
  import Card from './Card.vue';
  
  export default {
    components: {
      Card,
    },
  };
  </script>
  
  <style>
  .container {
    position: relative;
    width: 100%;
    height: 200px;
    overflow: hidden;
    margin-right: 25px;
    padding-right: 25px;
  }
  
  .moving-element {
    position: absolute;
    top: 50%;
    width: 210px;
    height: 50px;
    right: 0;
    background-color: rgb(126, 126, 231);
    animation: moveRightToLeft 10s linear infinite;
    display: flex;
  }

  .moving-element > * {
    
    padding-right: 20px; 
}
  
  @keyframes moveRightToLeft {
    0% {
      right: 0;
    }
    100% {
      right: 100%;
    }
  }
  </style>
  