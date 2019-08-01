<template>
    <div class="wrapper">
    <div id="sidebar" class="sidenav">
        
        <button class="dropdown-btn active">
            <img src="../assets/schoolLogo.png"/>Handmaid's International
            <i class="fa fa-caret-down" style="color:  #1B75BB;"></i></button>
            <div class="dropdown-container">
            <a href="#">Link 1</a>
            <a href="#">Link 2</a>
            <a href="#">Link 3</a>
        </div>

        <a href="#"><img src="../assets/dashboardlogo.png"/>Dashboard</a>

        <button class="dropdown-btn"><img src="../assets/students.png"/>Students<i class="fa fa-caret-down"></i></button>
        <div class="dropdown-container">
            <a href="#">Link 1</a>
            <a href="#">Link 2</a>
            <a href="#">Link 3</a>
        </div>

        <button class="dropdown-btn"><img src="../assets/employees.png"/>Employees<i class="fa fa-caret-down"></i></button>
        <div class="dropdown-container">
            <a href="#">Link 1</a>
            <a href="#">Link 2</a>
            <a href="#">Link 3</a>
        </div>

        <a href="#"><img src="../assets/parentsguardians.png"/>Guardians</a>

        <button class="dropdown-btn"><img src="../assets/attendance.png"/>Attendance<i class="fa fa-caret-down"></i></button>
        <div class="dropdown-container">
            <a href="#">Link 1</a>
            <a href="#">Link 2</a>
            <a href="#">Link 3</a>
        </div>

        <button class="dropdown-btn"><img src="../assets/finance.png"/>Finance<i class="fa fa-caret-down"></i></button>
        <div class="dropdown-container">
            <a href="#">Link 1</a>
            <a href="#">Link 2</a>
            <a href="#">Link 3</a>
        </div>

        <a href="#"><img src="../assets/subjects.png"/>Subjects</a>    
        <a href="#"><img src="../assets/batches.png"/>Batches</a>
        <a href="#"><img src="../assets/reportcards.png"/>Report Cards</a>
        <a href="#"><img src="../assets/sms.png"/>SMS</a>

        <button class="dropdown-btn"><img src="../assets/events.png"/>Events<i class="fa fa-caret-down"></i></button>
        <div class="dropdown-container">
            <a href="#">Link 1</a>
            <a href="#">Link 2</a>
            <a href="#">Link 3</a>
        </div>
        <hr>
        <a href="#">Settings</a>

        <div class="foot">
            <button class="btn"><img src="../assets/question.png" class="btnimage">Help</button>
            <span class="terms">Terms. Privacy</span>
        </div>
    </div>
    </div>
</template>


<style>
.wrapper {
    display: flex;
    align-items: stretch;
    perspective: 1500px;
}
.sidenav {
    min-width: 250px;
    max-width: 250px;
    background: linear-gradient(136.25deg, #1B75BB 0%, #00ADEE 100%);;
    color: #2C2C2C;
    font-size: 14px;
    font-weight: bold;
    box-shadow: 0px 2px 10px rgba(0, 0, 0, 0.170509);
    position: fixed; /* Fixed Sidebar (stay in place on scroll) */
    z-index: 1; /* Stay on top */
    top: 0; /* Stay at the top */
    left: 0;
    }
.active img {
        height: 40px;
        width: 40px;
        border-radius: 50px;
        border:1px solid #FAD961;
        margin-left: -10px;

    }
.sidenav a, .dropdown-btn {
  padding: 6px 8px 6px 16px;
  text-decoration: none;
  font-size: 14px;
  font-weight: bold;
  color: #ffffff;
  display: block;
  border: none;
  background: none;
  width:100%;
  line-height: 3.5;
  text-align: left;
  outline: none;
}
button .fa {
        float: right;
        line-height: 3.5;
        padding-right: 8px;  
    }
button img, a img {
        margin-right: 10px;
    }
.sidenav a:hover, .dropdown-btn:hover {
  color: #FAD961;
}
.active {
  background-color: #ffffff;
  color:  #2C2C2C;
}

.dropdown-container {
  display: none;
  background-color: #ffffff;
  color:  #2C2C2C;
  padding-left: 8px;
}
.btn {
        width: 100px;
        height: 38px;
        border-radius: 20px;
        background: #ffffff;
        color: #1B75BB;
        margin-bottom: 10px;
    }
    .btnimage {
        margin-right: 5px;
    }
    .terms {
        color: #ffffff;
        margin-left: 15px;
        margin-top: 6px;
        font-size: 14px;
    }
</style>

