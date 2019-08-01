<template>
    <div class="performance">
        <p class="stup"><img src="../assets/performance.png"/><span class="spp">STUDENT PERFORMANCE</span></p>
        <p class="viewreports">VIEW REPORTS</p>
        <p class="stup" style="margin-left: 720px; margin-top:10px;"><img src="../assets/statistics.png"/><span class="spp">GENERAL STATISTICS</span></p>
        <div>
            <img src="../assets/graph.png" class="graph"/>
        </div>
        <div class="grapharea">
        
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
    </div>
</template>

<style>
    /* .performance {
        margin-left: 280px;
    } */
    .viewreports {
        font-weight: bold;
        font-size: 10px;
        margin-bottom: -25px;
        margin-top: 10px;
        margin-left: 630px;
        color: #1B75BB;
    }
    .stup {
        margin-top: 20px;
        margin-bottom: -25px;
        color: #3B3B3B;
        font-size: 10px;
    }
    .spp {
        margin-left: 10px;
    }
    .grapharea {
        float: right;
        margin-top: -340px;
    }
    .graph {
        margin-left: -30px;
        width: 760px;
        height: 370px;
    }
    .threegraphs {
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
        margin-bottom: 20px;
        margin-top: -50px;
        margin-left: 20px;
    }
    .report {
        font-weight: bold;
        font-size: 10px;
        color: #1B75BB;
        margin-top: -20px;
        margin-left: 20px;
    }
    .graphimg {
        float: right;
        margin-top: -85px;
        margin-right: 10px;
    }
</style>
