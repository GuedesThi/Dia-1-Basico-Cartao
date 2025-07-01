### Se lembre

---

- Não precisa usar `background-image` para ter acesso a funcionalidade `background-size: cover`. Basta usar um `<img>` comum (dessa forma não perdemos **SEO**), e estilizá-lo com o comando:
  ```css
  img {
    object-fit: cover;
  }
  ```
- Use `<article>` para blocos completos de uma informação (ex: um comentário, uma postagem, um card de um produto numa lista). E, `<section>` para blocos que sozinhos não são completos, e que precisem de um título (ex: bloco onde ficará todo o conteúdo do nosso blog)
