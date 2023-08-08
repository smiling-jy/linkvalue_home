<template>
    <div class="headerDiv">
        <h1>LINKVALUE</h1>
    </div>
    <div class="comp1text">
        <h3 data-aos="fade-down"
            data-aos-duration="2500">" 기업이 비즈니스에 집중 할 수 있도록 "</h3>
        <h1 data-aos="fade-up"
            data-aos-duration="2500">IoT 미들웨어 플랫폼 및<br/> 컨설팅 서비스를 제공합니다.</h1>
            <!-- <div class="whiteLine" 
                data-aos="fade-right"
                data-aos-duration="3000"></div> -->
    </div>
    <div class="comp1Top"></div>
    <div class="comp1"></div>
</template>

<script>
export default {
  name: 'MainSection', // 컴포넌트의 name속성
  data(){
    return{

    }
  },
  mounted() {
  },
  methods() {

  }
};
</script>

<style scoped>
@import '../css/mainStyle.css';

@media (max-width: 750px) {
    .headerDiv h1 {
        font-size: 1.5em;
        font-weight: 500;
        margin: 22px 0px 0px 20px;
        color: white;
        display: inline-block;
    }
    .comp1text h1 {
        font-size: 1.5em !important;
        line-height: 1.5em;
        text-align: center;
        color: white;
    }
    .comp1text h3{
        color: white;
        font-size: 0.8em !important;
        text-align: center;
        height: 80px;
        padding-top: 320px;
    }

}
.comp1text{
    width: 100%;
    position:absolute;
    z-index: 3;
    text-shadow: 0px 0px 10px rgb(10,10,10);
}
.comp1text h1 {
    font-size: 3.5em;
    line-height: 1.5em;
    text-align: center;
    color: white;
}
.comp1text h3{
    color: white;
    font-size: 1.5em;
    text-align: center;
    height: 80px;
    padding-top: 320px;
}
.whiteLine {
    height: 1px;
    width: 1200px;
    background-color: white;
    margin: 20px 0px 0px 0px;
}
.comp1Top {
    background-color:rgb(38,118,218,0.5);
    width: 100%;
    height: 100vh;
    position:absolute;
    z-index: 2;
}
.comp1 {
    background-image: url('../assets/comp1_backimg.jpg');
    background-size: cover;
    background-position: center;
    height: 100vh;
    width: 100%;
}
</style>