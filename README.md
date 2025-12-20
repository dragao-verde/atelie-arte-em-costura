# 🧵 Ateliê Arte em Costura

Site institucional estático que apresenta o trabalho do Ateliê Arte em Costura: informações sobre o ateliê, catálogo de produtos (bolsas) e contatos.

---

## Tecnologias

- HTML5
- CSS3 (incluindo Flexbox e CSS Grid)

---

## Estrutura do projeto

```
atelie-arte-em-costura/
├─ assets/                # imagens e logo
├─ css/
│  ├─ style.css           # estilos da página principal
│  └─ style2.css          # estilos das páginas de catálogo
├─ index.html
├─ bolsas_aconchego.html
├─ bolsas_encanto.html
└─ README.md
```

---

## Como visualizar localmente

1. Clone ou baixe o repositório

```bash
git clone https://github.com/seu-usuario/atelie-arte-em-costura.git
```

2. Abra a pasta do projeto e abra `index.html` em seu navegador (duplo clique ou arraste para a janela do navegador).

Observação: o site é estático — não precisa de servidor ou instalação de dependências.

---

## Notas sobre o layout e estilos

- A paleta de cores utiliza tons suaves de rosa e pêssego.
- A seção `Produtos` usa um grid para exibir imagens em cards; as páginas de catálogo (`bolsas_aconchego.html`, `bolsas_encanto.html`) usam `css/style2.css`.
- A seção `Contato` possui botões estilizados (Instagram e WhatsApp). O mesmo estilo foi aplicado ao link de retorno nas páginas de catálogo (classe `.bt-voltar`).

---

## Edição rápida

- Para ajustar espaçamentos, cores ou tamanhos, edite `css/style.css` e `css/style2.css`.
- Para atualizar imagens, substitua/adicione arquivos na pasta `assets/` e atualize o `src` nas páginas HTML.

---

## Melhorias sugeridas

- Adicionar formulário de contato funcional
- Incluir modais para ampliar imagens
- Adicionar metadados e otimização para SEO

---

## Licença

Consulte o arquivo `LICENSE` para informação sobre licenciamento (se presente).

---

© Ateliê Arte em Costura — Todos os direitos reservados.