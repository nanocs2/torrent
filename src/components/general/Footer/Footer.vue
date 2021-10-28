<template>
    <div>
        <div class="container">
            <div class="ctn__footer">
                <div class="footer" v-html="footerTxt"></div>
            </div>
        </div>
    </div>
</template>

<script>
import DataCfg from "../../../constants/cfg.js";
export default {
    name: "Footer",

    data() {
        return {
            footerTxt: "123",
        };
    },
    mounted() {
        this.footerTxt = DataCfg.footerText;
        console.log(DataCfg);
    },
};
</script>

<style lang="sass">
.container
  width: 1440px
  height: auto  
.ctn__footer
  width: 100%
  background-color: black    

.footer
  width: 1070px
  height: auto
  padding-top: 25px
  padding-bottom: 25px
  color: white
</style>
