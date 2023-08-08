<template>
    <div class="comp2">
        <!-- 회사연혁 라인부분 -->
        <div class="historyLineDiv" 
            data-aos="fade-down"
            data-easing="linear"
            data-aos-duration="1500">
            <div class="lineInerDiv">
                <img src="../assets/history/historyIcon1.png"/>
            </div>
            <div class="lineInerDiv">
                <img src="../assets/history/historyIcon2.png"/>
            </div>
            <div class="lineInerDiv">
                <img src="../assets/history/historyIcon3.png"/>
            </div>
            <div class="lineInerDiv">
                <img src="../assets/history/historyIcon4.png"/>
            </div>
            <div class="lineInerDiv">
                <img src="../assets/history/historyIcon5.png"/>
            </div>
        </div>
        <!-- 회사연혁 이미지 부분 -->
        <div class="historyImgSec">
            <h1>HISTORY</h1>
            <img src="../assets/history/historyPage.png"/>
        </div>
        <!-- 회사연혁 텍스트 부분 -->
        <div class="historyTextSec">
            <div class="contentDiv" data-aos="fade-down" data-aos-duration="2000">
                <div class="yearDiv yearColor0">
                    <h1>2022</h1>
                </div>
                <div class="yearTextDiv">
                    <ul>
                        <li>캠프락 카라반 IoT 플랫폼 개발</li>
                        <li>세미나노 연구센터 스마트공방 시스템 개발</li>
                        <li>위팩토리 유망연구소 Backend 개발</li>
                        <li>판도플랫폼 메신저 챗봇 플랫폼 개발</li>
                    </ul>
                </div>
            </div>
            <div class="contentDiv" data-aos="fade-down" data-aos-duration="2000">
                <div class="yearDiv yearColor1">
                    <h1>2021</h1>
                </div>
                <div class="yearTextDiv">
                    <ul>
                        <li>해양복합연구단 RCS-MCS 기반 복함체계 운용 소프트웨어 설계</li>
                        <li>지텔레마 수면마스크 IoT 플랫폼 개발</li>
                        <li>이에스텍 e하우스키핑 호텔 솔루션 개발</li>
                        <li>스마트웨이 SM CBR 시스템 개발</li>
                        <li>헬스맥스 우울증 모니터링 케어 시스템 개발</li>
                    </ul>
                </div>
            </div>
            <div class="contentDiv" data-aos="fade-down" data-aos-duration="2000">
                <div class="yearDiv yearColor2">
                    <h1>2020</h1>
                </div>
                <div class="yearTextDiv moreDown">
                    <ul>
                        <li>에릭슨 LG 5G MANO 네트워크 가상화 개발</li>
                        <li>차량 ICT 기반 긴급구난체계(e-call) CAN 통신 디바이스 개발</li>
                        <li>아주대학교 4차 산업인력양성과정 IoT 교육 커리큘럼 개발</li>
                        <li>우리사이 020 서비스 기술 컨설팅</li>
                    </ul>
                </div>
            </div>
            <div class="contentDiv" data-aos="fade-down" data-aos-duration="2000">
                <div class="yearDiv yearColor3">
                    <h1>2019</h1>
                </div>
                <div class="yearTextDiv moreDown">
                    <ul>
                        <li>컨테이너와 Reverse Proxy 기반의 WAF 솔루션 개발</li>
                        <li>프렌디 카라반 IoT 솔루션 구축</li>
                        <li>협성대학교 IoT Living Lab 구축</li>
                    </ul>
                </div>
            </div>
            <div class="contentDiv" data-aos="fade-down" data-aos-duration="2000">
                <div class="yearDiv yearColor4">
                    <h1>2018</h1>
                </div>
                <div class="yearTextDiv moreDown">
                    <ul>
                        <li>컨테이너 기반의 IoT 미들웨어 개발</li>
                        <li>사업자 설립</li>
                    </ul>
                </div>
            </div>
        </div>
        <!-- 회사연혁 텍스트 끝 -->
    </div>
</template>

<script>
export default {
    name: 'HistorySection',
    data() {
        return{
            yearsArray: [2022,2021,2020,2019,2018]
        }
    },
}
</script>

<style scoped>
@import '../css/mainStyle.css';
@media (max-width: 750px) {
    .historyImgSec{
        display: none !important;
    }
    .active_history_text {
        font-family: 'Impact';
        font-size: 2em;
        margin: 20px 0px 0px 20px;
        color: rgb(0,121,188);
        font-weight: bold;
        display: absolute !important;
        z-index: 100px;
    }
    .historyImgSec h1{
        font-size: 2em !important;
        margin: 10px 30px 10px 60px !important;
    }
    .historyLineDiv {
        width: 20px;
        height: 100vh;
        position: absolute;
        z-index: 1;
        margin-left: 20px !important;
    }
    .historyTextSec {
        width: 90%;
        padding-left: 10%;
    }
    .yearDiv {
        font-size: 10px;
        width: 25%;
        height: 50px;
        margin-left: 20px;
    }
    .yearTextDiv {
        width: 110%;
        height: 80%;
        display: inline-block;
        clear:both;
        text-align: left;
        font-size: 10px;
        color: rgb(100,100,100);
        /* background: red; */
        margin-top: 50px;
        margin-left: 30px;
    }
    .yearTextDiv ul{
        margin-top: 0px; 
        list-style-type: disc;
    }
    .yearTextDiv li {
        height: 20px;
    }
    .contentDiv {
        margin-bottom: 2vh;;
        width: 80%;
        height: 20%;
        /* background-color:blue; */
    }
}
</style>