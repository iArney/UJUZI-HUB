<template>
  <div class="bg w-100 h-100 position-relative">
    <div class="row text-center">
      <div class="col-12 mt-5 mx-auto">
        <span class="fw-bold fs-3">
          A digital learning platform &#40;Masterclass&#41; aiming at <br />
          delivering knowledge by using a short, simplified, <br />
          and effective online courses
        </span>
      </div>
      <div class="comp col-12 mt-5 w-25 mx-auto">
        <reuse-button
          class="btn-comp mx-auto"
          btn_name="Get Started"
          style="background-color: #f18626; color: white"
        />
      </div>
      <div class="img-skill col-12 animate__animated animate__bounceIn">
        <img
          class="position-absolute top-50 start-50 translate-middle-x mt-5"
          src="@/assets/online_skills.webp"
          alt="online_skills"
          width="900"
          height="450"
        />
      </div>
    </div>
  </div>
</template>

<script>
import ReuseButton from "../GlobalComponents/ReuseButton.vue";
export default {
  name: "HomeVHeight",
  components: {
    ReuseButton,
  },
  data: () => ({
    btn_name: String,
  }),
};
</script>

<style scoped>
.bg {
  height: 100vh !important;
  background: url("@/assets/background.webp");
}
.btn-comp {
  z-index: 1000000;
}
@media (min-width: 400px) and (max-width: 650px) {
  .comp {
    position: relative;
  }
  .btn-comp {
    position: absolute;
    right: -4rem;
  }
}
@media (min-width: 300px) and (max-width: 398px) {
  .comp {
    position: relative;
  }
  .btn-comp {
    z-index: 1000000;
    position: absolute;
    right: -3.7rem;
  }
}
@media (min-width: 700px) and (max-width: 900px) {
  .img-skill {
    position: absolute;
    top: 22rem;
  }
  .img-skill img {
    height: 500px;
    width: 1200px;
  }
}
</style>
