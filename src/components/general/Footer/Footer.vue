<template>
    <footer>
        <div>
            <div class="container">
                <div class="footer" v-html="footerTxt"></div>
            </div>
        </div>
    </footer>
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
        console.log(DataCfg)
    }
};
</script>

<style lang="sass">
footer .container
  width: 1440px
  background-color: black

.footer
  width: 1070px
  height: auto
  padding-top: 25px
  padding-bottom: 25px
  color: white

</style>
