# 🧵 Ateliê Arte em Costura

Site institucional estático que apresenta o trabalho do Ateliê Arte em Costura: informações sobre o ateliê, catálogo de produtos (bolsas/frasqueiras/kit berço) e contatos.

---

## ✅ Novidades e correções

- A seção **Produtos** em `index.html` recebeu uma correção: havia divs sendo fechadas sem necessidade e a estrutura dos *cards* foi normalizada.
- Observação: algumas imagens têm espaços no nome (ex.: `foto central - aconchego.jpg`). Recomenda-se renomear arquivos para evitar problemas de URL (use `-` ou `_`).

---

## Tecnologias

- HTML5
- CSS3 (Flexbox e CSS Grid)

---

## Estrutura do projeto

```
atelie-arte-em-costura/
├─ assets/                     # imagens e logo
├─ css/
│  ├─ style.css                # estilos da página principal
│  └─ style2.css               # estilos das páginas de catálogo
├─ index.html
├─ bolsas_aconchego.html
├─ bolsas_encanto.html
├─ bolsas_elegancia.html
├─ bolsas_maternidade.html
├─ frasqueiras_termicas.html
├─ README.md
└─ LICENSE
```

---

## Como visualizar localmente 👀

Opções rápidas:

- Abrir `index.html` diretamente no navegador (duplo clique) — suficiente para ver o conteúdo estático.
- Para testar rotas relativas e links com comportamento idêntico a um servidor, rode um servidor local:


## Onde editar (ajustes rápidos) 🔧

- Conteúdo e estrutura dos *cards*: `index.html` (seção `<section id="produtos">`).
- Estilos gerais: `css/style.css`.
- Estilos das páginas de catálogo: `css/style2.css`.
- Imagens: pasta `assets/` (recomenda-se nomes sem espaços).

---

## Boas práticas e observações

- Evite nomes de arquivos com espaços e acentuação — prefira `nome-com-hifen.jpg` ou `nome_com_underscore.jpg`.
- Verifique links relativos e caminhos em `href`/`src` após renomear imagens.
- Teste em mais de um navegador para garantir consistência visual.

---

## Contribuição

Aberto a ajustes simples (corrigir texto, imagens ou estilos). Para mudanças maiores, crie uma branch e abra um *pull request* com uma descrição curta do que foi alterado.

---

## Licença

Consulte o arquivo `LICENSE` para detalhes sobre licenciamento.

---

© Ateliê Arte em Costura — Todos os direitos reservados.