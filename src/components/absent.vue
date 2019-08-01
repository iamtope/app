<template>
<div class="absentees">
     <p><img src="../assets/absentstudents.png" class="p-img"/><span>ABSENT STUDENTS</span></p>
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
        <div class="larger">
            <table style="width:100%">
                <tr>
                    <th>NAME</th>
                    <th>CLASS</th>
                    <th colspan="2">NUMBER OF DAYS ABSENT</th>
                </tr>
                <tr>
                    <td>Salihu, Attah Chigboza</td>
                    <td>JSS1 Happiness</td>
                    <td>3</td>
                    <td style="color: #1B75BB;"><a>VIEW CONTACT INFORMATION</a></td>
                </tr>
                <tr>
                    <td>Salihu, Attah Chigboza</td>
                    <td>JSS1 Happiness</td>
                    <td>3</td>
                    <td style="color: #1B75BB;"><a>VIEW CONTACT INFORMATION</a></td>
                </tr>
                <tr>
                    <td>Salihu, Attah Chigboza</td>
                    <td>JSS1 Happiness</td>
                    <td>3</td>
                    <td style="color: #1B75BB;"><a>VIEW CONTACT INFORMATION</a></td>
                </tr>
            </table>
            <figure><img src="../assets/triplequestion.png"/></figure>
        </div>
    </div>
</div>
</template>

<style>
.absentees {
    margin-top: -20px;
}
.p-img {
    margin-right: 10px;
}
.lower{
    /* margin-left: 280px; */
    display: flex;
    align-items: flex-start;
    }
    .smaller {
        width: 269px;
        height: 233px;
        background: #FFFFFF;
        border: 1px solid rgba(189, 189, 189, 0.25);
        box-sizing: border-box;
        box-shadow: 0px 7.51481px 37.574px rgba(0, 0, 0, 0.07);
        border-radius: 7.51481px;
        margin-right: 30px;
    }
    .larger {
        width: 823px;
        height: 233px;
        background: #FFFFFF;
        border: 1px solid rgba(189, 189, 189, 0.25);
        box-sizing: border-box;
        box-shadow: 0px 7.51481px 37.574px rgba(0, 0, 0, 0.07);
        border-radius: 7.51481px;
    }
    .percent {
        font-weight: bold;
        font-size: 36px;
        color: #3B3B3B;
        margin-left: 20px;
        margin-bottom: -10px;
        margin-top: 20px;
    }
    .percent2 {
        font-weight: bold;
        font-size: 36px;
        color: #3B3B3B;
        margin-left: 50px;
        margin-bottom: -10px;
        margin-top: 20px;
    }
    .text2 {
        font-size: 10px;
        color: #BDBDBD;
        margin-left: 20px;
    }
    .graphimages {
        float: right;
        margin-top: -190px;
        margin-right: 10px;
    }
    .graphimages2 {
        float: right;
        margin-top: -70px;
        margin-right: 10px;
    }
    table, th, td {
        border: 0.626846px solid #E0E0E0;
        border-collapse: collapse;
        border-left: none;
        border-right: none;
        border-top: none;
        overflow: hidden;
        }
th, td {
    margin-left: 20px;
    padding: 5px;
    text-align: left;
    font-size: 10px;
    color: #3B3B3B;
    height: 55px;    
}
td a {
    text-decoration: none;
    float: right;
     margin-right: 30px;
     font-weight: bold;
}
figure {
    float: right;
    margin-top: -35px;
    margin-right: -25px;
}
</style>

