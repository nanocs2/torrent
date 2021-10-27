<template>
    <div class="container">
        <div class="slider">
            <div :key="item.id" v-for="item in sidebarInfo" class="slider-img"><img :src="item.image" /></div>
        </div>
    </div>
</template>

<script>
import DataCfg from "../../../constants/cfg.js";
export default {
    name: "Slider",
    data() {
        return {
            sidebarInfo: [],
        };
    },

    mounted() {
        this.sidebarInfo = DataCfg.sliderList;
    }
};
</script>

<style lang="sass">
.container:nth-child(2n)
  width: 1440px
  background: linear-gradient(0deg, #F5F7FA, #F5F7FA)

.slider
  width: 1070px
  height: 270px
  display: flex
  justify-content: space-between
  position: relative

.slider-img
  width: 113px
  height: 168px

  img
    object-fit: cover
    width: 113px
    height: 168px
    cursor: pointer

  &:after
    position: absolute
    content: url("../../../assets/img/arrowR.png")
    left: -34px
    bottom: 119px
    transform: rotate(-180deg)
    cursor: pointer

  &:before
    position: absolute
    content: url("../../../assets/img/arrowR.png")
    right: -34px
    bottom: 119px
    cursor: pointer
</style>
