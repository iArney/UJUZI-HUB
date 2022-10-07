<template>
  <div
    class="body-section row w-75 mx-auto align-items-center container-fluid position-relative"
  >
    <div class="container d-inline col-7 d-none d-sm-none d-md-flex">
      <img
        class="position-relative start-50 top-0 translate-middle-x mx-5"
        src="@/assets/ujuziHubOfficialLogo.webp"
        alt="ujuziHub"
      />
    </div>
    <div
      class="container d-inline col-9 align-self-center mt-1 w-sm-25 col-sm-9 col-lg-5 sm-text-center"
    >
      <span class="fw-light w-100"
        >A digital learning platform &#40;Masterclass&#41; aiming at delivering
        knowledge by using a short, simplified, and effective online courses
        from best instructors/practitioners through visuals, audios &#38; notes
        to teach different important vocational/handy skills to people across
        East and Central Africa using Swahili language.
      </span>
    </div>
    <div
      class="container-fluid mt-5 row mx-auto d-none d-sm-none d-md-flex align-items-center mx-auto text-center"
    >
      <div class="col">
        <global-links
          link_name="HORRICULTURE"
          data-bs-toggle="tooltip"
          data-bs-placement="top"
          title="Agriculture Related"
          class="mx-auto animate__animated animate__lightSpeedInLeft"
        />
      </div>
      <div class="col">
        <global-links
          link_name="GARDERNING"
          data-bs-toggle="tooltip"
          data-bs-placement="top"
          title="Pro Garden Experts"
          class="mx-auto animate__animated animate__lightSpeedInLeft"
        />
      </div>
      <div class="col">
        <global-links
          link_name="CAPENTRY"
          data-bs-toggle="tooltip"
          data-bs-placement="top"
          title="Selects from Forestry"
          class="mx-auto animate__animated animate__lightSpeedInLeft"
        />
      </div>
      <div class="col">
        <global-links
          link_name="SEWING/FASHION"
          data-bs-toggle="tooltip"
          data-bs-placement="top"
          title="From your Fashionists"
          class="mx-auto animate__animated animate__lightSpeedInLeft"
        />
      </div>
      <div class="col">
        <global-links
          link_name="ANIMAL HUSBANDRY"
          data-bs-toggle="tooltip"
          data-bs-placement="top"
          title="Animal keeping explained"
          class="mx-auto animate__animated animate__lightSpeedInLeft"
        />
      </div>
      <div class="col">
        <global-links
          link_name="CAR MAINTANANCE"
          data-bs-toggle="tooltip"
          data-bs-placement="top"
          title="Animal keeping explained"
          class="mx-auto animate__animated animate__lightSpeedInLeft"
        />
      </div>
      <div class="col">
        <global-links
          link_name="MUSIC&#38;VIDEO PRODUCTION"
          data-bs-toggle="tooltip"
          data-bs-placement="top"
          title="Animal keeping explained"
          class="mx-auto animate__animated animate__lightSpeedInLeft"
        />
      </div>
      <div class="col">
        <global-links
          link_name="COOKING"
          data-bs-toggle="tooltip"
          data-bs-placement="top"
          title="Animal keeping explained"
          class="mx-auto animate__animated animate__lightSpeedInLeft"
        />
      </div>
      <!-- skills cards -->
    </div>

    <div class="col">
      <skill-cards class="mx-auto" />
    </div>
    <div class="col">
      <skill-cards class="mx-auto" />
    </div>
    <div class="col">
      <skill-cards class="mx-auto" />
    </div>
    <!-- <div class="col">
          <skill-cards class="mx-auto w-75" />
        </div> -->

    <!-- skills card ends -->
    <!-- </div> -->
    <div class="col-12 text-center mt-1 mb-5 fs-2">
      <span class="align-center">
        <a style="color: #000" href="#">View all courses</a>
      </span>
    </div>
    <!-- enroll cards starts -->
    <div class="price-container mt-5 row align-items-center">
      <div class="col-12">
        <h3>Latest Courses</h3>
      </div>
      <div class="col">
        <enroll-cards class="p-c mx-auto shadow-lg" />
      </div>
      <div class="col">
        <enroll-cards class="p-c mx-auto shadow-lg" />
      </div>
      <div class="col">
        <enroll-cards class="p-c mx-auto shadow-lg" />
      </div>
      <div class="col">
        <enroll-cards class="p-c mx-auto shadow-lg" />
      </div>
    </div>
    <!-- enroll cards contd.. -->
    <div class="price-container mt-5 row align-items-center ml-5">
      <div class="col col-xs-5">
        <enroll-cards class="p-c mx-auto shadow-lg" />
      </div>
      <div class="col col-xs-5">
        <enroll-cards class="p-c mx-auto shadow-lg" />
      </div>
      <div class="col col-xs-5">
        <enroll-cards class="p-c mx-auto shadow-lg" />
      </div>
      <div class="col col-xs-5 d-none d-sm-none d-md-flex">
        <enroll-cards class="p-c mx-auto shadow-lg" />
      </div>
    </div>

    <div class="price-container mt-5 row align-items-center ml-5">
      <div class="col-12">
        <h3>Top Courses</h3>
      </div>
      <div class="col col-xs-5">
        <enroll-cards class="p-c mx-auto shadow-lg" />
      </div>
      <div class="col col-xs-5">
        <enroll-cards class="p-c mx-auto shadow-lg" />
      </div>
      <div class="col col-xs-5">
        <enroll-cards class="p-c mx-auto shadow-lg" />
      </div>
      <div class="col col-xs-5">
        <enroll-cards class="p-c mx-auto shadow-lg" />
      </div>
    </div>
    <!-- enroll cards ends -->
    <div class="price-container row mt-5 align-items-center">
      <div class="col-12 mt-5 text-center">
        <h3>Choose your plan</h3>
        <p>
          Upgrade to enjoy unlimited access to different plans. <br />
          Access video trainings from experienced professionals with detailed
          and stepwise instructions.
        </p>
      </div>
      <div class="col">
        <price-cards class="p-c mx-auto mt-5" />
      </div>
      <div class="col">
        <price-cards class="p-c mx-auto mt-5" />
      </div>
      <div class="col">
        <price-cards class="p-c mx-auto mt-5" />
      </div>
    </div>
  </div>
  <br />

  <!-- team -->
  <div class="row mt-5">
    <div class="price-container row mt-5 align-items-center">
      <team-cards />
      <div class="col"></div>
    </div>
  </div>
</template>

<script>
import GlobalLinks from "../GlobalComponents/GlobalLinks.vue";
import EnrollCards from "../PageContents/EnrollCards.vue";
import PriceCards from "../PageContents/PriceCards.vue";
import SkillCards from "../PageContents/SkillCards.vue";
import TeamCards from "../PageContents/TeamCards.vue";
export default {
  name: "BodySection",
  components: {
    GlobalLinks,
    SkillCards,
    EnrollCards,
    PriceCards,
    TeamCards,
  },
  data: function () {
    return {
      link_name: String,
    };
  },
};
</script>

<style scoped>
@media (min-width: 400px) and (max-width: 650px) {
  .price-container {
    position: relative;
  }
  .p-c {
    display: block;
    position: relative;
    left: -1rem;
    width: 1000px;
  }
}
@media (min-width: 300px) and (max-width: 398px) {
  .price-container {
    position: relative;
  }
  .p-c {
    display: block;
    position: relative;
    left: -2.6rem;
    width: 1000px;
  }
}
.body-section {
  background: url("@/assets/background_n.webp");
}
.animate__animated.animate__lightSpeedInLeft {
  --animate-duration: 3s;
}
/* .animate__animated.animate__lightSpeedInLeft {
  --animate-duration: 3s;
} */
</style>
