<template>
    <div class="new-page">
        <p><img src="../assets/tuition-and-fees.png"/><span class="fees">RECEIVED PAGE</span></p>
        <p class="stup"><img src="../assets/statistics.png"/><span class="spp">GENERAL STATISTICS</span></p>
        
        <div>
        <div class="threegraphs">
            <p class="text">STUDENTS</p>
            <p class="figure">50,000</p>
            <p class="report">VIEW REPORTS</p>
                <img src="../assets/plus4.png" class="graphimg"/>
        </div>
        <div class="threegraphs">
            <p class="text">PARENTS</p>
            <p class="figure">15,000</p>
            <p class="report">VIEW REPORTS</p>
                <img src="../assets/plus13.png" class="graphimg"/>
        </div>
        <div class="threegraphs">
            <p class="text">TEACHERS</p>
            <p class="figure">5000</p>
            <p class="report">VIEW REPORTS</p>
                <img src="../assets/minus12.png" class="graphimg"/>
        </div>
        </div>

        <div>
            <p class="abst"><img src="../assets/absentstudents.png" /><span>ABSENT STUDENTS</span></p>
        </div>
        <div class="lower">
        <div class="smaller">
            <p class="percent">94.6%</p>
            <p class="text2">Student Attendance</p>
                <br>
            <p class="percent2">6</p>
            <p class="text2">No of students absent</p>
            
            <img src="../assets/plus4.png" class="graphimages"/>
            <img src="../assets/minus12.png" class="graphimages2"/>
        </div>
        </div>

    </div>
</template>

<style scoped>
    .new-page {
        margin-left: 270px;
    }
    p, p img, span {
        margin-left: 10px;
        margin-bottom: -10px;
    }
    .fees {
        margin-left: 10px;
        color: #3B3B3B;
        font-size: 14px;
    }
    .stup {
        margin-top: 20px;
        color: #3B3B3B;
        font-size: 14px;
    }
    .abst {
        margin-bottom: 15px;
    }
    .threegraphs {
        margin-top: 30px;
        width: 350px;
        height: 90px;
        background: #FFFFFF;
        border: 1px solid rgba(189, 189, 189, 0.25);
        box-sizing: border-box;
        box-shadow: 0px 4.71062px 23.5531px rgba(0, 0, 0, 0.07);
        border-radius: 4.71062px;
        margin-bottom: 10px;
        margin-right: 10px;
    }
    .text {
        font-size: 10px;
        color: #BDBDBD;
        margin-left: 20px;
        margin-top: 10px;
    }
    .figure {
        font-weight: 600;
        font-size: 24px;
        color: #3B3B3B;
        margin-top: 10px;
        margin-left: 20px;
    }
    .report {
        font-weight: bold;
        font-size: 10px;
        color: #1B75BB;
        margin-top: 10px;
        margin-left: 20px;
    }
    .graphimg {
        float: right;
        margin-top: -60px;
        margin-right: 10px;
    }
    .graphimages {
        float: right;
        margin-top: -140px;
        margin-right: 10px;
    }
    .graphimages2 {
        float: right;
         margin-top: -10px;
        margin-right: 10px;
    }
</style>
