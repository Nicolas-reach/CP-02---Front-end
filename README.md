## A Vinheria
A Vinheria Agnello é uma empresa familiar, com mais de **15 anos de história**, administrada por Giulio e Bianca.  
Atende tanto especialistas em vinhos quanto iniciantes, oferecendo atendimento personalizado e curadoria de produtos.

---

## Objetivos
- Desenvolver um **site moderno e funcional**, com foco na experiência do usuário.  
- Reforçar a **identidade visual elegante e acolhedora** da marca.  
- Facilitar a **navegação e o contato** com os clientes.  
- Criar um ambiente digital que mantenha a **tradição e sofisticação** da vinheria.

---

## Estrutura do Projeto

O site é composto pelas seguintes páginas:

- **`index.html`** – Página inicial com destaque para os vinhos e identidade da marca.  
- **`produtos.html`** – Catálogo de produtos, com imagens, descrições e valores.  
- **`sobre.html`** – História e tradição da Vinheria Agnello.  
- **`contato.html`** – Página com formulário de contato e redes sociais.  
- **`assets/imgs`** – Pasta com imagens e ícones utilizados no site.  
- **`style.css`** – Folha de estilo principal.
- **`equipe.css`** - Arquivo de estilo para a pagina da equipe. 
- **`efeitos.css`** – Arquivo de efeitos visuais, transições e animações.  

---

##  Integrantes do Projeto
- **Nicolas Forcione de Oliveira e Souza** – RM566998  
- **Alexandre Constantino Furtado Junior** – RM567188  
- **Enrico Dellatorre da Fonseca** – RM566824  
- **Leonardo Batista de Souza** – RM568558  
- **Matheus Freitas dos Santos** – RM567337  

---

##  Link para o site publicado
Acesse o projeto online no GitHub Pages:  
👉 [Vinheria Agnello - GitHub Pages](https://nicolas-reach.github.io/CP-02---Front-end/)

---

## Efeitos Visuais (CSS Avançado)

O projeto utiliza **recursos avançados de CSS** para aprimorar a experiência visual e interativa do usuário, com foco na **elegância e fluidez** da navegação.

### Pseudo-classes utilizadas:
- `:hover` — muda a cor de botões e menus quando o usuário passa o mouse.  
- `:focus` — destaca campos de formulário selecionados.  
- `:valid` e `:invalid` — validam automaticamente o campo de e-mail.  
- `:required` — aplica destaque a campos obrigatórios.  
- `:active` — altera a cor de botões clicados.  
- `:nth-child(3)` — destaca a página atual no menu de navegação.  

### Pseudo-elementos aplicados:
- `::before` — adiciona um **ícone 🍷** antes dos títulos `<h2>`.  
- `::after` — cria uma **linha decorativa** sob os títulos principais.  
- `::selection` — muda a cor do texto selecionado pelo usuário.

### Animações e Transições:
- **`@keyframes aparecer`** — animação suave aplicada aos títulos `<h2>`, que surgem de forma elegante com leve transição vertical.  
- **Transições (`transition`)** — usadas em imagens, botões e campos interativos para suavizar efeitos de `hover` e `focus`.  
- **Transformações (`transform`)** — aplicadas com `scale()` para criar efeitos de zoom e destaque visual.

### Arquivo de Efeitos:
Todos os efeitos visuais estão organizados no arquivo:  
📁 **`efeitos.css`**, que é importado no HTML principal através da tag:  
```html
<link rel="stylesheet" href="efeitos.css">
