<template>
    <div class="navbar">
        <input type="search" name="searchbar" class="search"/>
        <img src="../assets/Alarm.png" alt="alarm" class="alarm">
        <p class="name">Ukauwa David<br><span>ukauwadavid@gmail.com</span></p>
        <p class="pic"><img src="../assets/man.png" class="man"/><i class="fa fa-caret-down toggle" id="toggle"></i></p>
    </div>
</template>

<style>
    .navbar {
        margin-left: 260px;
    }
    .search{
        background-color: #ffffff;
        width: 700px;
        height: 38px;
        top: 21px;
        /* background-image: url(../assets/search.png); */
        border-radius: 3px;
        border: 1px solid rgba(189, 189, 189, 0.25);
        box-sizing: border-box;
        box-shadow: 0px 2px 9px rgba(196, 196, 196, 0.11);

    }
    .name {
        font-size: 12px;
        color: #31393C;
        margin-top: 20px;
        margin-left: -10px;
    }
    .alarm {
        margin-right: -30px;
    }
    span {
        font-size: 11px;
        color: #90A4AE;
    }
    .pic {
        margin-left: -40px;
    }
    .man {
        margin-right: 10px;
        margin-top: 5px;
    }
    .toggle {
        color: #90A4AE;
        line-height: 3.2;
    }
</style>
