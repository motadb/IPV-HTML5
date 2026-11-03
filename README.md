# Manual de HTML5 + CSS3

**Instituto Politécnico de Viseu**  
CTESP · 1.º Ano · Ano letivo 2026/2027  
Autor: David Mota

---

## Descrição

Este repositório contém o material de apoio à unidade curricular de Tecnologias Web, destinado a estudantes do primeiro ano de CTESP do Instituto Politécnico de Viseu.

O manual foi concebido para acompanhar alunos sem conhecimentos prévios de desenvolvimento web, desde os fundamentos da linguagem HTML5 até à construção de páginas com layout avançado em CSS3. Para cada capítulo teórico existe uma ficha de exercícios com enunciado, esqueleto de arranque e solução comentada.

---

## Estrutura do Repositório

```
IPV-HTML5/
├── index.html                     # Página de entrada — índice geral
├── css/
│   └── manual.css                 # Folha de estilos partilhada pelo manual
│
├── 01-introducao/
│   ├── teoria.html
│   └── exercicio/
│       ├── enunciado.html
│       ├── esqueleto.html
│       └── solucao.html
├── 02-semantica/
├── 03-texto-ligacoes/
├── 04-imagens-caminhos/
├── 05-css-fundamentos/
├── 06-css-box-model/
├── 07-css-flexbox/
├── 08-css-grid/
└── 09-formularios/
```

Cada pasta de capítulo segue a mesma organização: um ficheiro de teoria e uma pasta `exercicio/` com três ficheiros — enunciado, esqueleto e solução.

---

## Conteúdos

| Capítulo | Título | Tópicos principais |
|---|---|---|
| 01 | Introdução ao HTML5 | DOCTYPE, estrutura base, elementos de texto, atributos |
| 02 | Estrutura Semântica | `header`, `nav`, `main`, `article`, `section`, `aside`, `footer` |
| 03 | Texto e Ligações | Formatação, listas, hiperligações, caminhos relativos e absolutos |
| 04 | Imagens e Caminhos | `img`, atributo `alt`, `figure`, `figcaption`, organização de ficheiros |
| 05 | CSS — Fundamentos | Seletores, especificidade, cascata, cores, tipografia, unidades |
| 06 | CSS — Box Model | `margin`, `padding`, `border`, `display`, `position`, `overflow` |
| 07 | CSS — Flexbox | Contentor e itens, `justify-content`, `align-items`, `flex-wrap` |
| 08 | CSS — Grid | `grid-template-areas`, unidade `fr`, `auto-fill`, layout responsivo |
| 09 | Formulários HTML5 | Tipos de `input`, `label`, validação nativa, `fieldset`, `button` |

---

## Como Utilizar

### Pré-requisitos

- Editor de código — recomenda-se o [Visual Studio Code](https://code.visualstudio.com/) com a extensão **Live Server**
- Browser atualizado — Google Chrome ou Mozilla Firefox

### Instruções

1. Clonar o repositório:

   ```bash
   git clone https://github.com/motadb/IPV-HTML5.git
   ```

2. Abrir o ficheiro `index.html` no browser (duplo clique ou arrastar para o browser).

3. Seguir os capítulos pela ordem apresentada. Para cada capítulo:
   - Ler a **teoria** e experimentar os exemplos no editor;
   - Tentar resolver a **ficha de exercícios** sem consultar a solução;
   - Verificar a solução apenas após concluir a tentativa.

> Não são necessários servidor web, base de dados ou qualquer instalação adicional. Os ficheiros HTML funcionam diretamente no browser a partir do sistema de ficheiros local.

---

## Metodologia Pedagógica

O manual segue uma progressão gradual, em que cada capítulo assenta nos conhecimentos adquiridos nos anteriores. A componente prática é central: cada ficha de exercícios define objetivos mensuráveis, apresenta um esqueleto de código anotado com instruções (`TODO`) e inclui uma solução de referência totalmente funcional.

As fichas a partir do capítulo 05 são acumulativas — o aluno estiliza e expande páginas criadas em fichas anteriores, simulando o processo real de desenvolvimento web.

---

## Tecnologias

- HTML5
- CSS3 (Flexbox, Grid, Custom Properties)

Não são utilizadas bibliotecas externas, *frameworks* nem JavaScript. Todo o material é compatível com os browsers modernos atuais.

---

## Licença

Material de uso académico interno. Todos os direitos reservados ao Instituto Politécnico de Viseu.
