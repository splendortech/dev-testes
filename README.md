# 🧪 Desafio Técnico – Desenvolvedor(a) Full Stack PHP/WordPress

Olá! Obrigado por chegar até aqui.

Queremos conhecer melhor sua capacidade técnica com **PHP moderno**, **WordPress**, **hooks/filtros/shortcodes**, **integração com APIs**, uso de **Vue.js** e atenção a detalhes no **front-end responsivo**.

> ⚠️ Este é um teste simulado. Ele **não será usado em produção** e tem como único objetivo avaliar seu domínio técnico, clareza de raciocínio e organização de código.

---

## ✅ Parte 1 – Recriação de layout no WordPress (Hello Elementor + Tema Filho)

### 🎯 Objetivo

Reproduzir o seguinte layout (Landing page) utilizando WordPress com **tema Hello Elementor + tema filho oficial** e **Elementor (livre)**:

🔗 [Figma – Positivus Landing Page](https://www.figma.com/design/044YZ9Nh2LITD4OtzTNYja/Positivus-Landing-Page-Design--Community-?t=btGYEgQJ3URdWUEh-0)

### 🛠 Requisitos

- Usar Hello Elementor com o tema filho oficial
- Fidelidade visual ao Figma: tipografia, espaçamentos, cores e hierarquia
- Responsividade obrigatória
- Pode usar Elementor Pro ou escrever partes em código (CSS/JS/PHP)
- Entregar em uma URL pública, como:
  - InstaWP, LocalWP (Live Link)
  - Seu servidor
  - Etc

---

### 💡 EXTRA – Validação de código PHP no WordPress

Além do layout visual, crie no tema filho os seguintes recursos programáticos:

- Um **shortcode `[ano-atual]`** que exibe o ano atual
- Um filtro para modificar o **título de posts** adicionando “⭐” ao final
- Um hook `wp_footer` que imprime um comentário HTML ao final da página: `<!-- Renderizado por [seu_nome] -->`

Esses itens devem estar documentados no `functions.php` com comentários claros.

---

### 🔑 Elementor Pro

Caso não tenha licença, pode usar esta versão apenas para o teste:

📦 [Download (somente para teste)](https://drive.google.com/file/d/1wyNaDfLTuK-G2GXsMAbCIF_9kRVDfxol/view?usp=sharing)

---

## 💻 Parte 2 – Front-end: Vue.js + Tailwind

### 🎯 Objetivo

Criar uma pequena SPA com Vue.js 3 e Tailwind exibindo uma lista de produtos, consumindo dados via API PHP.

### 📋 Tarefas

- Criar interface com Vue 3 + Tailwind (com ou sem Vite)
- Exibir lista de produtos (dados da API `/api/produtos`)
- Campo de busca por nome
- Componente reutilizável para card de produto
- Loading e mensagens de erro

Pode usar Axios ou Fetch. Organização de código será avaliada.

---

## ⚙️ Parte 3 – Back-end: API REST em PHP

### 🎯 Objetivo

Criar uma rota `GET /api/produtos` que:

- Retorna JSON com ao menos 5 produtos (`id`, `nome`, `descricao`, `preco`)
- Suporte a filtro por `?search=`

#### 📦 Exemplo de JSON:

```json
[
  {
    "id": 1,
    "nome": "Camiseta Branca",
    "descricao": "100% algodão, unissex",
    "preco": 59.90
  },
  ...
]
```

Pode ser PHP puro (procedural ou OO). Use boas práticas.

---

## 🧩 Parte 4 – Teste com EMPS Framework

### 🎯 Objetivo

Validar sua autonomia técnica e capacidade de seguir documentação/códigos diversos.

### 📋 Tarefas

- Clonar: [https://github.com/AlexGnatko/EMPS6](https://github.com/AlexGnatko/EMPS6)
- Instanciar o framework localmente
- Criar uma página que exiba “Hello World” em uma nova rota
- Subir o projeto no Git
- Readme explicando brevemente como fez

📘 Documentação: [https://emps.ag38.ru](https://emps.ag38.ru)

---

## 🎥 (Opcional mas totalmente válido) Vídeo de Apresentação

Grave um vídeo rápido (máx. 5 min) com:

- Breve apresentação
- Explicação do raciocínio técnico mostrando os testes realizados
- Decisões que tomou
- O que faria diferente

---

## 📩 Como entregar

Preencha o formulário abaixo com os links de entrega:

👉 [Formulário de envio – Dev Full Stack](https://forms.gle/3aiw4cAqVHaZrgNG8)

Inclua:

1. Link da landing page Elementor
2. Link do projeto Vue.js funcional
3. Link da API PHP (repositório)
4. Repositório com a instância do Framework EMPS
5. (Opcional mas válido) Link do vídeo de apresentação (Loom ou vídeo privado no Youtube)

---

**Boa sorte!**  
Estamos animados para conhecer seu trabalho técnico 🚀
