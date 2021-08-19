<template>
  <div class="ex-va__container">
    <div class="ex-va__wrapper">
      <div
        id="ex-va__action"
        class="active ex-va__action"
        :style="{
          'background-image': 'url(' + require('@/assets/map@2x.jpg') + ')',
        }"
        :class="[
          { 'position-1': position1 },
          { 'position-2': position2 },
          { 'position-3': position3 },
          { 'position-4': position4 },
          { 'position-5': position5 },
          { 'position-6': position6 },
          { 'position-7': position7 },
          { 'position-8': position8 },
          { 'position-9': position9 },
          { 'position-10': position10 },
        ]"
      >
        <App-pin-start-1
          class="pin1"
          @removeActivePin="removeActivePin"
          :activePin="active"
        ></App-pin-start-1>
        <App-pin-start-2
          class="pin2"
          @removeActivePin="removeActivePin"
          :activePin="active"
        ></App-pin-start-2>
        <App-pin-start-3
          class="pin3"
          @removeActivePin="removeActivePin"
          :activePin="active"
        ></App-pin-start-3>
        <App-pin-start-4
          class="pin4"
          @removeActivePin="removeActivePin"
          :activePin="active"
        ></App-pin-start-4>
        <App-pin-start-5
          class="pin5"
          @removeActivePin="removeActivePin"
          :activePin="active"
        ></App-pin-start-5>
        <App-pin-start-6
          class="pin6"
          @removeActivePin="removeActivePin"
          :activePin="active"
        ></App-pin-start-6>
        <App-pin-start-7
          class="pin7"
          @removeActivePin="removeActivePin"
          :activePin="active"
        ></App-pin-start-7>
        <App-pin-start-8
          class="pin8"
          @removeActivePin="removeActivePin"
          :activePin="active"
        ></App-pin-start-8>
        <App-pin-start-9
          class="pin9"
          @removeActivePin="removeActivePin"
          :activePin="active"
        ></App-pin-start-9>
        <App-pin-start-10
          class="pin10"
          @removeActivePin="removeActivePin"
          :activePin="active"
        ></App-pin-start-10>
      </div>
    </div>
    <nav class="map-nav swiper-container">
      <ul class="map-nav-list swiper-wrapper">
        <li class="map-item swiper-slide">
          <button @click="changePosition(1)" class="map-btn map-btn--start">
            <img class="map-btn-img" src="@/assets/map-btn-start.png" />
            <p class="map-btn-txt">Старт</p>
          </button>
        </li>
        <li class="map-item swiper-slide">
          <button @click="changePosition(2)" class="map-btn map-btn--hn-grow">
            <img class="map-btn-img" src="@/assets/map-btn-hn-grow.png" />
            <p class="map-btn-txt">HN Grow</p>
          </button>
        </li>
        <li class="map-item swiper-slide">
          <button @click="changePosition(3)" class="map-btn map-btn--present-1">
            <img class="map-btn-img" src="@/assets/map-btn-present-1.png" />
            <p class="map-btn-txt">Подарок</p>
          </button>
        </li>
        <li class="map-item swiper-slide">
          <button @click="changePosition(4)" class="map-btn map-btn--tree">
            <img class="map-btn-img" src="@/assets/map-btn-tree.png" />
            <p class="map-btn-txt">Дерево<br />«Экопривычек»</p>
          </button>
        </li>
        <li class="map-item swiper-slide">
          <button @click="changePosition(5)" class="map-btn map-btn--present-2">
            <img class="map-btn-img" src="@/assets/map-btn-present-2.png" />
            <p class="map-btn-txt">Подарок</p>
          </button>
        </li>
        <li class="map-item swiper-slide">
          <button @click="changePosition(6)" class="map-btn map-btn--marketing">
            <img class="map-btn-img" src="@/assets/map-btn-marketing.png" />
            <p class="map-btn-txt">Отдел<br />маркетинга</p>
          </button>
        </li>
        <li class="map-item swiper-slide">
          <button @click="changePosition(7)" class="map-btn map-btn--present-3">
            <img class="map-btn-img" src="@/assets/map-btn-present.png" />
            <p class="map-btn-txt">Подарок</p>
          </button>
        </li>
        <li class="map-item swiper-slide">
          <button @click="changePosition(8)" class="map-btn map-btn--it">
            <img class="map-btn-img" src="@/assets/map-btn-it.png" />
            <p class="map-btn-txt">Отдел<br />информационной<br />поддержки</p>
          </button>
        </li>
        <li class="map-item swiper-slide">
          <button @click="changePosition(9)" class="map-btn map-btn--ethics">
            <img class="map-btn-img" src="@/assets/map-btn-etick.png" />
            <p class="map-btn-txt">Отдел этики</p>
          </button>
        </li>
        <li class="map-item swiper-slide">
          <button @click="changePosition(10)" class="map-btn map-btn--final">
            <img class="map-btn-img" src="@/assets/map-btn-final.png" />
            <p class="map-btn-txt">Подарок</p>
          </button>
        </li>
      </ul>
    </nav>
  </div>
</template>
<script>
import AppPinStart1 from "@/components/map1/PinStart1.vue";
import AppPinStart2 from "@/components/map1/PinStart2.vue";
import AppPinStart3 from "@/components/map1/PinStart3.vue";
import AppPinStart4 from "@/components/map1/PinStart4.vue";
import AppPinStart5 from "@/components/map1/PinStart5.vue";
import AppPinStart6 from "@/components/map1/PinStart6.vue";
import AppPinStart7 from "@/components/map1/PinStart7.vue";
import AppPinStart8 from "@/components/map1/PinStart8.vue";
import AppPinStart9 from "@/components/map1/PinStart9.vue";
import AppPinStart10 from "@/components/map1/PinStart10.vue";
import Swiper from "swiper/swiper-bundle.min.js";
import "swiper/swiper.min.css";

export default {
  name: "AppMain",
  components: {
    AppPinStart1,
    AppPinStart2,
    AppPinStart3,
    AppPinStart4,
    AppPinStart5,
    AppPinStart6,
    AppPinStart7,
    AppPinStart8,
    AppPinStart9,
    AppPinStart10,
  },
  data() {
    return {
      active: null,
      position1: false,
      position2: false,
      position3: false,
      position4: false,
      position5: false,
      position6: false,
      position7: false,
      position8: false,
      position9: false,
      position10: false,
    };
  },
  methods: {
    changeShow() {
      this.show = !this.show;
    },
    changePosition(step) {
      this.position1 = false;
      this.position2 = false;
      this.position3 = false;
      this.position4 = false;
      this.position5 = false;
      this.position6 = false;
      this.position7 = false;
      this.position8 = false;
      this.position9 = false;
      this.position10 = false;
      if (step == 1) {
        this.active = "pin1";
        this.position1 = true;
      }
      if (step == 2) {
        (this.active = "pin2"), (this.position2 = true);
      }
      if (step == 3) {
        this.active = "pin3";
        this.position3 = true;
      }
      if (step == 5) {
        this.active = "pin4";
        this.position5 = true;
      }
      if (step == 4) {
        this.active = "pin5";
        this.position5 = true;
      }
      if (step == 6) {
        this.active = "pin6";
        this.position6 = true;
      }
      if (step == 7) {
        this.active = "pin7";
        this.position7 = true;
      }
      if (step == 8) {
        this.active = "pin8";
        this.position8 = true;
      }
      if (step == 9) {
        this.active = "pin9";
        this.position9 = true;
      }
      if (step == 10) {
        this.active = "pin10";
        this.position10 = true;
      }
    },
    removeActivePin(pin) {
      if (this.active === pin) {
        this.active = null;
        return false;
      }
      this.active = pin;
    },
  },
  mounted() {
    if (window.screen.width <= 576) {
      this.changePosition(1);

      new Swiper(this.$el.querySelector(".map-nav"), {
        slideToClickedSlide: true,
        slidesPerView: 3,
        speed: 900,
        slideActiveClass: "swiper-slide-active",
      });
    }
  },
};
</script>
<style>
body {
  margin: 0;
}
.pin1 {
  bottom: -33px;
  left: -67px;
}

.pin2 {
  bottom: 85px;
  left: 224px;
}

.pin3 {
  bottom: 91px;
  left: 376px;
}

.pin4 {
  bottom: 163px;
  left: 552px;
}

.pin5 {
  bottom: 85px;
  left: 641px;
}

.pin6 {
  bottom: 259px;
  left: 354px;
}

.pin7 {
  bottom: 375px;
  left: 220px;
}

.pin8 {
  bottom: 415px;
  left: 271px;
}

.pin9 {
  bottom: 310px;
  left: 502px;
}

.pin10 {
  bottom: 510px;
  left: 502px;
}

.ex-va__container {
  background-color: #000;
  display: flex;
  flex-direction: column;
  align-items: center;
}

@media screen and (max-width: 576px) {
  .ex-va__container {
    /* overflow: hidden; */
  }
}

.ex-va__wrapper {
  height: 997px;
  width: 935px;
  overflow: hidden;
  position: relative;
  background: linear-gradient(208.35deg, #25054d -69.14%, #45108a 68.82%);
}

@media screen and (max-width: 768px) {
  .ex-va__wrapper {
    margin-right: -110px;
  }
}

@media screen and (max-width: 576px) {
  .ex-va__wrapper {
    height: 484px;
    width: 100vw;
    overflow: hidden;
    position: relative;
    margin-right: 0;
  }
}

.map-nav {
  display: none;
}

.map-nav-list {
  margin: 0;
  padding: 0;
}

@media screen and (max-width: 576px) {
  .map-nav {
    display: block;
    width: 100vw;
    height: 84px;
  }
}

.map-btn {
  background: transparent;
  color: white;
  font-weight: 700;
  font-size: 20px;
  border: none;
  height: 84px;
  width: 100%;
  box-sizing: border-box;
  padding-top: 4px;
  padding-bottom: 4px;

  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  position: relative;
}

.map-btn:after {
  content: "";
  display: block;
  width: 16px;
  height: 2px;
  background-color: rgba(66, 85, 108, 1);
  position: absolute;
  top: 50%;
  right: 0;
  transform: translate(50%, -50%);
}

.map-btn--final:after {
  display: none;
}

.map-btn-txt {
  padding: 0;
  font-size: 12px;
  font-style: normal;
  font-weight: 700;
  line-height: 15px;
  text-align: center;
  margin-top: 3px;
  margin-bottom: 3px;
}

.ex-va__action {
  background-repeat: no-repeat;
  background-size: 1580px 1000px;
  background-position: -320px 0px;
  height: 997px;
  width: 935px;
  margin: 0;
  overflow: hidden;
  position: absolute;
  top: 0;
  left: 0;
  transition: all ease-in-out 0.3s;
}

@media screen and (max-width: 576px) {
  .ex-va__action {
    transform: scale(o);
  }
}

.ex-va__road {
  position: absolute;
  top: 0;
  left: 0;
}

@media screen and (max-width: 576px) {
  .position-1 {
    top: -432px;
    left: -7px;
  }

  .position-2 {
    top: -386px;
    left: -174px;
  }

  .position-3 {
    top: -397px;
    left: -318px;
  }

  .position-4 {
    top: -376px;
    left: -570px;
  }

  .position-5 {
    top: -447px;
    left: -515px;
  }

  .position-6 {
    top: -269px;
    left: -318px;
  }

  .position-6 {
    top: -286px;
    left: -309px;
  }

  .position-7 {
    top: -168px;
    left: -138px;
  }

  .position-8 {
    top: -92px;
    left: -249px;
  }

  .position-9 {
    top: -222px;
    left: -470px;
  }

  .position-10 {
    top: -19px;
    left: -476px;
  }
}

@media screen and (max-width: 360px) {
  .position-1 {
    top: -432px;
    left: -44px;
  }

  .position-2 {
    top: -386px;
    left: -245px;
  }

  .position-3 {
    top: -397px;
    left: -385px;
  }

  .position-4 {
    top: -376px;
    left: -570px;
  }

  .position-5 {
    top: -447px;
    left: -515px;
  }

  .position-6 {
    top: -286px;
    left: -309px;
  }

  .position-7 {
    top: -168px;
    left: -203px;
  }

  .position-8 {
    top: -92px;
    left: -320px;
  }

  .position-9 {
    top: -222px;
    left: -540px;
  }

  .position-10 {
    top: -19px;
    left: -546px;
  }
}
.pin-start {
  position: absolute;
}
svg {
  height: intrinsic;
}

.animations {
  transform-origin: center;
  transform: rotate3d(1, 0, 0, 56deg);
  opacity: 0;
  transition: 1s ease-in-out;
}
.active-pin .animations {
  opacity: 1;
  transform: rotate3d(1, 0, 0, 56deg);
}

.additionals {
  opacity: 0.4;
  transition: 0.2s ease-in-out;
}
.pin-rect {
  cursor: pointer;
}
.additionals.hovered,
.active-pin .additionals {
  opacity: 1;
}

.levitation {
  transition: all 5s ease-in-out;
  animation-duration: 5s;
  animation-name: float;
  animation-iteration-count: infinite;
  animation-play-state: paused;
}
.levitation1 {
  animation-name: float1;
}
.levitation2 {
  animation-name: float2;
}

.active-pin .levitation1,
.active-pin .levitation2,
.active-pin .levitation {
  animation-play-state: running;
}

.levitation2:nth-child(2) {
  animation-timing-function: cubic-bezier(0.05, 0, 0.45, 1);
}
.levitation2:nth-child(3) {
  animation-timing-function: cubic-bezier(0.1, 0, 0.5, 1);
}
.levitation2:nth-child(4) {
  animation-timing-function: cubic-bezier(0.15, 0, 0.55, 1);
}
.levitation2:nth-child(5) {
  animation-timing-function: cubic-bezier(0.2, 0, 0.6, 1);
}
.levitation2:nth-child(6) {
  animation-timing-function: cubic-bezier(0.25, 0, 0.65, 1);
}
.levitation2:nth-child(7) {
  animation-timing-function: cubic-bezier(0.3, 0, 0.7, 1);
}
.levitation2:nth-child(8) {
  animation-timing-function: cubic-bezier(0.35, 0, 0.75, 1);
}
.levitation2:nth-child(9) {
  animation-timing-function: cubic-bezier(0.4, 0, 0.8, 1);
}
.shine {
  transform-origin: 50% 57%;
  animation-duration: 6s;
  animation-iteration-count: infinite;
  animation-timing-function: linear;
  animation-name: shine;
  stroke: #44ffff;
  opacity: 0.5;
}

@keyframes shine {
  0% {
    stroke-width: 0px;
    opacity: 0.6;
  }
  50% {
    stroke-width: 60px;
    filter: blur(5px);
    opacity: 0.35;
  }
  100% {
    opacity: 0;
    stroke-width: 60px;
    filter: blur(5px);
  }
}

@keyframes shine-big {
  0% {
    stroke-width: 0px;
    opacity: 0.6;
  }
  50% {
    stroke-width: 120px;
    filter: blur(5px);
    opacity: 0.35;
  }
  100% {
    opacity: 0;
    stroke-width: 120px;
    filter: blur(5px);
  }
}
@keyframes float {
  0% {
    transform: translatey(0px);
  }
  50% {
    transform: translatey(-20px);
  }
  100% {
    transform: translatey(0px);
  }
}

@keyframes float1 {
  0% {
    transform: translatey(0px);
  }
  30% {
    transform: translatey(-20px);
  }
  70% {
    transform: translatey(-20px);
  }
  100% {
    transform: translatey(0px);
  }
}

@keyframes float2 {
  0% {
    transform: translatey(0px);
  }
  40% {
    transform: translatey(-20px);
  }
  60% {
    transform: translatey(-20px);
  }
  100% {
    transform: translatey(0px);
  }
}
</style>
