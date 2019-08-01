<template>
    <div class="new-page">
        <p><img src="../assets/tuition-and-fees.png"/><span class="fees">INVOICE PAGE</span></p>
        <div>
            <img src="../assets/graph.png" class="graph"/>
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
    .graph {
        width: 760px;
        height: 370px;
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
</style>

