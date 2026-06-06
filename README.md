# Para-Henrique-
<img src="fotos/foto1.jpg"><img width="2268" height="4032" alt="image" src="https://github.com/user-attachments/assets/8c593b83-f996-445a-a1f5-eb33f49bda3b" />

<img src="fotos/foto2.jpg">
<img src="fotos/foto3.jpg">
<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Para Henrique ❤️</title>

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial,sans-serif;
}

body{
background:linear-gradient(135deg,#ffb6c1,#ffe4ec);
overflow-x:hidden;
text-align:center;
color:#fff;
}

.hero{
height:100vh;
display:flex;
flex-direction:column;
justify-content:center;
align-items:center;
padding:20px;
}

h1{
font-size:3rem;
margin-bottom:20px;
}

p{
font-size:1.2rem;
}

.botao{
margin-top:25px;
padding:15px 30px;
border:none;
border-radius:30px;
background:white;
color:#ff4f88;
font-size:18px;
cursor:pointer;
}

.section{
padding:60px 20px;
}

.card{
background:rgba(255,255,255,0.2);
backdrop-filter:blur(10px);
padding:25px;
border-radius:20px;
max-width:700px;
margin:auto;
}

.contador{
font-size:2rem;
margin-top:15px;
}

.heart{
position:fixed;
top:-10px;
animation:fall linear infinite;
pointer-events:none;
}

@keyframes fall{
to{
transform:translateY(110vh);
}
}
</style>
</head>

<body>

<div class="hero">
<h1>Henrique ❤️</h1>
<p>Feliz Dia dos Namorados</p>
<button class="botao" onclick="mostrarSurpresa()">
Clique aqui 💕
</button>
</div>

<div class="section">
<div class="card">
<h2>Desde que nos conhecemos...</h2>
<div class="contador" id="contador"></div>
</div>
</div>

<div class="section">
<div class="card">
<h2>Uma mensagem 💌</h2>
<p>
Primeiro Dia dos Namorados com meu chatinho e amor da minha vida kkk! ❤️

Mesmo você me irritando todos os dias, eu ainda continuo te amando e, principalmente, amando ser sua namorada. Até porque você me trata tão bem. Consigo perceber o carinho que você tem comigo, mesmo eu sendo meio coração duro às vezes kkk, mas eu te amo do fundo do meu coração! ❤️‍🩹

Quero que saiba que é com você que quero construir uma família e viver ao lado pelo resto da minha vida, até a última batida do meu coração e o último respiro. Eu te amo, Henrique! ❤️

Às vezes eu penso: e se eu não tivesse te respondido naquele dia? Onde estaríamos agora? O que eu estaria fazendo agora? Nada faz sentido se você não tivesse feito parte disso. Por isso digo que o destino nos uniu da forma mais aleatória possível, com uma simples mensagem em um chat do Instagram.

O que te motivou a fazer aquilo? Kkk. O destino apenas nos uniu, porque você foi feito para mim e eu para você.

Te amo infinitamente, meu bbzinhoo ! ❤️
</p>
</div>
</div>

<script>

function mostrarSurpresa(){
alert("Eu te amo muito ❤️");
}

const inicio = new Date("2025 - 06 - 28");

function atualizarContador(){

const hoje = new Date();

const diff = hoje - inicio;

const dias = Math.floor(diff/(1000*60*60*24));

document.getElementById("contador").innerHTML =
dias + " dias juntos ❤️";
}

setInterval(atualizarContador,1000);
atualizarContador();

for(let i=0;i<40;i++){

const heart=document.createElement("div");

heart.innerHTML="💖";

heart.classList.add("heart");

heart.style.left=Math.random()*100+"vw";

heart.style.fontSize=(Math.random()*20+10)+"px";

heart.style.animationDuration=(Math.random()*5+5)+"s";

document.body.appendChild(heart);
}
</script>

</body>
</html>
