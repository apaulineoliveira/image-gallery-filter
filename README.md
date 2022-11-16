# image-gallery-filter
Filtro de seção de e-commerce | Feito em Javascript.
# 🚩Objetivo
<p>O intuito deste projeto foi criar um filtro de galeria de um e-commerce em que cada seção contivesse os produtos de cada setor.</p>
<p>O projeto foi fundamentado utilizando HTML5, CSS3 e Javascript (puro).</p></h3>
<ul>
<li>Se tratando da solução em Javascript utilizei maioritariamente DOM (Document Object Model) para fazer as interações com o HTML e CSS, sobretudo, utilizando <code>querySelector()</code>.</li>
<li>Com a utilização do <code>querySelector()</code> foi possível "pegar" os seletores de estilo CSS e atribuí-los a comandos de interatividade com javascript. Como podem ser evidenciados nos códigos:<br></br>
  <code>const filterContainer = document.querySelector(".gallery-filter")</code> <br></br>
  <code>filterContainer.querySelector(".active").classList.remove("active");</code><br></br></li>
<li>Foi utilizado o método <code>forEach()</code> para percorrer o array e passar uma função de callback para cada elemento da mesma, juntamente ao valor atual (item) e logo em seguida, passada uma estrutura condicional <code>if/else</code>.</li>
</ul>
