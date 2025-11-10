# 🌿 Viva Bem | Saúde Preventiva e Autocuidado

![Badge: Status Concluído](https://img.shields.io/badge/Status-Concluído-3cb371?style=for-the-badge)
![Badge: Feito com HTML5 e CSS3](https://img.shields.io/badge/Tecnologia-HTML5%20%26%20CSS3-E34F26?style=for-the-badge&logo=html5)
![Badge: Layout Responsivo](https://img.shields.io/badge/Layout-Responsivo-1e90ff?style=for-the-badge)

## 🎯 Sobre o Projeto

O projeto **Viva Bem** é uma página moderna e informativa focada em conscientizar sobre a importância da saúde preventiva e dos exames de rotina essenciais para homens e mulheres.

Este projeto foi desenvolvido como um desafio de front-end com foco rigoroso em técnicas de layout e boas práticas de CSS, garantindo uma interface clara, acolhedora e responsiva.

## 🌟 Desafio e Regras

O principal objetivo deste projeto era construir uma interface completa, elegante e, acima de tudo, **totalmente responsiva** utilizando apenas uma técnica de layout: **Flexbox**.

### Regras Mandatórias (Self-Challenge):

1.  **Layout Apenas com Flexbox:** Todas as seções (Header, Banner, Cards, Dicas e Footer) foram estruturadas exclusivamente com `display: flex`.
2.  **Sem Propriedade `position`:** Não foi permitido o uso de `position: absolute`, `relative`, etc.
3.  **Sem Frameworks/Grid:** Não foi permitido o uso de frameworks (Bootstrap, Tailwind) ou CSS Grid.
4.  **Boas Práticas de CSS:** Uso de **CSS Variables** (`:root`) para gestão de cores e espaçamentos, tipografia moderna e organização modular de estilos.

## 📁 Estrutura do Projeto

A estrutura de arquivos do projeto reflete a organização de desenvolvimento com pré-processadores:
```
VIVA-BEM/ 
├── img/ 
├── index.html
├── style.css 
├── style.css.map
└── style.scss
```

| Arquivo/Pasta | Descrição |
| :--- | :--- |
| `index.html` | Contém toda a marcação HTML da página. |
| `style.scss` | Arquivo fonte do estilo utilizando SCSS, permitindo variáveis e aninhamento. |
| `style.css` | Arquivo CSS compilado e final que o navegador utiliza. |
| `style.css.map`| Mapa de origem do SCSS (para debug). |
| `img/` | Pasta para armazenar quaisquer ativos de imagem. |

## ✨ Funcionalidades e Destaques

* **Header Responsivo:** Navegação que se ajusta de forma fluida.
* **Banner Informativo (Hero):** Mensagem de impacto centralizada verticalmente (`flex-direction: column`).
* **Cards de Prevenção:** Seções separadas para saúde **Masculina (Azul)** e **Feminina (Rosa)**. Eles são dispostos lado a lado em telas maiores, quebrando para coluna no mobile (`flex-wrap`).
* **Seção Dicas Essenciais:** Layout de colunas no desktop que se ajustam automaticamente, empilhando as dicas em telas menores (graças ao `flex-wrap` e `flex-basis`).
* **Rodapé Organizado:** Usa Flexbox para alternar entre uma disposição em coluna (mobile) e em linha (desktop).

## 💻 Tecnologias Utilizadas

| Tecnologia | Descrição |
| :--- | :--- |
| **HTML5** | Estrutura semântica do conteúdo. |
| **SCSS / CSS3** | Estilização avançada, com uso de variáveis, funções e media queries para responsividade. |
| **Flexbox** | Exclusivamente utilizado para todo o layout, alinhamento e organização responsiva. |

## 🚀 Como Rodar o Projeto

Este é um projeto estático e não requer instalação de pacotes ou dependências.

1.  Clone o repositório:
    ```bash
    git clone [https://github.com/Wbernard98/Vivabem_VainaWeb.git]
    ```
2.  Navegue até a pasta do projeto.
3.  Abra o arquivo `index.html` diretamente no seu navegador de preferência.

## 🤝 Contribuição

Sinta-se à vontade para sugerir melhorias.

1.  Faça um Fork do projeto.
2.  Crie uma branch para sua feature (`git checkout -b feature/nome-da-feature`).
3.  Comite suas mudanças (`git commit -m 'feat: Adiciona seção de...'`).
4.  Faça o Push para a branch (`git push origin feature/nome-da-feature`).
5.  Abra um Pull Request.

---
Desenvolvido com carinho e foco em saúde e código limpo!
