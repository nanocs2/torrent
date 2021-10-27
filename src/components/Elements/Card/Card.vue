<template>
		<div class="catalog__grid-item">
            <img src="../../../assets/img/img1.png" /><span>The Elder Scrolls 5 Skyrim Special</span>
        </div>
</template>

<script>
export default {
    name: "Card",
};
</script>

<style lang="sass">
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
</style>
