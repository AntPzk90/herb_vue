<template>
  <transition name="fade">
    <div class="pin-popup">
      <h3 class="pin-popup-title">{{ title }}</h3>
      <p class="pin-popup-dscr">{{ dscr }}</p>
      <a class="pin-popup-link"> Начать </a>
    </div>
  </transition>
</template>

<script>
export default {
  name: "AppPinPopup",
  props: {
    title: {
      type: String,
      required: true,
    },
    dscr: {
      type: String,
      required: false,
    },
  },
};
</script>

<style>
.pin-popup {
  box-sizing: border-box;
  width: 100%;
  width: 218px;
  padding: 16px;
  background: linear-gradient(
    133.9deg,
    #8934cc 0%,
    #5d66e0 65.19%,
    #79b2f5 100%
  );
  border-radius: 16px;
  color: #ffffff;
  text-align: center;
  z-index: 10;
  position: absolute;
  top: 0;
  left: 50%;
  transform: translate(-50%, -100%);
}

@media screen and (max-width: 768px) {
  .pin-popup {
    transform: translate(-24%, -100%);
  }
}

.pin-popup-title {
  font-size: 18px;
  line-height: 22px;
  color: #ffffff;
  margin-top: 0;
  margin-bottom: 4px;
}

.pin-popup-dscr {
  font-size: 14px;
  line-height: 20px;
  color: #ffffff;
  margin-top: 0;
  margin-bottom: 16px;
}

.pin-popup-link {
  font: inherit;
  font-size: 16px;
  line-height: 24px;
  text-align: center;
  display: inline-block;
  padding: 12px 24px;
  border-radius: 5px;
  background: #629727;
  color: #ffffff;
  cursor: pointer;
}

fade-enter-active,
.fade-leave-active {
  transition: opacity 0.5s;
}
.fade-enter, .fade-leave-to /* .fade-leave-active до версии 2.1.8 */ {
  opacity: 0;
}
</style>