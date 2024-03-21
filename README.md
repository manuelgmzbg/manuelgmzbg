<!DOCTYPE html>
<html>
<head>
 <title>Message and Flowers</title>
 <style>
 body {
 background-color: #FFA07A;
 font-size: 24px;
 }
 #message {
 display: block;
 }
 #flowers {
 display: none;
 }
 </style>
</head>
<body>
 <div id="message">
 <p>Ya que entraste aquí quiero que sepas que eres lo más importante para mí y que siempre voy a querer que estés bien, mereces todo lo bonito que hay en la vida, mereces ser feliz, te amo mi pequeña y eres una mujer maravillosa, me haces feliz, y siempre nos encontraremos en cada vida que pase.</p>
 <button onclick="showFlowers()">Pulsa aquí</button>
 </div>
 <div id="flowers" style="display:none;">
 <img src="https://img.freepik.com/vector-premium/dibujo-ramo-rosas-amarillas_564737-1587.jpg" alt="Yellow Flowers">
 <p>No se me olvidan nunca tus flores, tal vez no es como se espera pero siempre las tendrás, te amo</p>
 </div>
 <script>
 function showFlowers() {
 document.getElementById('message').style.display = 'none';
 document.getElementById('flowers').style.display = 'block';
 }
 </script>
</body>
</html>
