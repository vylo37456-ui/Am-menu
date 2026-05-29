
<style>
body{
background:black;
color:#ff0033;
font-family:Arial;
text-align:center;
}

.box{
margin:20px;
padding:25px;
border:2px solid #ff0033;
border-radius:20px;
box-shadow:0 0 25px #ff0033;
}

.btn{
display:inline-block;
background:#ff0033;
color:white;
padding:12px 22px;
margin:10px;
border-radius:12px;
font-weight:bold;
}
</style>

<div class="box">

<h2>⚡ HEAD LOCK SYSTEM ⚡</h2>

<div class="btn">Head Tracking : ON</div>
<div class="btn">Aim Assist : ON</div>
<div class="btn">Drag Smooth : ON</div>
<div class="btn">Aim Stable : ON</div>
<div class="btn">Touch Boost : ON</div>

<h2>📱 SUPPORT 📱</h2>

<p>ALL ANDROID</p>
<p>ALL iPHONE</p>

<h2>🚀 STATUS 🚀</h2>

<p>NO KEY VERSION</p>
<p>ULTRA SMOOTH UI</p>

</div>
<!DOCTYPE html>
<html>
<head>
<title>Neon Menu</title>

<style>
body{
    background:black;
    font-family:Arial;
    text-align:center;
    color:#ff0033;
}

.box{
    margin:40px auto;
    padding:30px;
    width:80%;
    border:2px solid #ff0033;
    border-radius:20px;
    box-shadow:0 0 25px #ff0033;
}

button{
    background:#ff0033;
    color:white;
    border:none;
    padding:15px 25px;
    margin:10px;
    border-radius:12px;
    font-size:18px;
    cursor:pointer;
    box-shadow:0 0 10px #ff0033;
}

.off{
    background:gray;
    box-shadow:0 0 10px gray;
}
</style>
</head>

<body>

<div class="box">

<h1>HEAD LOCK SYSTEM</h1>

<button id="aimBtn" onclick="toggleAim()">
Aim Assist : OFF
</button>

<button id="smoothBtn" onclick="toggleSmooth()">
Drag Smooth : OFF
</button>

</div>

<script>

let aim = false;
let smooth = false;

function toggleAim(){
    aim = !aim;

    let btn = document.getElementById("aimBtn");

    if(aim){
        btn.innerHTML = "Aim Assist : ON";
        btn.classList.remove("off");
    }else{
        btn.innerHTML = "Aim Assist : OFF";
        btn.classList.add("off");
    }
}

function toggleSmooth(){
    smooth = !smooth;

    let btn = document.getElementById("smoothBtn");

    if(smooth){
        btn.innerHTML = "Drag Smooth : ON";
        btn.classList.remove("off");
    }else{
        btn.innerHTML = "Drag Smooth : OFF";
        btn.classList.add("off");
    }
}

</script>

</body>
</html>
