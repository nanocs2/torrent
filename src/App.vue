<template>
    <div id="app">
        <Header />
        <Slider />
        <!-- <Profile /> -->
        <!-- <MainPage /> -->
        <GameInfo />
        <Footer />
    </div>
</template>

<script>
// import MainPage from "./components/views/MainPage/MainPage";
import Header from "./components/general/Header/Header";
import Footer from "./components/general/Footer/Footer";
import Slider from "./components/general/Slider/Slider";
// import Profile from './components/views/Profile/Profile';
import GameInfo from "./components/views/GameInfo/GameInfo";
export default {
    name: "App",
    components: {
        // MainPage,
        Slider, 
        Header,
        Footer,
        // Profile,
        GameInfo,
    },
};
</script>

<style lang="sass">
@import 'https://fonts.googleapis.com/css2?family=Roboto:wght@100,500,900&display=swap'
div
  font-family: 'Roboto', sans-serif
</style>
