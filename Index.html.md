Index.html  
<!DOCTYPE html>  
<html lang="en">  
<head>  
<meta charset="UTF-8">  
  
<meta name="viewport"  
      content="width=device-width, initial-scale=1.0,  
               maximum-scale=1.0, user-scalable=no">  
  
<title>For Ria ❤️</title>  
  
<style>  
  
* {  
    box-sizing: border-box;  
}  
  
html, body {  
    margin: 0;  
    padding: 0;  
    width: 100%;  
    min-height: 100%;  
}  
  
body {  
    min-height: 100vh;  
    min-height: 100svh;  
  
    display: flex;  
    align-items: center;  
    justify-content: center;  
  
    padding: 20px;  
  
    font-family:  
        -apple-system,  
        BlinkMacSystemFont,  
        "Segoe UI",  
        Roboto,  
        sans-serif;  
  
    background:  
        radial-gradient(  
            circle at 50% 25%,  
            #fff9fc 0%,  
            #ffdce9 45%,  
            #ffb6ce 100%  
        );  
  
    overflow: hidden;  
  
    color: #58152e;  
}  
  
  
/* MAIN CARD */  
  
.card {  
    width: 100%;  
    max-width: 520px;  
  
    padding: 40px 24px;  
  
    text-align: center;  
  
    background: rgba(255,255,255,0.84);  
  
    backdrop-filter: blur(15px);  
    -webkit-backdrop-filter: blur(15px);  
  
    border-radius: 30px;  
  
    border: 1px solid rgba(255,255,255,0.9);  
  
    box-shadow:  
        0 20px 60px rgba(100,20,55,0.20);  
  
    position: relative;  
  
    z-index: 2;  
}  
  
  
/* NAMES */  
  
.names {  
    font-size: 13px;  
  
    letter-spacing: 2.5px;  
  
    text-transform: uppercase;  
  
    color: #805567;  
  
    margin-bottom: 22px;  
}  
  
  
/* HEART */  
  
.main-heart {  
    font-size: 55px;  
  
    line-height: 1;  
  
    margin-bottom: 20px;  
}  
  
  
/* HEADING */  
  
h1 {  
    margin: 0 0 18px;  
  
    font-size: clamp(30px, 8vw, 46px);  
  
    line-height: 1.08;  
  
    font-weight: 800;  
}  
  
  
/* SUBTEXT */  
  
.question {  
    font-size: 18px;  
  
    line-height: 1.5;  
  
    margin-bottom: 32px;  
}  
  
  
/* BUTTON AREA */  
  
.button-area {  
  
    display: flex;  
  
    justify-content: center;  
  
    align-items: center;  
  
    gap: 18px;  
  
    width: 100%;  
  
    min-height: 80px;  
  
    position: relative;  
}  
  
  
/* BOTH BUTTONS */  
  
button {  
  
    width: 135px;  
  
    height: 58px;  
  
    border-radius: 50px;  
  
    border: none;  
  
    font-size: 17px;  
  
    font-weight: 800;  
  
    cursor: pointer;  
  
    -webkit-tap-highlight-color: transparent;  
  
    touch-action: manipulation;  
  
    transition:  
        transform 0.15s ease,  
        box-shadow 0.15s ease;  
}  
  
  
/* YES */  
  
#yesButton {  
  
    background: #ff4f83;  
  
    color: white;  
  
    box-shadow:  
        0 10px 25px rgba(255,79,131,0.30);  
  
    z-index: 5;  
}  
  
  
/* NO */  
  
#noButton {  
  
    background: white;  
  
    color: #765362;  
  
    border: 1px solid #e8c7d4;  
  
    box-shadow:  
        0 8px 20px rgba(80,20,50,0.10);  
  
    z-index: 6;  
}  
  
  
/* LITTLE TEXT */  
  
.choose {  
  
    margin-top: 25px;  
  
    font-size: 15px;  
  
    color: #906879;  
}  
  
  
/* SUCCESS SCREEN */  
  
#success {  
  
    display: none;  
}  
  
  
/* BIG HEART */  
  
.success-heart {  
  
    font-size: 75px;  
  
    margin-bottom: 15px;  
  
    animation: heartbeat 0.7s infinite alternate;  
}  
  
  
@keyframes heartbeat {  
  
    from {  
        transform: scale(1);  
    }  
  
    to {  
        transform: scale(1.15);  
    }  
}  
  
  
/* FALLING HEARTS */  
  
.heart {  
  
    position: fixed;  
  
    pointer-events: none;  
  
    z-index: 100;  
  
    font-size: 25px;  
  
    animation:  
        heartFly 2.5s ease-out forwards;  
}  
  
  
@keyframes heartFly {  
  
    0% {  
  
        opacity: 1;  
  
        transform:  
            translate(0,0)  
            scale(0.4)  
            rotate(0deg);  
    }  
  
    100% {  
  
        opacity: 0;  
  
        transform:  
            translate(var(--x), var(--y))  
            scale(1.5)  
            rotate(var(--rotation));  
    }  
}  
  
  
/* SMALL PHONES */  
  
@media (max-width: 400px) {  
  
    .card {  
        padding: 32px 18px;  
    }  
  
    h1 {  
        font-size: 31px;  
    }  
  
    .question {  
        font-size: 17px;  
    }  
  
    button {  
        width: 120px;  
    }  
  
    .button-area {  
        gap: 12px;  
    }  
}  
  
  
/* SHORT PHONE SCREENS */  
  
@media (max-height: 700px) {  
  
    .card {  
        padding-top: 25px;  
        padding-bottom: 25px;  
    }  
  
    .main-heart {  
        font-size: 45px;  
        margin-bottom: 12px;  
    }  
  
    h1 {  
        margin-bottom: 12px;  
    }  
  
    .question {  
        margin-bottom: 20px;  
    }  
  
    .choose {  
        margin-top: 18px;  
    }  
}  
  
</style>  
</head>  
  
  
<body>  
  
  
<!-- QUESTION SCREEN -->  
  
<div class="card" id="questionScreen">  
  
    <div class="names">  
        BALWANT OBEROI ❤️ RIA SINGH  
    </div>  
  
  
    <div class="main-heart">  
        🥺❤️  
    </div>  
  
  
    <h1>  
        Ria, will you<br>  
        go on a date with me?  
    </h1>  
  
  
    <div class="question">  
        I have a very important question for you...  
    </div>  
  
  
    <div class="button-area" id="buttonArea">  
  
        <button id="yesButton">  
            YES ❤️  
        </button>  
  
        <button id="noButton">  
            NO 🙄  
        </button>  
  
    </div>  
  
  
    <div class="choose">  
        Choose wisely... 😌  
    </div>  
  
</div>  
  
  
  
<!-- SUCCESS SCREEN -->  
  
<div class="card" id="success">  
  
    <div class="success-heart">  
        💖  
    </div>  
  
  
    <h1>  
        I KNEW IT! 😌❤️  
    </h1>  
  
  
    <div class="question">  
  
        <strong>  
            I KNEW IT GONNA BE YES,<br>  
            CAUSE NO OTHER OPTION BABY HAHA!! 😂❤️  
        </strong>  
  
    </div>  
  
  
    <div class="question">  
        See ya sooonnnnnn 🫂🥺  
    </div>  
  
  
    <div style="font-size:40px;">  
        💕 💕 💕  
    </div>  
  
</div>  
  
  
  
<script>  
  
/* =========================  
   NO BUTTON  
========================= */  
  
const noButton =  
    document.getElementById("noButton");  
  
const buttonArea =  
    document.getElementById("buttonArea");  
  
  
let noHasMoved = false;  
  
  
/*  
   Move the NO button somewhere  
   inside the button area.  
  
   It will NEVER move on the  
   initial screen, so YES and NO  
   cannot overlap.  
*/  
  
function moveNoButton() {  
  
    noHasMoved = true;  
  
    const area =  
        buttonArea.getBoundingClientRect();  
  
    const button =  
        noButton.getBoundingClientRect();  
  
  
    /*  
       Calculate safe positions.  
    */  
  
    const maxX =  
        area.width - button.width;  
  
    const maxY =  
        area.height - button.height;  
  
  
    const randomX =  
        Math.max(  
            0,  
            Math.random() * maxX  
        );  
  
  
    const randomY =  
        Math.max(  
            0,  
            Math.random() * maxY  
        );  
  
  
    /*  
       Switch NO to absolute positioning  
       ONLY after she tries to touch it.  
    */  
  
    noButton.style.position = "absolute";  
  
    noButton.style.left =  
        randomX + "px";  
  
    noButton.style.top =  
        randomY + "px";  
}  
  
  
/* Desktop */  
  
noButton.addEventListener(  
    "mouseenter",  
    function() {  
  
        moveNoButton();  
  
    }  
);  
  
  
/* iPhone / Android */  
  
noButton.addEventListener(  
    "touchstart",  
    function(event) {  
  
        event.preventDefault();  
  
        moveNoButton();  
  
    },  
    {  
        passive: false  
    }  
);  
  
  
/* Modern touch devices */  
  
noButton.addEventListener(  
    "pointerdown",  
    function(event) {  
  
        if (event.pointerType === "touch") {  
  
            event.preventDefault();  
  
            moveNoButton();  
        }  
  
    }  
);  
  
  
/* =========================  
   YES BUTTON  
========================= */  
  
const yesButton =  
    document.getElementById("yesButton");  
  
  
yesButton.addEventListener(  
    "click",  
    function() {  
  
        /*  
           Hide question.  
        */  
  
        document.getElementById(  
            "questionScreen"  
        ).style.display = "none";  
  
  
        /*  
           Show success.  
        */  
  
        document.getElementById(  
            "success"  
        ).style.display = "block";  
  
  
        /*  
           HEART EXPLOSION  
        */  
  
        createHearts();  
  
    }  
);  
  
  
/* =========================  
   HEART EFFECT  
========================= */  
  
function createHearts() {  
  
    const hearts = [  
        "❤️",  
        "💖",  
        "💕",  
        "💗",  
        "💘",  
        "🥰",  
        "💓"  
    ];  
  
  
    for (  
        let i = 0;  
        i < 120;  
        i++  
    ) {  
  
        const heart =  
            document.createElement("div");  
  
  
        heart.className = "heart";  
  
  
        heart.innerText =  
            hearts[  
                Math.floor(  
                    Math.random() *  
                    hearts.length  
                )  
            ];  
  
  
        /*  
           Start around the middle  
           of the screen.  
        */  
  
        heart.style.left =  
            (20 + Math.random() * 60) +  
            "vw";  
  
  
        heart.style.top =  
            (55 + Math.random() * 20) +  
            "vh";  
  
  
        /*  
           Random flight.  
        */  
  
        heart.style.setProperty(  
            "--x",  
            (Math.random() * 500 - 250) +  
            "px"  
        );  
  
  
        heart.style.setProperty(  
            "--y",  
            (-300 - Math.random() * 600) +  
            "px"  
        );  
  
  
        heart.style.setProperty(  
            "--rotation",  
            (Math.random() * 360 - 180) +  
            "deg"  
        );  
  
  
        /*  
           Different timing.  
        */  
  
        heart.style.animationDelay =  
            (Math.random() * 0.8) +  
            "s";  
  
  
        document.body.appendChild(  
            heart  
        );  
  
  
        /*  
           Remove after animation.  
        */  
  
        setTimeout(  
            function() {  
  
                heart.remove();  
  
            },  
            3500  
        );  
  
    }  
  
}  
  
</script>  
  
</body>  
</html>  
