<template>
    <div class="container">
        <div class="gamecard">
            <div class="gamecard__img"><img src="../../../../src/assets/img/gamecard-1.png" /></div>
            <div class="gamecard__info">
                <div class="gamecard__name">
                    <span>Resident Evil 3 Remake</span>
                    <span>ОБНОВЛЕНО 20.04.2020</span>
                </div>
                <div class="gamecard__pref">
                    <li>
                        <ul>
                            Дата выхода: 3 апреля
                        </ul>
                        <ul>
                            Озвучка: Английская
                        </ul>
                        <ul>
                            Язык интерфейса: Русская, Английская, Multi12
                        </ul>
                        <ul>
                            Тип издания: Лицензия
                        </ul>
                        <ul>
                            Разработчик: CAPCOM CO., Ltd.
                        </ul>
                        <ul>
                            Платформа: PC
                        </ul>
                        <ul>
                            Таблетка: Отсутствует (Denuvo)
                        </ul>
                        <ul>
                            Жанр: Экшен, Стратегии, Ролевые (RPG), Симуляторы, Приключения, Инди
                        </ul>
                    </li>
                </div>
                <div class="gamecard__rate">
                    <div class="gamecard__button btns">Скачать прямо сейчас</div>
                    <div class="gamecard__stars">
                        <img src="../../../assets/img/star1.png" />
                        <img src="../../../assets/img/star1.png" />
                        <img src="../../../assets/img/star1.png" />
                        <img src="../../../assets/img/star1.png" />
                        <img src="../../../assets/img/star1.png" />
                    </div>
                </div>
            </div>
        </div>
        <div class="gallery">
            <img src="../../../assets/img/glimg1.png" />
            <img src="../../../assets/img/glimg2.png" />
            <img src="../../../assets/img/glimg3.png" />
        </div>
        <div class="gamecard__description">
            <p>
                Описание <br />

                Resident Evil 3 Remake (Резидент Эвил 3) – обновление легендарной части «Обителя Зла», в свое время
                совершившей революции в жанре зомби-апокалипсиса. В роли Джил Валентайн игрокам вновь предстоит пережить
                ужасные события, произошедшие в Раккун-сити. Разработчиком римейка третьей части является японская
                корпорация Capcom. Что увидят в переизданной части легендарной игры? Давайте посмотрим. <br />
                - Особенности <br />
                Враги. Зомби теперь обладают своеобразным интеллектом и могут удивить скоростью передвижения. Джил
                Валентайн. Героиня обросла множеством новых возможностей. Как и прежде, ей в одиночку предстоит сбежать
                из зараженного города. <br />
                - Графика <br />
                В игре в первую очередь подтянули графику. Все персонажи и текстуры выглядят изумительно. Во многих
                играх последних лет делается ставка на передачу эмоций персонажей. ResidentEvil 3 Remake не является
                исключением. Nemesis. Ужасный проект корпорации Umbrella приведен в действие, после начала
                распространения ужасного вируса. Джил и ее немногих помощникам придется непросто, ведь в финальной сцене
                вам предстоит сразиться со страшным монстром.
            </p>
        </div>
        <div class="gamecard__video">
            <img src="../../../assets/img/Video.png" />
        </div>
        <div class="gamecard__sys">
            <span>Системные требования:</span>
            <li>
                <ul>
                    ОС: Windows 7, 8.1, 10 (64-bit Required)
                </ul>
                <ul>
                    Процессор: Intel® Core™ i5-4460 or AMD FX™-6300 or better
                </ul>
                <ul>
                    Оперативная память: 8 GB ОЗУ
                </ul>
                <ul>
                    Видеокарта: NVIDIA® GeForce® GTX 760 or AMD Radeon™ R7 260x with 2GB Video RAM
                </ul>
                <ul>
                    DirectX: Версии 11
                </ul>
                <ul>
                    Место на диске: 45 GB
                </ul>
            </li>
        </div>
        <div class="gamecard__inst">
            <span>Установка:</span>
            <p>
                Установка (Обычная): <br />
                1. Скопировать содержимое релиза в любое место на вашем жестком диске. <br />
                2. Ждать таблетку <br />
                Установка (Для обладателей лицензии): <br />
                Перед установкой в клиент Steam, игра уже должна быть зарегистрирована на аккаунте, а сам клиент Steam -
                закрыт! <br />
                1. Скопировать папку с игрой RE3 в папку с вашим Steam-клиентом, путь (...\Steam\steamapps\common)
                <br />
                2. Скопировать содержимое папки Steam в папку с вашим клиентом. <br />
                3. Играть <br />
            </p>
        </div>
        <div class="gamecard__down">
            <div class="gamecard__dowm__item">
                <div><img src="../../../assets/img/torrent-ic.png" />resident-evil-3.torrent</div>
                <div>Вес: 23,13GB</div>
                <div>Скачали: 1120 раз</div>
            </div>
            <div class="gamecard__dowm__item">
                <div>Как качать через <span>torrent</span>?</div>
                <div class="gamecard__button btns btns__down">СКАЧАТЬ ТОРРЕНТ (30,01 КБ)</div>
            </div>
            <div class="gamecard__dowm__item">
                <div>Проверено (вирусов нет)</div>
                <div class="gamecard__button btns btns__err">ЖАЛОБА НА ФАЙЛ</div>
            </div>
        </div>
        <div class="gamecard__recp">
            <span>Рекомендуем скачать</span>
            <div class="gamecard__recom">
                <Card :key="item.id" v-for="item in 8"/>
            </div>
        </div>
        <div class="gamecard__comments">
            <div class="gamecard__com">Комментарии <span>(19)</span></div>
            <div class="gamecard__com-list">
                <div class="gamecard__comlog">
                    <img src="../../../assets/img/21.svg">
                    <div>- 15 +</div>
                    <span>19.04.2020</span>
                </div>
                <div class="gamecard__comTxt">
                    <span>Philip Morris</span> <br />
                    Resident Evil 2 is a survival horror game developed and published by Capcom. A remake of the 1998
                    game Resident Evil 2, it was released for Windows, PlayStation 4, and Xbox One on January 25
                    Resident Evil 2 is a survival horror game developed and published by Capcom. A remake of the 1998
                    game Resident Evil 2, it was released for Windows, PlayStation 4, and Xbox One on January 25Resident
                    Evil 2 is a survival horror game developed and published by Capcom. A remake of the 1998 game
                    Resident Evil 2, it was released for Windows, PlayStation 4, and Xbox One on January 25
                </div>
            </div>
        </div>
    </div>
</template>

<script>
import Card from "../../Elements/Card/Card";
export default {
    name: "GameInfo",
    components: {
        Card,
    },
};
</script>

<style lang="sass">
.container
    width: 1440px
    height: auto

.gamecard
    width: 960px
    height: auto
    display: flex
    justify-content: space-around
    padding-top: 60px

.gamecard__info
    width: 484px
    height: 544px

.gamecard__name
    span
        display: block

    span:first-child
        font-family: Roboto
        font-style: normal
        font-weight: 500
        font-size: 36px
        line-height: 150%

    span:nth-child(2n)
        font-family: Roboto
        font-style: normal
        font-weight: 500
        font-size: 12px
        line-height: 14px
        text-transform: uppercase
        color: #FF0404

.gamecard__pref
    margin-top: 31px
    li
        list-style: none
        font-family: Roboto
        font-style: normal
        font-weight: normal
    ul
        border-bottom: 1px solid #F9F9F9
        padding-bottom: 8px
        padding-top: 6px
    ul:last-child
        border: none

.gamecard__button
    width: 194px
    height: 42px
    font-family: Roboto
    font-style: normal
    font-weight: bold
    font-size: 12px
    line-height: 14px
    text-transform: uppercase
    padding-top: 14px

.gamecard__rate
    display: flex
    margin-top: 90px

.gallery
    width: 960px
    height: auto
    padding-top: 60px

.gamecard__description
    padding-top: 60px
    padding-bottom: 60px
    width: 960px

.gamecard__video
    width: 960px
    height: auto
    padding-bottom: 40px

.gamecard__sys
    width: 960px
    height: auto
    padding-bottom: 60px
    span
        font-family: Roboto
        font-style: normal
        font-weight: 500
        font-size: 28px
        line-height: 150%
        color: #000000

    li
        list-style: none
        padding-top: 18px

    ul
        padding-bottom: 6px

.gamecard__inst
    width: 960px
    height: auto
    padding-bottom: 60px

.gamecard__down
    width: 960px
    height: 180px
    background: #F5F7FA
    margin-bottom: 60px
    display: flex

.gamecard__dowm__item
    div
        margin-top: 12px
    div:first-child
        margin-bottom: 28px
        margin-top: 0px
        color: #54B825

.btns__down
    width: 344px
    height: 50px
    padding-top: 18px

.btns__err
    color: white
    background: #D05027
    border-color: #D05027

.btns__err:hover
    background-color: #D05027


.gamecard__recp
    width: 960px
    span:first-child
        font-family: Roboto
        font-style: normal
        font-weight: 500
        font-size: 28px
        line-height: 150%
        color: #000000
        padding-left: 23px

.gamecard__recom
    width: 960px
    height: auto
    display: flex
    justify-content: flex-start
    flex-wrap: wrap
    padding-bottom: 60px

.gamecard__com-list
    padding-top: 80px
    display: flex
    font-family: Roboto
    font-style: normal
    font-weight: normal
    font-size: 14px
    line-height: 150%
    color: #000000

.gamecard__comlog
    width: 80px
    height: 148px
    padding-right: 28px
    div
        width: 63px
        height: auto
        margin: auto
        text-align: center
        font-family: Roboto
        font-style: Medium
        font-size: 18px
        line-height: 27px
        line-height: 150%
        margin-top: 11px
    span
        display: block
        margin-top: 12px
        font-family: Roboto
        font-style: Regular
        font-size: 12px
        line-height: 18px
        line-height: 150%
        color: #B9B0B0
        text-align: center

.gamecard__com
    font-family: Roboto
    font-style: normal
    font-weight: 500
    font-size: 28px
    line-height: 150%
    color: #000000
    span
        font-family: Roboto
        font-style: normal
        font-weight: 500
        font-size: 28px
        line-height: 150%
        color: #B6B6B6

.gamecard__comments
    width: 960px
    height: auto
    padding-bottom: 60px

.gamecard__comTxt
    span
        display: block
        font-family: Roboto
        font-style: normal
        font-weight: 500
        font-size: 16px
        line-height: 150%
        color: #000000
</style>
