<template>
    <div class="comp3">
        <div class="compLeftDiv">
            <h1 data-aos="fade-down" data-aos-duration="2000">인공지능 플랫폼<br/> 공동 기술 개발 진행</h1>
            <ol data-aos="fade-down" data-aos-duration="2000">
                <li>IoT센싱 신호처리 알고리즘 디자인</li>
                <li>일상생활 전주기적 행동패턴 수집/분석</li>
                <li>활동/수면 자동전환 데이터 센싱</li>
                <li>수면의 질 측정, 수면 모니터링</li>
                <li>나쁜습관 사전행동원인 분석</li>
                <li>자동 행동인지, 습관패턴 모델링</li>
                <li>건강지식기반 습관개선 케어프로세스</li>
                <li>습관 원인, 동기, 심리 감성변화 측정</li>
            </ol>
        </div>
        <div class="compRightDiv" data-aos="fade-down" data-aos-duration="3000">
            <img class="rightImg" src="../assets/Cooperation.png"/>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'CooperationSection',
        data() {
            return {

            }
        }
    }
</script>

<style>
@import '../css/mainStyle.css';

@media (max-width: 750px) {
    .compLeftDiv {
        width: 100% !important;
        height: 50% !important;
        /* background-color:red; */
        float: left;
    }
    .compLeftDiv h1 {
        font-size: 2em !important;
        text-align: left;
        /* margin: 5em 2em 20px 4em; */
        color: rgb(0,121,188);
        font-weight: bold;
        width: 300px;
        margin: 5em 0px 0px 40px !important;
    }
    .compLeftDiv li {
        width: 300px;
    }
    .compLeftDiv ol {
        text-align: left;
        list-style-type: decimal;
        /* margin: 60px 2em 20px 11em; */
        font-size: 0.8em !important;
        line-height: 40px;
        color: rgb(100,100,100);
        width: 300px;
        margin: 2em 0px 0px 60px !important;
    }
    .compRightDiv {
        width: 300px!important;
        height: 300px !important;
        display: absolute !important;
        z-index: 0px !important;
        margin-left: 5%;
        margin-top: 200px;
    }
    .rightImg {
        width: 100% !important;
        margin-top: 0px !important;
        margin-left: 20px;
    }

}
</style>