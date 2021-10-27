<template>
    <div>
        <div class="container">
            <div class="catalog">
                <div class="catalog__grid">
                    <Card />
                    <Card />
                    <Card />
                    <Card />
                    <Card />
                    <Card />
                    <Card />
                    <Card />
                    <Card />
                    <Card />
                    <Card />
                    <Card />
                </div>
                <div class="catalog__info">
                    <div :key="item.id" v-for="item in sidebarList" class="catalog__info-list">{{ item.name }}</div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
import DataCfg from "../../../constants/cfg.js";
import Card from "../../Elements/Card/Card";
export default {
    name: "MainPage",
    components: {
        Card,
    },
    data() {
        return {
            sidebarList: [],
            footerTxt: "",
        };
    },
    mounted() {
        this.sidebarList = DataCfg.sidebarMenu;
        this.footerTxt = DataCfg.footerText;
    },
};
</script>

<style lang="sass" scoped>
*
  margin: 0px
  padding: 0px
  margin: auto
  font-family: 'Roboto', sans-serif

.container
  width: 1440px
  height: auto
  margin: auto

.btns
  border: 1px solid #54B825
  box-sizing: border-box
  border-radius: 4px
  width: 77px
  height: 38px
  text-align: center
  font-family: 'Roboto', sans-serif
  font-style: normal
  font-weight: bold
  font-size: 12px
  line-height: 14px
  padding-top: 12px
  color: #54B825

.btns:hover
  background-color: #54B825
  cursor: pointer
  transition: 0.5s
  color: white

.catalog
  width: 1070px
  height: auto
  padding-top: 34px
  display: flex
  justify-content: space-between
  padding-bottom: 50px

.catalog__grid
  width: 820px
  height: auto
  display: flex
  justify-content: flex-start
  flex-wrap: wrap

.catalog__grid-item
  width: 193px
  height: 326px
  align-items: center
  text-align: center
  background: #FFFFFF
  border: 1px solid #EBEBEB
  box-sizing: border-box
  border-radius: 2px
  margin-top: 16px

  img
    padding: 16px

  span
    display: block
    width: 160px
    height: auto

.catalog__info
  width: 222px
  height: auto
  background: #FFFFFF
  border: 1px solid #EBEBEB
  box-sizing: border-box
  border-radius: 2px
  margin-top: 16px

.catalog__info-list
  position: relative
  display: block
  width: 160px
  height: auto
  text-align: center
  padding-top: 23px
  font-family: 'Roboto', sans-serif
  font-style: normal
  font-weight: 500
  font-size: 16px
  line-height: 100%

  &:after
    position: absolute
    content: " "
    width: 162px
    height: 1px
    bottom: -11px
    left: 0px
    background-color: #F9F9F9

  &:last-child
    padding-bottom: 27px

    &:after
      position: absolute
      content: " "
      width: 162px
      height: 1px
      bottom: 11px
      left: 0px

</style>
