<div align="center">
<a href="https://github.com/monicaquintal" target="_blank"><img align="right" width="120px" src="https://res.cloudinary.com/practicaldev/image/fetch/s--eY5Y_t8t--/c_imagga_scale,f_auto,fl_progressive,h_420,q_auto,w_1000/https://cdn.artandlogic.com/wp-content/uploads/2000px-AJAX_logo_by_gengns.svg_.png" /></a>
<h1>Ajax</h1>
<p>Seção 14 do Curso Desenvolvimento Web Completo 2022.</p>
</div>

<div align="center">
<h2>Aula 04: Requisições síncronas.</h2>
</div>

Para exemplificar as requisições síncronas:

- conversão do arquivo pagina_1.html em pagina_1.php.
- inserido um laço for, com o intuito de causar uma lentidão no processamento da página, e a resposta demora alguns segundos para ser recebida.

~~~php
for ($i = 0; $i > 100000000; $i++) {
  //
}
~~~

> Acompanhar o andamento da requisição em DevTools &gt; Nerwork, até que o status seja 200 (concluído).

---

[Voltar ao início.](https://github.com/monicaquintal/estudandoAjax)