<template>
    <div class="footerSec">
        <div class="LeftFooter">
            
        </div>
        <div class="RightFooter">
            <ul>
                <li><h1>LINKVALUE</h1></li>
                <li>
                    <span class="spanRightMG">링크밸류</span>
                    <span class="spanRightMG">대표 : 양기훈</span>
                    <span>주소 : 경기도 수원시 영통구 대학4로17 206호</span>
                </li>
                <li>
                    <span class="spanRightMG">MAIL : yanggihoon@gmail.com</span>
                    <span>사업자등록번호 : 195-14-00678</span>
                    <span class="copyRihgt">Copyrightⓒ2023. LINKVALUE ALL rights reserved.</span>
                </li>
            </ul>
        </div>
    </div>
</template>

<script>
    export default {
        name: "FooterSection",
        data() {
            return{

            }
        },
    }
</script>

<style>
@import '../css/mainStyle.css';

@media (max-width: 750px) {
    .RightFooter {
        width: 100%;
        height: 200px !important;
        /* height: 100%; */
    }
    .copyRihgt {
        color: rgb(100,100,100);
        font-size: 10px !important;
        margin-top:10px;
        display:block !important;
        height: 20px !important;
    }
    .RightFooter ul {
        color: rgb(200,200,200);
        line-height: 30px !important;
        font-size: 1em;
        margin-top: 30px;
        margin-left: 20px !important;
    }
    .RightFooter li {
        font-size: 12px;
    }
    .footerSec {
        height: 200px !important;
        margin-top: 0px !important;
    }
    .spanRightMG {
        margin-right: 12px !important;
    }
}
.footerSec {
    font-family:  sans-serif;
    background-color: rgb(50,50,50);
    width: 100%;
    height: 30vh;
    /* border: 1px solid red; */
}

.RightFooter {
    width: 100%;
    height: 100%;
    display: inline-block;
}
.RightFooter ul {
    color: rgb(200,200,200);
    line-height: 40px;
    font-size: 1em;
    margin-top: 30px;
    margin-left: 20%;
}
.RightFooter ul li:first-child {
    color: rgb(38,118,218);
}
.RightFooter h1 {
    font-size: 1.3em;
    font-weight: bold;
    display: inline-block;
    margin-right: 15px;
}
.spanRightMG {
    margin-right: 20px;
}
.copyRihgt {
    color: rgb(100,100,100);
    font-size: 16px;
    margin-top:10px;
    display:block !important;
}
.copyRightLi {
    margin-top: 20px;
}
</style>