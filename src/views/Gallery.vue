<template>
  <div>
    <b-cointainer>
      <b-card>
        <div class="container-fluid">
          <b-card>
            <div class="text-center">
              <h1>Live Today, Love Tomorrow, Unite Forever</h1>
              <h5>TOMORROWLAND BELGIUM</h5>
            </div>
          </b-card>
          <br />
          <b-card>
            <div class="d-flex flex-row flex-wrap justify-content-center">
              <div class="d-flex flex-column">
                <img
                  src="https://live-cdn.tomorrowland.com/tmllive2019/542ce439a6a5880de4a34580b306632086b34bce_image1-7.jpeg"
                  class="img-fluid m-1 p-1 hoverable zoom"
                />
                <img
                  src="https://live-cdn.tomorrowland.com/tmllive2019/34b7c84a16fcbf8f617fa862c507b73b9d2e7345_image3-5.jpeg"
                  class="img-fluid m-1 p-1 hoverable zoom"
                />
              </div>

              <div class="d-flex flex-column">
                <img
                  src="https://i2.wp.com/www.lovethecontrary.com/wp-content/uploads/2017/08/LoveTheContrary-Tomorrowland-blog-18.jpg"
                  class="img-fluid m-1 p-1 hoverable zoom"
                  alt="hoverable"
                />

                <img
                  src="https://live-cdn.tomorrowland.com/tmllive2019/032c4491739c78bc45f244c107f451ef48fd8254_img_1310.jpg"
                  class="img-fluid m-1 p-1 hoverable zoom"
                  alt="hoverable"
                />
              </div>

              <div class="d-flex flex-column">
                <img
                  src="https://1footintherave.files.wordpress.com/2015/09/tomorrowland.jpg"
                  class="img-fluid m-1 p-1 hoverable zoom"
                  alt="hoverable"
                />
                <img
                  src="https://live-cdn.tomorrowland.com/tmllive2019/f1ba748fdc20eb11b41f7c2207d3ee7a41a56cc3_image1-23.jpeg"
                  class="img-fluid m-1 p-1 hoverable zoom"
                  alt="hoverable"
                />
              </div>

              <div class="d-flex flex-column">
                <img
                  src="https://live-cdn.tomorrowland.com/tmllive2019/d9cd747025876a075a1f5d3187b6c395e233324a_foto-21-07-19-22-50-20.jpg"
                  class="img-fluid m-1 p-1 hoverable zoom"
                  alt="hoverable"
                />

                <img
                  src="https://live-cdn.tomorrowland.com/tmllive2019/37d8b7ecf701656a01947a5463bb22e2223e04db_image1-2.jpeg"
                  alt="zoom"
                  class="img-fluid m-1 p-1 hoverable zoom"
                />
              </div>
            </div>
          </b-card>
        </div>
      </b-card>
    </b-cointainer>
  </div>
</template>

<style scoped>
.container {
  background: #f9f9f9;
}

.flex-column {
  max-width: 260px;
}
h1 {
  color: royalblue;
}
img {
  margin: 5px;
}

.scale {
  transform: scaleY(1.05);
  padding-top: 5px;
}
* {
  box-sizing: border-box;
}

.zoom {
  /* padding: 50px; */
  /* background-color: green; */
  transition: transform 0.2s;
  /* width: 200px; */
  /* height: 200px; */
  margin: 0 auto;
}

.zoom:hover {
  -ms-transform: scale(1.5); /* IE 9 */
  -webkit-transform: scale(1.5); /* Safari 3-8 */
  transform: scale(1.5);
}
</style>