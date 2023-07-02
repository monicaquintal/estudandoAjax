<div align="center">
<a href="https://github.com/monicaquintal" target="_blank"><img align="right" width="120px" src="https://res.cloudinary.com/practicaldev/image/fetch/s--eY5Y_t8t--/c_imagga_scale,f_auto,fl_progressive,h_420,q_auto,w_1000/https://cdn.artandlogic.com/wp-content/uploads/2000px-AJAX_logo_by_gengns.svg_.png" /></a>
<h1>Ajax</h1>
<p>Seção 14 do Curso Desenvolvimento Web Completo 2022.</p>
</div>

<div align="center">
<h2>Aula 01: Introdução ao Ajax.</h2>
</div>

- acrônimo de Asynchronous JavaScript And XML.
- metodologia/técnica de programação que utiliza JS, e possibilita a comunicação assíncrona entre front-end e back-end de aplicações web.
  - essa comunicação assíncrona era prioritariamente feita através da troca de dados no formato XML.
  - atualmente, o formato de dados mais utilizado para comunicação entre front e back-end de aplicações web é o JSON (notação ainda mais enxuta/levem e suportado ativamente pelo JS e outras linguagens, facilitando o parse de objetos para JSON e vice-versa.)
- inicialmente disponibilizada na versão 4.0 do Internet Explorer.
- potencializou a criação do conceito de web 2.0.
  - atualmente, há muitos frameworks JS, como Angular, React e Vue, que implementam o conceito de single page applications.

## Revendo conceito de aplicação web:

### 1. modelo tradicional: 
- cliente &gt; Internet &gt; servidor. 
- durante esse modelo de requisição, o browser fica travado aguardando a resposta do servidor.

### 2. processamento assíncrono/metodologia AJAX: 
- a própria aplicação, através da captura de um evento no front-end, realiza uma requisição ao servidor, através do objeto XMLHTTP Request, que gerencia o processo de envio da requisição e captura da resposta.
- aplicação web não fica travada, o usuário pode continuar utilizando a aplicação enquanto a resposta não retorna.

---

[Voltar ao início.](./readme.md)