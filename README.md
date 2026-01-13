# 📐 Boas Práticas CSS - Arquitetura & Organização

![Status](https://img.shields.io/badge/Status-Finalizado-green)
![CSS3](https://img.shields.io/badge/Style-CSS3_Architecture-1572B6?logo=css3&logoColor=white)
![HTML5](https://img.shields.io/badge/Code-HTML5-orange?logo=html5&logoColor=white)
![Clean Code](https://img.shields.io/badge/Focus-Clean_Code-success)

> Um projeto demonstrativo focado na qualidade do código, aplicando metodologias de organização para garantir que o CSS seja legível, reutilizável e escalável.

## 🎯 Motivação e Propósito

No desenvolvimento de software, escrever o código é apenas metade do trabalho; a outra metade é mantê-lo. O propósito deste repositório não é apenas criar um layout visual, mas sim aplicar **Boas Práticas de Engenharia de CSS**.

Este projeto resolve problemas comuns como:
* **Conflitos de Especificidade:** Evitando o uso excessivo de IDs ou `!important`.
* **Código Duplicado:** Criando classes reutilizáveis.
* **Dificuldade de Leitura:** Usando nomes de classes semânticos que descrevem a função do elemento (ex: `.produto-botao` ao invés de `.btn-azul`).

## 🛠️ Tecnologias Utilizadas

A stack é minimalista, focando na pureza da implementação:

* **[HTML5](https://developer.mozilla.org/pt-BR/docs/Web/HTML):** Estrutura semântica rigorosa (uso de `<article>`, `<section>`, `<aside>`).
* **[CSS3](https://developer.mozilla.org/pt-BR/docs/Web/CSS):** Estilização com foco em arquitetura.
    * **Metodologia:** Organização lógica de seletores.
    * **Layout:** Uso moderno de Flexbox e/ou Grid para posicionamento.
    * **Reset/Normalize:** Padronização de estilos entre navegadores.

## ✨ Funcionalidades

O projeto implementa uma interface (geralmente uma vitrine de loja ou layout de produto) demonstrando:

1.  **Separação de Responsabilidades:** HTML cuida da estrutura, CSS cuida da aparência.
2.  **Modularidade:** Componentes (como botões e cards) que podem ser movidos para qualquer lugar da página sem quebrar o estilo.
3.  **Responsividade:** Layout fluido que se adapta a diferentes larguras de tela.

## 📦 Instalação e Execução

Este é um projeto estático ("Client-Side"), o que facilita a execução e análise.

### Pré-requisitos
* Qualquer navegador web moderno (Chrome, Firefox, Edge).

### Passo a Passo

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/DouglassenG/boas_praticas_css.git](https://github.com/DouglassenG/boas_praticas_css.git)
    ```

2.  **Acesse o diretório:**
    ```bash
    cd boas_praticas_css
    ```

3.  **Visualização:**
    * Localize o arquivo `index.html`.
    * Abra-o diretamente no navegador.

## 💻 Estrutura do Código

A organização dos arquivos reflete a preocupação com a manutenção:

```text
boas_praticas_css/
├── index.html       # Markup semântico
├── main.css         # Estilos (pode estar dividido em pastas em projetos maiores)
├── images/          # Ativos otimizados
└── README.md        # Documentação
