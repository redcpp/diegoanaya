<template>
  <b-container fluid class="cover mvh-100">
    <b-row class="justify-content-center mvh-100">
      <b-col sm="8" md="6" lg="4" class="d-flex align-items-center">
        <b-card no-body class="shadow border-0 rounded my-3 w-100">
          <div class="gradient-bg text-center text-white p-4">
            <div class="m-4">
              <b-img rounded="circle" src="@/assets/io.jpg" class="me mb-3" />
              <h1 class="font-weight-bold title">Diego Anaya</h1>
              <p class="my-3">Software engineer. Climber. Entrepreneur.</p>
            </div>
          </div>
          <b-container fluid>
            <b-row class="p-4 mt-4 btn-50">
              <b-col sm="6" class="px-2">
                <b-button block variant="transparent" href="https://vcfplotein.liigh.unam.mx" target="_blank">
                  VCFPlotein
                  <b-img src="@/assets/plotein.png" width="18" />
                </b-button>
                <b-button block variant="transparent" href="https://amrenders.com" target="_blank">
                  AMRenders
                  <b-icon-brush-fill />
                </b-button>
                <b-button block variant="transparent" href="https://drive.google.com/file/d/1H3lRUslNRwlhDd5mg2so58NnjQ4Ssgm-/view?usp=sharing" target="_blank">
                  Resume
                  <b-icon-file-arrow-down-fill />
                </b-button>
              </b-col>
              <b-col sm="6" class="px-2">
                <b-button block variant="transparent" href="mailto:redcpp@gmail.com" target="_blank">
                  Email
                  <b-icon-mailbox-2 />
                </b-button>
                <b-button block variant="transparent" href="https://github.com/redcpp" target="_blank">
                  GitHub
                  <b-icon-github />
                </b-button>
                <b-button block variant="transparent" href="https://www.linkedin.com/in/redcpp/" target="_blank">
                  LinkedIn
                  <b-icon-linkedin />
                </b-button>
              </b-col>
            </b-row>
          </b-container>
        </b-card>
      </b-col>
    </b-row>
  </b-container>
</template>

<script>
import { BIcon, BIconBrushFill, BIconFileArrowDownFill, BIconMailbox2, BIconGithub, BIconLinkedin } from 'bootstrap-vue'

export default {
  components: {
    BIcon,
    BIconGithub,
    BIconLinkedin,
    BIconMailbox2,
    BIconBrushFill,
    BIconFileArrowDownFill
  }
}
</script>

<style>
body {
  font-family: Inter, sans-serif;
}
.title {
  letter-spacing: -0.175rem;
}
.mvh-100 {
  height: 100% !important;
  min-height: 100vh !important;
}
.cover {
  background-size: 512px, cover, cover;
  background-position-x: center, 0%, center;
  background-position-y: center, 0%, center;
  background-image: url("data:image/svg+xml;charset=utf8,%3Csvg%20xmlns%3D%22http%3A//www.w3.org/2000/svg%22%20viewBox%3D%220%200%20512%20512%22%20width%3D%22512%22%20height%3D%22512%22%20preserveAspectRatio%3D%22none%22%3E%3Cfilter%20id%3D%22noise%22%3E%3CfeTurbulence%20type%3D%22fractalNoise%22%20baseFrequency%3D%220.875%22%20result%3D%22noise%22%20/%3E%3CfeColorMatrix%20type%3D%22matrix%22%20values%3D%220%200%200%200%200%200%200%200%200%200%200%200%200%200%200%200%200%200%200.328125%200%22%20/%3E%3C/filter%3E%3Crect%20filter%3D%22url%28%23noise%29%22%20x%3D%220%22%20y%3D%220%22%20width%3D%22512%22%20height%3D%22512%22%20fill%3D%22transparent%22%20opacity%3D%221%22%20/%3E%3C/svg%3E"), linear-gradient(45deg, rgba(255, 139, 89, 0.49) 0%, rgba(66, 105, 150, 0.8) 100%), url("~@/assets/ocean.jpg");
}
.me {
  width: 125px;
}
.gradient-bg {
  background: #7DBEE3;
  background-image: url("data:image/svg+xml;charset=utf8,%3Csvg%20xmlns%3D%22http%3A//www.w3.org/2000/svg%22%20viewBox%3D%220%200%20512%20512%22%20width%3D%22512%22%20height%3D%22512%22%20preserveAspectRatio%3D%22none%22%3E%3Cfilter%20id%3D%22noise%22%3E%3CfeTurbulence%20type%3D%22fractalNoise%22%20baseFrequency%3D%220.875%22%20result%3D%22noise%22%20/%3E%3CfeColorMatrix%20type%3D%22matrix%22%20values%3D%220.2890625%200%200%200%200%200%200.125%200%200%200%200%200%200.125%200%200%200%200%200%200.52734375%200%22%20/%3E%3C/filter%3E%3Crect%20filter%3D%22url%28%23noise%29%22%20x%3D%220%22%20y%3D%220%22%20width%3D%22512%22%20height%3D%22512%22%20fill%3D%22transparent%22%20opacity%3D%221%22%20/%3E%3C/svg%3E"), linear-gradient(45deg, rgb(125, 190, 227) 0%, rgb(255, 160, 130) 100%);
  backdrop-filter: blur(2px);
  border-top-left-radius: 1rem;
  border-top-right-radius: 1rem;
}
.rounded {
  border-radius: 1rem !important;
}
.btn-50 .btn {
  display: flex;
  align-items: center;
  justify-content: space-between;
  font-weight: bold;
  font-size: 0.8rem;
  padding: 0.5rem 1.25rem;
  margin-bottom: 1.2rem;
  border-color: #0000002B;
  border-top-left-radius: 50px;
  border-bottom-left-radius: 50px;
  border-top-right-radius: 50px;
  border-bottom-right-radius: 50px;
}
.btn-50 .btn:hover {
  color: #FF5C5C;
  border-color: #FF5C5C;
}
</style>
