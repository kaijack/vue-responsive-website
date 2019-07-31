<template>
  <div class="text-center">
    <div id="slider">
      <figure>
        <img
          src="https://www.youredm.com/wp-content/uploads/2019/07/190722-000357-TML2019-julienduvalphoto.jpg"
        />
        <img src="https://i.ytimg.com/vi/06eSsOWcKYA/maxresdefault.jpg" />
        <img
          src="https://www.youredm.com/wp-content/uploads/2018/07/fish-eye-fireworks-tomorrowland-2018.jpg"
        />
      </figure>
    </div>
  </div>
</template>
<style scoped>
#slider {
  overflow: hidden;
  max-width: 1280px;
  max-height: 800;
  float: center;
}

@keyframes slider {
  0% {
    left: 0;
  }
  30% {
    left: 0;
  }
  33% {
    left: -100%;
  }
  63% {
    left: -100%;
  }
  66% {
    left: -200%;
  }
  95% {
    left: -200%;
  }
  100% {
    left: 0;
  }
}
#slider figure {
  width: 300%;
  position: relative;
  animation: 9s slider infinite;
}

#slider figure:hover {
  animation-play-state: paused;
}
#slider figure img {
  width: 33.333333333%;
  height: 100%;
  float: left;
}
</style>

