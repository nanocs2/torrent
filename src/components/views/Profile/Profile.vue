<template>
    <div class="container">
        <div class="users__hub">
            <div class="users__info">
                <span>Пользователь: Nolis <span>(offline)</span></span>
            </div>
            <div class="users__bar">
                <div class="users__bar-svg">
                    <img src="../../../assets/img/22.svg" />
                    <div class="users__bar-button btns">Написать</div>
                </div>
                <div class="users__bar-window">
                    <div class="users__bar-window-t">
                        <div class="users__bar__window__items">
                            <div class="users__bar__window__item">Имя:</div>
                            <div class="users__bar__window__item">Дата регистрации:</div>
                            <div class="users__bar__window__item">Логин:</div>
                            <div class="users__bar__window__item">Последнее посещение:</div>
                            <div class="users__bar__window__item">Группа:</div>
                        </div>
                        <div class="users__bar__window__items">
                            <div class="users__bar__window__item">Андрей</div>
                            <div class="users__bar__window__item">24.04.2020</div>
                            <div class="users__bar__window__item">Nolis</div>
                            <div class="users__bar__window__item">24.04.2020</div>
                            <div class="users__bar__window__item">Администратор</div>
                        </div>
                    </div>
                    <div class="users__bar-window__games">
                        <div class="users__bar-window__games-txt">Любимые игры:</div>
                        <div class="users__bar-window__games-txt">
                            Game of The Year, Game of The Year, Game of The Year Game of Th, Game of The Year, Game of
                            The Year.
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: "Profile",
};
</script>

<style lang="sass">

.users__hub
  width: 1070px
  height: auto
  margin-top: 80px

.users__info span
  width: 991px
  height: 44px
  padding-left: 36px
  font-family: 'Roboto', sans-serif
  font-style: normal
  font-weight: normal
  font-size: 29px
  line-height: 150%

  span
    padding-left: 0px
    color: #F12424

.users__bar
  width: 996px
  height: 398px
  background: #FFFFFF
  border: 1px solid #EBEBEB
  box-sizing: border-box
  border-radius: 2px
  margin-bottom: 137px
  display: flex
  justify-content: space-around

.users__bar-window
  width: 473px
  height: 266px

.users__bar-window-t
  margin-top: 0px
  display: flex

  div
    border-bottom: 1px solid #F9F9F9
    width: 235px
    padding: 8px 0px 8px 0px

    &:last-child
      border: none

.users__bar-button
  width: 137px
  height: 37px
  margin: auto
  margin-top: 18px

.users__bar-svg
  width: 143px
  height: 191px
  margin-left: 172px
  margin-top: 34px

.users__bar-window__games
    width: 394px
    height: 78px
    margin-left: 0px

    div
        padding-bottom: 6px
</style>
