 <!-- <div class="cloud"></div>
<div class="cont ">
<div class="sun">
    <div class="eyes">
        <div class="ineye"></div>
    </div>
    <div class="eyes">
        <div class="ineye"></div>
    </div>
    <div class="smile"></div>
</div>
</div>
<div class="mooncont hide">
    <div class="moon ">
        <div class="mooneye">
            <div class="eyeball"></div>
        </div>
       <div class="mooneye">
        <div class="eyeball"></div></div>
        <div class="smile2"></div>
        </div>
        </div>

********************css***************
*{
   padding: 0;
  margin: 0;

}
body{
    background-color:rgb(92, 249, 254);
}
.sun{
    height:200px;
    width:200px;
    background-color: yellow;
    border: 2px solid black;
    border-radius: 50%;
    display: flex;
    justify-content: center;
    align-items: center;
}
.cont{
    display:flex;
    justify-content: space-evenly;
}
.eyes{
    height:70px;
    width:70px;
    position: relative;
    margin-bottom: 35px;
    margin-left: 35px;
    border:2px solid #000000;
    border-radius: 50%;
    display: flex;
    justify-content: center;
    align-items: center;
}
.ineye{
    height:40px;
    width:40px;
    background-color: #000000;
    margin-top: 27px;
    border:2px solid #000000;
    border-radius: 50%;
}
.smile{
    height:40px;
    width:10rem;
    border:5px solid #000000;
    border-radius: 50%;
    position: relative;
    top:50px;
    right:80px;
    border-top: none;
    border-left: none;
    border-right: none;
}
.road{
    height:200px;
    width: 100%;
    border: 4px solid black;
    display: flex;
    flex-wrap: wrap;
    background-color: rgb(149, 148, 148);
    justify-content: center;
    align-items: center;
}
 .track{
    height:0px;
    width:100%;
    border:2px dashed black;
    margin-bottom: 100px;
} 
.wheel1{
    height:50px;
    width:50px;
    border:5px solid black;
    border-radius: 50%;
    position: relative;
    right:13rem;
     display: flex;
    justify-content: center;
    align-items: center;
    margin-left: 25px;

}
.wheel2{
    height:50px;
    width:50px;
    border:5px solid black;
    border-radius: 50%;
    position: relative;
    right:13rem;
     display: flex;
    justify-content: center;
    align-items: center;
    margin-left: 25px;

}
.wheel3{
    height:50px;
    width:50px;
    border:5px solid black;
    border-radius: 50%;
    position: relative;
    right:13rem;
     display: flex;
    justify-content: center;
    align-items: center;
    margin-left: 25px;

}
.wheel4{
    height:50px;
    width:50px;
    border:5px solid black;
    border-radius: 50%;
    position: relative;
    right:13rem;
     display: flex;
    justify-content: center;
    align-items: center;
    margin-left: 25px;

}


.car2{
    display: flex;
    text-align: center;
}
.inwheel{
     height:30px;
    width:30px;
    border:2px solid rgb(6, 5, 5);
    border-radius: 50%; 
    list-style:25px;
    background-color: #000000;
}
.carbody{
    display: flex;
    justify-content: center;
    justify-content: space-evenly;
    height:150px;
    width:350px;
    border:5px solid black;
    position: relative;
    top:15px;
    left:5px;
    background-color: rgb(224, 66, 66);
    border-top-right-radius: 50px;
    border-bottom-right-radius: 10px;
    border-top-left-radius: 10px;
    margin-top: 242px;
}

.window{
    height:50px;
    width:50px;
    background-color: rgb(116, 235, 248);
    border:5px solid black;
    position: relative;
    top:25px;
    border-radius: 10px;
}
@keyframes start {
    0%{
        transform: translatex(0);
    }
    100%{
        transform: translatex(800px);
    }
}

.btn{
    background-color:darksalmon;
    height:50px;
    width:100px;
    border-radius: 10px;
    position: relative;
    top:30px;
    border:2px solid rgb(7, 4, 4);
    left:20rem;
    font-size: 15px;
    margin-top: 20px;
    color: rgb(12, 2, 11);
    cursor: pointer;
}
.btn:hover ,.startBtn:hover{
    border:3px solid rgb(255, 251, 251);
}
.startBtn{
    height:50px;
    width:100px;
    border-radius: 10px;
    position: relative;
    top:100px;
    left:13.6rem;
    border:2px solid rgb(15, 4, 4);
    font-size: 25px;
    background-color: chartreuse;
}
.mooncont{
    background-color: red;
    height:100px;
    width:0px;
}
.moon{
    height:200px;
    width:200px;
    border:2px solid black;
    border-radius: 50%;
    position: relative;
    bottom:100px;
    left:270px;
    background-color: grey;
    display:flex;
    justify-content: center;
    align-items: center;
}

.hide{
    display: none;
}
.mooneye{
    height:60px;
    width:50px;
    border:2px solid rgb(248, 242, 242);
    border-radius: 50%;
    position: relative;
    margin-left: 20px;
    bottom:20px;
    right:10px;
    left:14px;
    display:flex;
    justify-content: center;
    align-items: center;
}
.eyeball{
    height:40px;
    width:40px;
    border-radius: 50%;
    background-color: aliceblue;
    position: relative;
    top:10px;
}
.smile2{
    height:40px;
    width:50px;
    border:10px solid black;
    border-top: none;
     border-left: none;
    border-right: none;
    border-radius: 50%;
    position: relative;
    top:50px;
    right:70px;

}  
