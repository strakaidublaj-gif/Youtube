<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>Nisa ❤️</title>

<style>
body{
  margin:0;
  background:black;
  overflow:hidden;
  font-family:Arial;
}

/* Ortadaki yazı */
#main{
  position:absolute;
  top:50%;
  left:50%;
  transform:translate(-50%,-50%);
  font-size:40px;
  text-align:center;
  background:linear-gradient(45deg, red, pink, purple, orange, yellow);
  -webkit-background-clip:text;
  -webkit-text-fill-color:transparent;
}

/* Mesajlar */
.msg{
  position:absolute;
  white-space:nowrap;
  opacity:0;
  transition:0.5s;
}

/* Kalpler */
.heart{
  position:absolute;
  color:red;
  animation:fall linear forwards;
}

@keyframes fall{
  from{ transform:translateY(-50px); }
  to{ transform:translateY(110vh); }
}
</style>
</head>

<body>

<div id="main"></div>

<audio id="music" loop>
  <source src="https://www.soundhelix.com/examples/mp3/SoundHelix-Song-1.mp3">
</audio>

<script>
// 🔤 SIRALI YAZI
const text = "Nisa seni çok seviyorum 😍❤️";
let i = 0;
const main = document.getElementById("main");

function type(){
  if(i <= text.length){
    main.innerText = text.slice(0,i++);
    setTimeout(type, 50);
  }
}
type();

// ❤️ KALP YAĞMURU
function heart(){
  const h = document.createElement("div");
  h.className = "heart";
  h.innerText = "❤️";

  h.style.left = Math.random()*window.innerWidth + "px";
  h.style.fontSize = (Math.random()*20+20)+"px";
  h.style.animationDuration = (Math.random()*3+3)+"s";

  document.body.appendChild(h);
  setTimeout(()=>h.remove(),6000);
}
setInterval(heart,150);

// 🌈 DÜZENLİ GRID + SIRALI
const cols = 10;
const spacingX = window.innerWidth / cols;
const spacingY = 40;

let count = 0;

function createMsg(){
  if(count >= 999) return;

  const m = document.createElement("div");
  m.className = "msg";
  m.innerText = text;

  const col = count % cols;
  const row = Math.floor(count / cols);

  m.style.left = col * spacingX + "px";
  m.style.top = window.innerHeight - (row * spacingY) + "px";

  m.style.color = `hsl(${Math.random()*360},100%,50%)`;
  m.style.fontSize = "16px";

  document.body.appendChild(m);

  // görünür yap
  setTimeout(()=> m.style.opacity = 1, 50);

  count++;
  setTimeout(createMsg, 40); // sırayla çıkış
}
createMsg();

// 🔊 TIKLAYINCA MÜZİK
document.addEventListener("click", ()=>{
  document.getElementById("music").play();
});
</script>

</body>
</html>
