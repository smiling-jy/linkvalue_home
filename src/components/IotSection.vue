<template>
    <div class="outDiv">
        <!-- IOT PASS PLATFORM -->
        <div class="middleContents">
            <h1 class="middleConTitle"> IOT PASS PLATFORM IS...</h1>
            <h1>" BUSINESS LOGIC "</h1>
            <div class="middleImgs">
                <img data-aos="zoom-in"
                    data-aos-duration="2500" src="../assets/iot/iotImgTitle.png"/>
                <ul>
                    <li><img src="../assets/iot/iotImg1.png"/></li>
                    <li><img src="../assets/iot/iotImg2.png"/></li>
                    <li><img src="../assets/iot/iotImg3.png"/></li>
                </ul>
            </div>
        </div>
        <!-- IOT INTEGRATION MODULE -->
        <div data-aos="fade-down" data-aos-duration="2000" class="comp4After">
            <!-- <div class="comp4Triangle"></div> -->
        </div>
        <div class="comp4">
            <div>
                <h2 data-aos="fade-up" data-aos-duration="3000">IOT INTEGRATION MODULE</h2>
                <img data-aos="fade-up" data-aos-duration="3000" src="../assets/iot/iotImg4.png"/>
            </div>
        </div>
        <!-- SMART FACTORY SECTION -->
        <div class="comp5">
            <div data-aos="fade-up" data-aos-duration="1500"  class="comp5LeftDiv">
                <img src="../assets/iot/smartFactory.png"/>
            </div>
            <div data-aos="fade-up" data-aos-duration="1500"  class="comp5RightDiv">
                <div class="comp5RightText">
                    <h1>산업용 프로토콜 연동 부터<br/> AI 기술까지 Big Data<br/>파이프라인 구축</h1>
                    기획,설계, 생산, 유통, 판매에 이르는 제조과정에서<br/>이러한 정보통신 기술을 융합 및 적용해 
                    <span>생산성, 품질을 향상</span>시키고 <span>고객 맞춤형 제품</span>을 생성합니다
                    <br/><br/>
                    이를 구축하기 위해 가상화, 유연화, 간소화, 동기화의<br/>네가지 조건`을 충족시킵니다.
                </div>
            </div>
        </div>
        <!-- camping IoT Section -->
        <div class="comp6">
            <div class="comp6LeftDiv">
                <div class="comp6LeftImgs">
                    <img data-aos="zoom-out" data-aos-duration="2000" class="first6Img" src="../assets/iot/campingIOT1.png"/>
                    <img data-aos="zoom-in" data-aos-duration="2000" class="second6Img" src="../assets/iot/campingIOT2.png"/>
                </div>
            </div>
            <div class="comp6RightDiv">
                <div class="comp6RightText">
                    <h1 data-aos="fade-up" data-aos-duration="1000" >다양한 환경에 맞는<br/>디바이스와 플랫폼들을 연결합니다</h1>
                    <ul>
                        <li data-aos="fade-up" data-aos-duration="1000" class="comp6OutLi1">
                            <h2 class="comp6TextTitle1">Safety & Security</h2>
                            <ul class="comp6InnerUl">
                                <li>비대면 출입 인증</li>
                                <li>일산화탄소 감지</li>
                                <li>카라반 어닝 자동 제어</li>
                            </ul>
                        </li>
                        <li data-aos="fade-up" data-aos-duration="1500" class="comp6OutLi2">
                            <h2 class="comp6TextTitle2">Relax & Entertainment</h2>
                            <ul class="comp6InnerUl">
                                <li>AI Speaker</li>
                                <li>Lightning Therapy</li>
                            </ul>
                        </li>
                        <li data-aos="fade-up" data-aos-duration="2000" class="comp6OutLi3">
                            <h2 class="comp6TextTitle3">Energy Saving</h2>
                            <ul class="comp6InnerUl">
                                <li>보일러 제어</li>
                                <li>에어컨 제어</li>
                            </ul>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
        <!-- hotel IOT Section -->
        <div class="comp7">
            <div class="comp7LeftDiv">
                <div class="comp7LeftImgs">
                    <img data-aos="zoom-in" data-aos-duration="2000" class="first7Img" src="../assets/iot/hotelIOTimg.png"/>
                </div>
            </div>
            <div class="comp7RightDiv">
                <div class="comp7RightText">
                    <h1 data-aos="fade-up" data-aos-duration="1000" >IOT 객실제어와<br/>원격 객실 관리 서비스</h1>
                    <ul>
                        <li data-aos="fade-up" data-aos-duration="1000" class="comp7OutLi1">
                            <h2 class="comp7TextTitle1">Keyless 도어락</h2>
                            <ul class="comp7InnerUl">
                                <li>비대면 호텔 예약</li>
                                <li>비대면 출입 인증</li>
                            </ul>
                        </li>
                        <li data-aos="fade-up" data-aos-duration="1500" class="comp7OutLi2">
                            <h2 class="comp7TextTitle2">객실 관리</h2>
                            <ul class="comp7InnerUl">
                                <li>조명 제어</li>
                                <li>커튼 제어</li>
                                <li>AI Speaker</li>
                                <li>DND/MUR</li>
                            </ul>
                        </li>
                        <li data-aos="fade-up" data-aos-duration="2000" class="comp7OutLi3">
                            <h2 class="comp7TextTitle3">Amenity 서비스</h2>
                            <ul class="comp7InnerUl">
                                <li>비대면 모바일 Amenity 서비스</li>
                            </ul>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
        <!-- IOT 아키텍처 Section -->
        <div class="comp8">
            <h1 data-aos="fade-up" data-aos-duration="2000" >IOT Platform Architecture</h1>
            <div data-aos="fade-up" data-aos-duration="2000"  class="comp8InnerBox">
                <img src="../assets/iot/iotArchitecture.png"/>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'IotSection',
        data() {
            return {

            }
        }
    }
</script>

<style>
@import '../css/mainStyle.css';

@media (max-width: 750px) {
    .comp8 {
        width: 100%;
        height: 50vh !important;
        text-align: center;
        margin-top: 200px;
        /* background-color: red; */
    }
    .comp8 h1{
        font-size: 2em !important;
        font-weight: bold;
        color: rgb(68,95,145);
        margin-bottom: 50px !important;
    }
    .comp8 img {
        width: 100% !important;
    }
    .comp8InnerBox {
        padding: 30px !important;
        background-color: rgb(230,230,230);
    }
    .middleConTitle {
        margin-top: 0px;
        margin-bottom: 100px;
        font-size: 40px !important;
        color: white;
    }
    .middleContents {
        width: 100%;
        height: 60vh !important;
        font-size: 50px;
        text-align: center;
        color: rgb(0,121,188);
        font-weight: bold;
        background-color: rgb(240,240,240);
        padding-top: 100px;
    }
    .middleContents h1 {
        font-size: 30px;
    }
    .middleImgs {
        width: 100% !important;
        height: 30vh !important;
        /* border:1px solid red; */
        margin: 0 auto;
        padding: 0px !important;
    }
    .middleImgs li img {
        width: 100%;
    }
    .middleImgs img {
        width: 90%;
        margin-bottom: 10px;
    }
    .middleImgs li {
        width: 30% !important;
        display: inline-block;
    }
    .comp4 {
        height: 50vh !important;
        padding-top: 100px;
    }
    .comp4After {
        content: "";
        width: 80% !important;
        height: 40% !important;
        background-color: rgb(255,255,255);
        border-radius: 30px !important;
        position: absolute;
        z-index: 1;
        margin-top: 30px !important;
        margin-left: 10% !important;
    }
    .comp4 h2 {
        font-family:Arial, Helvetica, sans-serif;
        height: 50px !important;
        font-size: 1.2em !important;
        font-weight: bold;
        line-height: 0px !important;
        color: rgb(0,121,188);
        position: absolute;
        z-index: 3;
        margin: -30px 0px 0px 15% !important;
    }
    .comp4 img {
        position: absolute;
        z-index: 3;
        width: 70% !important;
        margin: 30px 0px 0px 15% !important;
    }
    .comp5 {
        width: 100%;
        height: 80vh !important;
        background-image: linear-gradient(to bottom, rgb(240,240,240), rgb(255,255,255));
        /* border: 1px solid red; */
    }
    .comp5:after {
        content: "";
        display: block;
        clear: both;
    }
    .comp5LeftDiv {
        width: 100% !important;
        height: 300px !important;
        float: left;
    }
    .comp5LeftDiv img{
        width: 60%; 
        margin-left: 20% !important;
        margin-top: 0px !important;
    }
    .comp5RightDiv {
        width: 90% !important;
        height: 40% !important;
        display: inline-block;
        margin-left: 10%;
        /* padding: 10%; */
    }
    .comp5RightDiv h1 {
        font-size: 2em !important;
        font-weight: bold;
        color: rgb(68,95,145);
        line-height: 30px !important;
        margin-bottom: 50px;
    }
    .comp5RightText {
        width: 85% !important;
        font-size: 12px !important;
        margin-left: 0px !important;
        color: rgb(150,150,150);
        line-height: 20px !important;
        margin-top: 0px !important;
        margin-right: 0px !important;
    }
    .comp5RightDiv span {
        color: rgb(255,192,0);
    }
    .comp6 {
        width: 100%;
        height: 150vh !important;
        background-color: white;
    }
    .comp6LeftDiv {
        width: 100% !important;
        height: 500px !important;
        float: left;
    }
    .comp6LeftImgs {
        width: 80%;
        height: 100%;
        margin-left: 40px !important;
        /* border: 1px solid red; */
    }
    .comp6LeftDiv img:first-child{
        width: 220px !important; 
        margin-left: 42px !important;
        margin-top: 125px !important;
        position: absolute;
        z-index: 2;
    }
    .comp6LeftDiv img:nth-child(2){
        width: 300px !important; 
        margin-left: 0px !important;
        margin-top: 80px;
        position: absolute;
        z-index: 2;
        /* border: 1px solid red; */
    }
    .comp6RightDiv {
        width: 100% !important;
        height: 50% !important;
        display: inline-block;
    }
    .comp6RightDiv h1 {
        font-size: 1.5em !important;
        font-weight: bold;
        color: rgb(68,95,145);
        line-height: 30px !important;
        margin-bottom: 50px;
        margin-left: -40px;
    }
    .comp6RightText {
        width: 65%;
        margin-left: 5em;
        color: rgb(150,150,150);
        line-height: 40px;
    }
    .comp6RightText ul h2{
        font-size: 15px !important;
        font-weight: bold;
    }
    .comp6InnerUl {
        font-size: 15px !important;
    }
    .comp7 {
        width: 100%;
        height: 150vh !important;
        background-color: white;
    }
    .comp7LeftDiv {
        width: 100% !important;
        height: 500px !important;
        float: left;
    }
    .comp7LeftImgs {
        width: 60% !important;
        height: 100%;
        margin-left: 30px !important;
        /* border: 1px solid red; */
    }
    .comp7LeftDiv img:first-child{
        width: 250px !important; 
        margin-left: 30px;
        margin-top: 100px;
        position: absolute;
        z-index: 2;
    }
    .comp7RightDiv {
        width: 100% !important;
        height: 500px !important;
        display: inline-block;
    }
    .comp7RightDiv h1 {
        font-size: 1.5em !important;
        font-weight: bold;
        color: rgb(68,95,145);
        line-height: 30px !important;
        margin-bottom: 50px;
        margin-left: -40px;
    }
    .comp7RightText {
        width: 65%;
        margin-left: 5em;
        color: rgb(150,150,150);
        line-height: 40px;
    }
    .comp7RightText ul h2{
        font-size: 15px !important;
        font-weight: bold;
    }
    .comp7InnerUl {
        font-size: 15px !important;
    }
}

.outDiv {
    width: 100%;
}
.middleContents {
    width: 100%;
    height: 110vh;
    font-size: 50px;
    text-align: center;
    color: rgb(0,121,188);
    font-weight: bold;
    background-color: rgb(240,240,240);
    padding-top: 100px;
}
.middleConTitle {
    margin-top: 0px;
    margin-bottom: 100px;
    font-size: 100px;
    color: white;
}
.middleImgs {
    width: 80%;
    height: 80vh;
    /* border:1px solid red; */
    margin: auto;
    padding: 50px;
}
.middleImgs li img {
    width: 100%;
}
.middleImgs img {
    width: 90%;
    margin-bottom: 20px;
}
.middleImgs li {
    width: 25%;
    display: inline-block;
}
.comp4 {
    width: 100%;
    height: 100vh;
    /* background-image: linear-gradient(to bottom, rgb(240,240,240), rgb(255,255,255), rgb(255,255,255)); */
    background-color: rgb(240,240,240);
    padding-top: 100px;
}
.comp4After {
    content: "";
    width: 75%;
    height: 90%;
    background-color: rgb(255,255,255);
    border-radius: 100px;
    position: absolute;
    z-index: 1;
    margin-top: 100px;
    margin-left: 13em;
}
.comp4Triangle {
  width: 0;
  height: 0;
  border-bottom: 50px solid white;
  border-top: 50px solid transparent;
  border-left: 50px solid transparent;
  border-right: 50px solid transparent;
  position: absolute;
  z-index:2;
  margin-top: -100px;
  margin-left: 20em;
}
.comp4 h2 {
    font-family:Arial, Helvetica, sans-serif;
    height: 100px;
    font-size: 3em;
    font-weight: bold;
    line-height: 60px;
    color: rgb(0,121,188);
    position: absolute;
    z-index: 3;
    margin: 1em 0px 1em 6em;
}
.comp4 img {
    position: absolute;
    z-index: 3;
    width: 60%;
    margin: 10em 0px 0px 25em;
}

/* smart factory css */
.comp5 {
    width: 100%;
    height: 100vh;
    background-image: linear-gradient(to bottom, rgb(240,240,240), rgb(255,255,255));
    /* border: 1px solid red; */
}
.comp5:after {
    content: "";
    display: block;
    clear: both;
}
.comp5LeftDiv {
    width: 50%;
    height: 100%;
    float: left;
}
.comp5LeftDiv img{
    width: 60%; 
    margin-left: 20em;
    margin-top: 10em;
}
.comp5RightDiv {
    width: 50%;
    height: 100%;
    display: inline-block;
}
.comp5RightDiv h1 {
    font-size: 1.5em;
    font-weight: bold;
    color: rgb(68,95,145);
    line-height: 50px;
    margin-bottom: 50px;
}
.comp5RightText {
    width: 65%;
    font-size: 1.5em;
    margin-left: 3em;
    color: rgb(150,150,150);
    line-height: 40px;
    margin-top: 8em;
}
.comp5RightDiv span {
    color: rgb(255,192,0);
}

/* camping iot css */
.comp6 {
    width: 100%;
    height: 100vh;
    background-color: white;
}
.comp6LeftDiv {
    width: 50%;
    height: 100%;
    float: left;
}
.comp6LeftImgs {
    width: 80%;
    height: 100%;
    margin-left: 20em;
    /* border: 1px solid red; */
}
.comp6LeftDiv img:first-child{
    width: 380px; 
    margin-left: 30px;
    margin-top: 160px;
    position: absolute;
    z-index: 2;
}
.comp6LeftDiv img:nth-child(2){
    width: 530px; 
    margin-left: -50px;
    margin-top: 80px;
    position: absolute;
    z-index: 2;
    /* border: 1px solid red; */
}
.comp6RightDiv {
    width: 50%;
    height: 100%;
    display: inline-block;
}
.comp6RightDiv h1 {
    font-size: 2.5em;
    font-weight: bold;
    color: rgb(68,95,145);
    line-height: 60px;
    margin-bottom: 50px;
    margin-left: -40px;
}
.comp6RightText {
    width: 65%;
    margin-left: 5em;
    color: rgb(150,150,150);
    line-height: 40px;
}
.comp6RightText ul h2{
    font-size: 1.5em;
    font-weight: bold;
}
.comp6InnerUl {
    color: rgb(120,120,120);
    list-style-type: disc;
    margin: 0.5em 0px 0.5em 2em;
}
.comp6OutLi1:before {
    content: "";
    position: absolute;
    height: 140px;
    background-color:  rgb(68,95,145);
    border-radius: 0px;
    margin: 6px 0px 10px -40px;
    padding: 10px;
}
.comp6OutLi2:before {
    content: "";
    position: absolute;
    height: 100px;
    background-color: rgb(137,171,228);
    border-radius: 0px;
    margin: 6px 0px 10px -40px;
    padding: 10px;
}
.comp6OutLi3:before {
    content: "";
    position: absolute;
    height: 100px;
    background-color: rgb(173,196,236,0.5);
    border-radius: 0px;
    margin: 6px 0px 10px -40px;
    padding: 10px;
}

/* hotel iot css */
.comp7 {
    width: 100%;
    height: 100vh;
    background-color: white;
}
.comp7LeftDiv {
    width: 50%;
    height: 100%;
    float: left;
}
.comp7LeftImgs {
    width: 80%;
    height: 100%;
    margin-left: 20em;
    /* border: 1px solid red; */
}
.comp7LeftDiv img:first-child{
    width: 380px; 
    margin-left: 30px;
    margin-top: 100px;
    position: absolute;
    z-index: 2;
}
.comp7RightDiv {
    width: 50%;
    height: 100%;
    display: inline-block;
}
.comp7RightDiv h1 {
    font-size: 2.5em;
    font-weight: bold;
    color: rgb(68,95,145);
    line-height: 60px;
    margin-bottom: 50px;
    margin-left: -40px;
}
.comp7RightText {
    width: 65%;
    margin-left: 5em;
    color: rgb(150,150,150);
    line-height: 40px;
}
.comp7RightText ul h2{
    font-size: 1.5em;
    font-weight: bold;
}
.comp7InnerUl {
    color: rgb(120,120,120);
    list-style-type: disc;
    margin: 0.5em 0px 2em 2em;
}
.comp7TextTitle1 {
    color: rgb(68,95,145);
}
.comp7TextTitle2 {
    color: rgb(137,171,228);
}
.comp7TextTitle3 {
    color: rgb(173,196,236);
}
.comp7OutLi1:before {
    content: "";
    position: absolute;
    height: 100px;
    background-color:  rgb(68,95,145);
    border-radius: 0px;
    margin: 6px 0px 10px -40px;
    padding: 10px;
}
.comp7OutLi2:before {
    content: "";
    position: absolute;
    height: 180px;
    background-color: rgb(137,171,228);
    border-radius: 0px;
    margin: 6px 0px 10px -40px;
    padding: 10px;
}
.comp7OutLi3:before {
    content: "";
    position: absolute;
    height: 70px;
    background-color: rgb(173,196,236,0.5);
    border-radius: 0px;
    margin: 6px 0px 10px -40px;
    padding: 10px;
}
.comp8 {
    width: 100%;
    height: 90vh;
    text-align: center;
    /* background-color: red; */
}
.comp8 h1{
    font-size: 3em;
    font-weight: bold;
    color: rgb(68,95,145);
    margin-bottom: 100px;
}
.comp8 img {
    width: 50%;
}
.comp8InnerBox {
    padding: 50px;
    background-color: rgb(230,230,230);
}
</style>