<template>
    <div class="container">
        <div class="users__hub">
            <div class="users__info">
                <span>Пользователь: Nolis <span>(offline)</span></span>
            </div>
            <div class="users__bar">
                <div class="users__bar-svg">
                    <!-- TODO: ВЕКТОР В ОТДЕЛЬНЫЙ ФАЙЛ -->
                    <svg width="142" height="136" viewBox="0 0 142 136" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <path
                            d="M71 0C31.8513 0 0 30.5054 0 68C0 105.495 31.8513 136 71 136C110.149 136 142 105.495 142 68C142 30.5054 110.149 0 71 0Z"
                            fill="#303C42"
                        />
                        <path
                            d="M70.9999 5.66675C106.887 5.66675 136.083 33.6294 136.083 68.0002C136.083 81.682 131.402 94.3071 123.569 104.598C122.885 104.172 122.209 103.783 121.523 103.444C109.666 97.6147 91.2749 90.6667 70.9999 90.6667C50.725 90.6667 32.3335 97.6147 20.4743 103.447C19.7901 103.785 19.1147 104.172 18.4308 104.598C10.5978 94.3066 5.9165 81.682 5.9165 68.0002C5.9165 33.6294 35.1128 5.66675 70.9999 5.66675Z"
                            fill="#E6E6E6"
                        />
                        <path
                            d="M71 130.333C51.5413 130.333 34.0977 122.07 22.1611 109.064C22.5014 108.867 22.8445 108.652 23.1812 108.486C34.4569 102.941 51.9065 96.3335 71 96.3335C90.0934 96.3335 107.543 102.941 118.816 108.483C119.154 108.651 119.498 108.865 119.839 109.064C107.902 122.07 90.4587 130.333 71 130.333Z"
                            fill="#54B825"
                        />
                        <path
                            d="M71 85C90.6061 85 106.5 69.7777 106.5 51C106.5 32.2223 90.6061 17 71 17C51.3939 17 35.5 32.2223 35.5 51C35.5 69.7777 51.3939 85 71 85Z"
                            fill="#303C42"
                        />
                        <path
                            d="M97.8276 124.735C106.277 121.037 113.774 115.672 119.839 109.064C119.498 108.865 119.154 108.651 118.816 108.483C107.543 102.941 90.0933 96.3335 71.0001 96.3335C70.086 96.3335 69.1971 96.4169 68.291 96.4461L97.8276 124.735Z"
                            fill="url(#paint0_linear)"
                        />
                        <path
                            d="M70.9999 79.3333C87.3384 79.3333 100.583 66.648 100.583 50.9999C100.583 35.3518 87.3384 22.6665 70.9999 22.6665C54.6615 22.6665 41.4165 35.3518 41.4165 50.9999C41.4165 66.648 54.6615 79.3333 70.9999 79.3333Z"
                            fill="#54B825"
                        />
                        <path
                            opacity="0.1"
                            d="M86.8598 27.1636C88.018 30.1944 88.7502 33.423 88.7502 36.8334C88.7502 52.4561 75.4793 65.1668 59.1668 65.1668C53.3212 65.1668 47.9008 63.483 43.3071 60.6698C47.4551 71.5235 58.2482 79.3334 70.9999 79.3334C87.3122 79.3334 100.583 66.6227 100.583 51C100.584 40.9753 95.085 32.2014 86.8598 27.1636Z"
                            fill="black"
                        />
                        <path
                            d="M71 0C31.8513 0 0 30.5054 0 68C0 105.495 31.8513 136 71 136C110.149 136 142 105.495 142 68C142 30.5054 110.149 0 71 0Z"
                            fill="url(#paint1_linear)"
                        />
                        <defs>
                            <linearGradient
                                id="paint0_linear"
                                x1="77.887"
                                y1="87.2632"
                                x2="108.939"
                                y2="119.692"
                                gradientUnits="userSpaceOnUse"
                            >
                                <stop stop-color="#54B825" stop-opacity="0.1" />
                                <stop offset="1" stop-opacity="0" />
                            </linearGradient>
                            <linearGradient
                                id="paint1_linear"
                                x1="6.65506"
                                y1="39.2722"
                                x2="133.306"
                                y2="100.928"
                                gradientUnits="userSpaceOnUse"
                            >
                                <stop stop-color="white" stop-opacity="0.2" />
                                <stop offset="1" stop-color="white" stop-opacity="0" />
                            </linearGradient>
                        </defs>
                    </svg>
                    <div class="users__bar-button btns">Написать</div>
                </div>
                <div class="users__bar-window">
                    <div class="users__bar-window-t">
                        <!-- TODO: ПУСТЫЕ КЛАССЫ? -->
                        <div class="">
                            <div class="">Имя:</div>
                            <div class="">Дата регистрации:</div>
                            <div class="">Логин:</div>
                            <div class="">Последнее посещение:</div>
                            <div class="">Группа:</div>
                        </div>
                        <div class="">
                            <div class="">Андрей</div>
                            <div class="">24.04.2020</div>
                            <div class="">Nolis</div>
                            <div class="">24.04.2020</div>
                            <div class="">Администратор</div>
                        </div>
                    </div>
                    <div class="users__bar-window__games">
                        <div class="">Любимые игры:</div>
                        <div class="">
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
