<template>
  <section class="main">
    <LeftSideBar class="left-side-bar" ></LeftSideBar>
    <Main class="main-bar" ></Main>
    <RightSideBar  class="right-side-bar"></RightSideBar>
  </section>
</template>

<script>
import LeftSideBar from "../components/LeftSideBar";
import RightSideBar from "../components/RightSideBar";
import Main from "../components/Main";
export default {
  data() {
    return{

    }
  },
  components: {
    LeftSideBar,
    RightSideBar,
    Main
  }
};
</script>
<style lang="sass">
@import "../assets/components/Dashboard"
</style>
