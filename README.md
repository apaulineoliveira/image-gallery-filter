  <p>Visualização do Projeto: https://image-gallery-filter-vanilla-js.netlify.app/</p>
  <h3>Sobre o projeto</h3>
  <p>O intuito deste projeto foi criar um filtro de galeria de e-commerce em que cada seção contivesse os produtos de seu respectivo setor. As ferramentas utilizadas foram: html5, css3 e javascript (puro). Se tratando da solução em javascript, utilizei maioritariamente o DOM (Document Object Model) para realizar as interações com o html e css, sobretudo, utilizando o <code>querySelector()</code>. Com o manuseio do <code>querySelector()</code> foi possível "pegar" os seletores de estilo css e atribuí-los a comandos de interatividade com o javascript. Como pode ser visualizado no código abaixo:</p>


````filterContainer.querySelector(".active").classList.remove("active");````

<br>

<p>Além disso, foi utilizado o método <code>forEach()</code> para percorrer o array e passar uma função de <b>callback</b> para cada elemento da mesma, juntamente ao valor atual (item), e logo em seguida, passada uma estrutura condicional <code>if/else</code>.</p> <br>




