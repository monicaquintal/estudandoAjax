<div align="center">
<a href="https://github.com/monicaquintal" target="_blank"><img align="right" width="120px" src="https://res.cloudinary.com/practicaldev/image/fetch/s--eY5Y_t8t--/c_imagga_scale,f_auto,fl_progressive,h_420,q_auto,w_1000/https://cdn.artandlogic.com/wp-content/uploads/2000px-AJAX_logo_by_gengns.svg_.png" /></a>
<h1>Ajax</h1>
<p>Seção 14 do Curso Desenvolvimento Web Completo 2022.</p>
</div>

<div align="center">
<h2>Aula 05: Requisições assíncronas parte 1 - Efetuando requisições HTTP via XMLHttpRequest.</h2>
</div>

## XMLHttpRequest

-  objeto nativo dos navegadores modernos, acessado através da linguagem de programação Javascript.
- no modelo de requisições assíncronas, há mudança na estrutura do projeto: ao invés de navegar entre páginas distintas, teremos apenas uma única página, responsável por requisitar apenas o conteúdo dinâmico de outras páginas.
  - o browser não fará mais um refresh a cada solicitação de dados!
  - serão solicitados dados ao servidor internamente pela própria página!
  - a própria aplicação gerenciará o processo de requisição e resposta, se mantendo disponível para o usuário realizar novas tarefas, mesmo que haja requisições em curso.

## Praticando

- trabalhar com arquivos [pagina_1_conteudo](../pages/pagina_1_conteudo.html), [pagina_2_conteudo](../pages/pagina_2_conteudo.html) e [pagina_3_conteudo](../pages/pagina_3_conteudo.html).
  - não são as páginas em si, apenas seus conteúdos!

- criado o arquivo [requisicoes_assincronas](../pages/requisicoes_assincronas.html).
  - ctrl c + ctrl v no conteúdo da pagina_1.
  - excluidos os conteúdos do container (conteúdo principal) e atributo href das tags a, e alterado title.

- criar o objeto XMLHttpRequest:
  - no head, criar a tag script.

~~~javascript
function requisitarPagina(url) {
  let ajax = new XMLHttpRequest();
  ajax.open('GET', url);
  ajax.send();

  console.log(ajax);
}
~~~

- em cada uma das tags a, adicionar o evento onclick:

~~~html
<a href="#" class="btn btn-primary" onclick="requisitarPagina('pagina_1_conteudo.html')">Página 1</a>
<a href="#" class="btn btn-primary" onclick="requisitarPagina('pagina_2_conteudo.html')">Página 2</a>
<a href="#" class="btn btn-primary" onclick="requisitarPagina('pagina_3_conteudo.html')">Página 3</a>
~~~

---

[Voltar ao início.](https://github.com/monicaquintal/estudandoAjax)