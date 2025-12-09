# 💻 XYZ/SYSTEM - Landing Page Responsiva com CSS

Este projeto é uma **Landing Page (LP)** desenvolvida para apresentar a empresa fictícia **XYZ/SYSTEM**, que oferece soluções tecnológicas. O layout é **totalmente responsivo**, garantindo uma visualização ideal em diferentes tamanhos de tela (desktop, tablet e mobile) utilizando **Media Queries** em CSS.

---

## ✨ Tecnologias Utilizadas

* **HTML5:** Estrutura semântica da página.
* **CSS3:** Estilização e responsividade do design.
    * Uso de **Flexbox** para layout.
    * Uso de **Variáveis CSS** (`:root`).
    * Uso de **Media Queries** para design responsivo.
* **Google Fonts:** Utilização da fonte 'Catamaran'.
* **Bootstrap 5:** Incluído no `<head>` do `index.html`, embora aparentemente usado de forma limitada ou apenas para recursos básicos de reset/componentes que podem não estar visíveis no CSS fornecido.

---

## 🛠️ Estrutura do Projeto

O projeto está organizado da seguinte forma:
```
LP-CSS-DESIGN-RESPONSIVO-master/
├── assets/
│   ├── imagens/
│   │   ├── img1.jpg          // Imagem de fundo para a seção Hero
│   │   ├── img2.jpg
│   │   ├── img3.jpg
│   │   ├── img4.jpg
│   │   ├── img5.jpg
│   │   └── img6.jpg
│   └── (faltam ícones - web.png, mobile.png, bigdata.png, cloud.png)
├── css/
│   └── style.css           // Arquivo principal de estilos (inclui a lógica de responsividade)
├── pages/
│   └── index.html          // Página principal da Landing Page
└── .gitignore              // Configuração de arquivos ignorados (exclui node_modules/, .vscode/, etc.)
```

**Nota sobre as imagens:** Os ícones (`web.png`, `mobile.png`, `bigdata.png`, `cloud.png`) referenciados em `index.html` não foram incluídos na pasta `assets/imagens/` fornecida, mas o placeholder de imagem de fundo (`img1.jpg`) para a seção `.hero` está presente.

---

## 🎨 Design Responsivo (Media Queries)

O arquivo `css/style.css` utiliza as seguintes Media Queries para adaptar o layout:

| Breakpoint | Regra CSS | Alteração Principal |
| :---: | :--- | :--- |
| **Tablet** | `@media(max-width:1250px)` | Reduz a largura de cada `solution-item` para **48%**, fazendo com que dois itens fiquem lado a lado na seção **Soluções**. |
| **Mobile** | `@media(max-width:900px)` | * Ajusta o **Header** para ser empilhado (coluna) e centralizado, adaptando a navegação. <br> * Define a largura de cada `solution-item` para **90%**, exibindo um item por linha na seção **Soluções**. |

---

## 🚀 Como Executar o Projeto

Para visualizar a Landing Page, siga estes passos:

1.  **Clone ou baixe** este repositório para sua máquina local.
2.  Navegue até a pasta `LP-CSS-DESIGN-RESPONSIVO-master/pages/`.
3.  Abra o arquivo `index.html` em seu navegador web preferido.

---

## 🌟 Estrutura da Página

A página é composta pelas seguintes seções principais:

1.  **Header (`.header`):** Contém o logo (`XYZ/SYS`) e a navegação principal (Home, Clientes, Soluções, Portfolio, Cases, Contato).
2.  **Hero (`.hero`):** Seção de destaque com uma imagem de fundo, título principal e slogans.
3.  **Soluções (`.solutions`):** Exibe as principais ofertas (`Web`, `Mobile`, `Big Data`, `Cloud`) com descrições e botões de "Mais informações".
4.  **Footer (`.footer`):** Contém a nota de direitos autorais.

---
### Desenvolvido por Gabriel Baldini para fins de estudo em Front-end

