# 📄 Currículo Web Interativo & Compacto — Enzo Gazolla Nagano

Currículo web moderno, responsivo e ultra-compacto para mobile, desenvolvido em **HTML5**, **CSS3 puro** e **JavaScript nativo** (zero dependências pesadas). Criado sob medida para destacar competências em **Desenvolvimento de Software**, **Inteligência Artificial (LLMs & Agentes)** e **Projetos Acadêmicos/Práticos**.

---

## ✨ Destaques & Funcionalidades

- 📱 **Mobile-First & Ultra Compacto**:
  - Ajustado milimetricamente para telas de smartphones, evitando scroll excessivo e aproveitando cada espaço com tipografia proporcional (`clamp` e `rem`).
  - Cards e chips de competências organizados e legíveis com facilidade de toque.
- 🌓 **Tema Claro & Escuro (Dark/Light Mode)**:
  - Alternador dinâmico de tema com persistência automática no `localStorage` do navegador.
  - Paleta escura inspirada em temas para desenvolvedores (*Slate/Navy & Cyan Accents*).
- 🖨️ **Otimizado para PDF & Impressão (`@media print`)**:
  - Botão integrado de impressão/PDF.
  - Oculta botões de navegação, ajusta margens para **padrão A4** e evita quebras de página desagradáveis no meio dos cards (`break-inside: avoid`).
- ⚡ **Alta Performance & Acessibilidade**:
  - Sem frameworks pesados; carrega instantaneamente.
  - Links diretos com ícones SVG inline para **WhatsApp/Telefone**, **E-mail**, **LinkedIn** e **GitHub**.
  - Tags semânticas do HTML5 (`<header>`, `<main>`, `<section>`, `<article>`, `<footer>`).

---

## 📁 Estrutura de Arquivos

```plaintext
Currículo/
├── index.html        # Estrutura semântica e dados do currículo
├── style.css         # Design system com variáveis CSS, responsividade e regras de impressão
└── README.md         # Documentação e instruções de uso
```

---

## 🚀 Como Visualizar Localmente

### Método 1: Direto no Navegador (Mais Rápido)
1. Dê um duplo clique no arquivo `index.html`.
2. O currículo abrirá no seu navegador padrão (Chrome, Edge, Firefox, Brave, etc.).

### Método 2: Com VS Code / Antigravity IDE (Live Server)
1. Com o projeto aberto na IDE, instale a extensão **Live Server** (caso não tenha).
2. Clique com o botão direito no `index.html` e selecione **"Open with Live Server"**.
3. O projeto recarregará automaticamente sempre que você fizer alterações no código.

---

## 🖨️ Como Exportar em PDF com Qualidade Máxima

1. Abra o arquivo no navegador (Google Chrome ou Microsoft Edge recomendados).
2. Clique no botão **"PDF"** no topo da página ou pressione `Ctrl + P` (no Windows).
3. Na janela de impressão:
   - **Destino**: Escolha **"Salvar como PDF"**.
   - **Páginas**: "Tudo" (ou selecione as páginas que desejar).
   - **Layout**: "Retrato".
   - Em **Mais definições**:
     - **Tamanho do papel**: A4.
     - **Margens**: "Padrão" ou "Mínimas".
     - **Gráficos de segundo plano**: Marque esta opção caso queira manter os fundos dos chips e cores de destaque.
4. Clique em **Salvar**.

---

## 🌐 Como Publicar Online Gratuitamente

Você pode colocar seu currículo no ar em minutos com um link próprio para enviar aos recrutadores:

### Opção 1: GitHub Pages (Recomendado)
1. Crie um repositório no seu GitHub (ex.: `curriculo` ou `EnzoGazolla.github.io`).
2. Faça o commit e envie os arquivos (`index.html`, `style.css`, `README.md`):
   ```bash
   git init
   git add .
   git commit -m "feat: curriculo web compacto e responsivo"
   git branch -M main
   git remote add origin https://github.com/EnzoGazolla/SEU-REPOSITORIO.git
   git push -u origin main
   ```
3. No GitHub, acesse: **Settings** > **Pages** > em *Branch*, selecione `main` e a pasta `/ (root)`.
4. Salve. Seu currículo estará online em `https://enzogazolla.github.io/SEU-REPOSITORIO`.

### Opção 2: Vercel ou Netlify (Arrastar e Soltar)
1. Acesse [vercel.com](https://vercel.com) ou [netlify.com](https://netlify.com).
2. Conecte sua conta do GitHub ou simplesmente arraste a pasta do currículo para a interface.
3. Você receberá um domínio gratuito instantaneamente com suporte a HTTPS (ex.: `curriculo-enzo.vercel.app`).

---

## ✏️ Como Personalizar

- **Adicionar Novos Projetos**:
  No arquivo `index.html`, copie qualquer bloco `<article class="project-card">...</article>` dentro da seção de projetos e atualize título, descrição, link e tecnologias (`mini-tag`).
- **Atualizar Contatos e Links**:
  Edite a lista `<ul class="contact-list">` no `<header>` de `index.html`.
- **Customizar Cores**:
  No arquivo `style.css`, altere as variáveis `:root` (tema claro) ou `[data-theme="dark"]` (tema escuro), como `--primary` e `--accent`.

---

Desenvolvido para **Enzo Gazolla Nagano** • Estudante de Ciência da Computação | Dev Software & IA
