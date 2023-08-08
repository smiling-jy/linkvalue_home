<template>
  <div>
    <a name="main"><MainSection name="main"/></a>
    <a name="history"><HistorySection/></a>
    <a name="cooperation"><CooperationSection name="cooperation"/></a>
    <a name="iot"><IotSection name="iot"/></a>
    <a name="foot"><FooterSection name="foot"/></a>
    
    <div data-aos="fade-right"
        data-aos-duration="2000"  class="nav">
      <ul>
        <li><a href="#main"><span class="material-symbols-outlined">radio_button_unchecked</span></a></li>
        <li><a href="#history"><span class="material-symbols-outlined">radio_button_unchecked</span></a></li>
        <li><a href="#cooperation"><span class="material-symbols-outlined">radio_button_unchecked</span></a></li>
        <li><a href="#iot"><span class="material-symbols-outlined">radio_button_unchecked</span></a></li>
        <li><a href="#foot"><span class="material-symbols-outlined">radio_button_unchecked</span></a></li>
      </ul>
    </div>
  </div>
</template>

<script>
  import MainSection from './components/MainSection.vue';
  import HistorySection from './components/HistorySection.vue';
  import CooperationSection from './components/CooperationSection.vue';
  import FooterSection from './components/FooterSection.vue';
  import IotSection from './components/IotSection.vue';
    
  export default {
    name: 'App',
    components: {
      MainSection,
      HistorySection,
      CooperationSection,
      FooterSection,
      IotSection,
    },
    data() {
      return {
        navResult: true,
      };
    },
  };
</script>

<style lang="scss">
@import './css/mainStyle.css';
  /* 여백제거 + 드래그방지 */
  // body{ padding:0; margin:0; -ms-user-select: none; -moz-user-select: none; -khtml-user-select: none; -webkit-user-select: none; user-select: none; }

@media (max-width: 750px) {
  .nav {
    width: 180px !important;
    height: 30px !important;
    border-radius: 40px;
    position: fixed;
    top: 17px !important;
    right: 20px;
    z-index: 10;
    background-color: rgba(115, 139, 228, 0.709);
    text-align: center;
  }
  .nav li {
    margin: 3px 6px 0px 5px !important;
    display: inline-block;
    flex: left;
  }
}

.nav {
  width:65px;
  height: 215px;
  border-radius: 40px;
  position: fixed;
  top: 40%;
  right: 20px;
  z-index: 10;
  background-color: rgb(100,100,100,0.2);
  text-align: center;
}
.nav li {
  margin-top: 20%;
}
.nav a {
  // color: rgb(45,68,130);
  color: rgb(255,255,255);
}
.material-symbols-outlined {
  font-variation-settings:
  'FILL' 1,
  'wght' 200,
  'GRAD' 0,
  'opsz' 20
}
.material-symbols-outlined-fill {
  font-variation-settings:
  'FILL' 1,
  'wght' 100,
  'GRAD' 0,
  'opsz' 20
}
</style>
