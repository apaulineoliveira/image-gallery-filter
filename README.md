<img src="https://cdn.pixabay.com/photo/2015/04/23/17/41/javascript-736400_960_720.png" height="50" width="50"/>
<h1 align="center">Objetivo</h1>
<p>O intuito deste projeto foi criar um filtro de galeria de um e-commerce em que cada seção contivesse os produtos de cada setor.</p>
<p>O projeto foi fundamentado utilizando HTML5, CSS3 e Javascript (puro).</p></h3>

<ul>
<li>Se tratando da solução em Javascript utilizei maioritariamente DOM (Document Object Model) para fazer as interações com o HTML e CSS, sobretudo, utilizando <code>querySelector()</code>.</li>
<li>Com a utilização do <code>querySelector()</code> foi possível "pegar" os seletores de estilo CSS e atribuí-los a comandos de interatividade com javascript. Como podem ser evidenciados nos códigos:<br></br>
  <code>const filterContainer = document.querySelector(".gallery-filter")</code> <br></br>
  <code>filterContainer.querySelector(".active").classList.remove("active");</code><br></br></li>
<li>Foi utilizado o método <code>forEach()</code> para percorrer o array e passar uma função de callback para cada elemento da mesma, juntamente ao valor atual (item) e logo em seguida, passada uma estrutura condicional <code>if/else</code>.</li>
</ul>
<br></br>
<br></br>


<h1>Goal</h1>
<p>The target of this project was to create an e-commerce gallery filter in which each section contained products from each sector.</p>
<p>The project was based using HTML5, CSS3 and Javascript (pure).</p>

<ul>
<li>When it comes to the solution in Javascript, I mostly used DOM (Document Object Model) to make interactions with HTML and CSS, especially using <code>querySelector()</code>.</li>
<li>By using <code>querySelector()</code> it was possible to "take" CSS style selectors and assign them to interactivity commands with javascript. As can be evidenced in the codes:<br></br>
   <code>const filterContainer = document.querySelector(".gallery-filter")</code> <br></br>
<code>filterContainer.querySelector(".active").classList.remove("active");</code><br></br></li>
<li>The <code>forEach()</code> method was used to traverse the array and pass a callback function for each element of the same, together with the current value (item) and soon after, passing a conditional structure <code>if/else</code>.</li>
</ul>   
