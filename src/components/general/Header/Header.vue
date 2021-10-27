<template>
<header>
    <div>
        <div class="container">
            <nav class="nav">
                <div class="nav__logo"><img class="nav__logo-img" src="../../../assets/img/logo.png" /></div>
                <div class="nav__title">
                    <span>TGS</span>
                    <p>Лучший бесплатный торрент-трекер</p>
                </div>
                <div class="nav__form">
                    <form><input type="text" placeholder="Например: “Mount & Blade 2 Bannerlord”" /></form>
                </div>
                <div class="nav__lics">Я правообладатель</div>
                <div class="nav__btns btns">ВХОД</div>
                <div class="nav__btns btns">РЕГИСТРАЦИЯ</div>
            </nav>
        </div>
    </div>
</header>
</template>

<script>
export default {
    name: "Header",
};
</script>

<style lang="sass">
*
  margin: 0px
  padding: 0px
  margin: auto
  font-family: 'Roboto', sans-serif

.container
  width: 1440px
  height: auto
  margin: auto

.nav
  width: 1070px
  height: 118px
  display: flex
  justify-content: space-between

.nav__logo
  width: 65px
  height: 65px

.nav__title
  width: 116px
  height: 53px
  align-items: center
  font-family: 'Roboto', sans-serif
  font-style: normal
  font-weight: normal
  font-size: 12px
  line-height: 14px
  color: #7E7E7E
  text-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25)

  span
    font-family: 'Roboto', sans-serif
    font-style: normal
    font-weight: 900
    font-size: 18px
    line-height: 21px
    color: #000000

.nav__form input
  width: 357px
  height: 38px
  background: #FFFFFF
  border: 1px solid #E6E6E6
  border-radius: 4px
  text-decoration: none
  text-align: left
  padding-left: 10px
  font-family: 'Roboto', sans-serif
  font-style: normal
  font-weight: normal
  font-size: 14px
  line-height: 16px
  color: #BDBCBC

.nav__lics
  width: 129px
  height: 20px
  font-family: 'Roboto', sans-serif
  font-style: normal
  font-weight: normal
  font-size: 14px
  line-height: 16px
  color: #54B825
  position: relative

  &:after
    position: absolute
    content: " "
    left: 0px
    bottom: 1px
    background-color: #54B825
    width: 124px
    height: 1px

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

.nav__btns:nth-child(2n)
  width: 129px

.btns:hover
  background-color: #54B825
  cursor: pointer
  transition: 0.5s
  color: white

</style>
