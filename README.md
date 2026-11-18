# Atividade — HTML Semântico

## 1. Proposta

Desenvolva uma página web utilizando HTML semântico, escolhendo um tema de seu interesse ou relacionado à sua realidade.

Você terá liberdade para criar uma solução, apresentar uma ideia, divulgar algo ou organizar informações sobre um assunto que considere interessante.

Algumas possibilidades são:

- Apresentação de um pequeno negócio ou serviço.
- Divulgação de um evento ou iniciativa.
- Página sobre um esporte, hobby ou jogo.
- Organização de informações sobre um curso ou assunto de interesse.
- Apresentação de um projeto pessoal.

Essas são apenas sugestões. Use sua criatividade para definir o que deseja desenvolver!

O projeto será dividido em missões, permitindo que a página evolua gradualmente enquanto você aprende a utilizar os elementos semânticos do HTML.

## 2. Orientações para o desenvolvimento

Antes de iniciar, considere algumas orientações importantes:

### Tecnologias

- Utilize exclusivamente HTML.
- Não utilize arquivos externos de CSS ou JavaScript.
- Caso queira personalizar a aparência, utilize CSS simples, diretamente no HTML, por meio da tag `<style>` ou do atributo `style` (inline).
- A aparência visual não é o foco. Priorize a estrutura e a organização do conteúdo.

### Organização

- Mantenha os arquivos e diretórios organizados.
- Utilize nomes claros para os arquivos.
- Preserve a indentação e o espaçamento adequado do código.
- Evite estruturas desnecessárias ou repetitivas.

### Comentários explicativos

Cada elemento semântico utilizado deverá possuir um comentário HTML imediatamente antes de sua utilização.

O comentário deverá explicar:

1. Qual é a finalidade da tag?
2. Por que ela foi escolhida naquele contexto?
3. Qual benefício sua utilização proporciona?

Escreva as explicações com suas próprias palavras. Não basta apenas utilizar uma tag: é importante compreender sua finalidade.

### Utilização do Git

- O projeto será desenvolvido em etapas, utilizando branches para organizar cada missão.
- Mantenha a branch principal organizada, preservando uma versão estável do projeto.
- Ao concluir uma missão, organize as alterações realizadas e integre o resultado à versão principal antes de iniciar a próxima etapa.
- Considere o histórico de alterações como parte da organização do projeto.

Você terá autonomia para decidir como realizar essas etapas. Caso encontre dificuldades, procure consultar a documentação ou os materiais de estudo disponíveis.

## 3. Missões

### MISSÃO 01 — Estrutura inicial

Defina o tema do seu projeto, seu objetivo e as informações que deseja apresentar.

Comece desenvolvendo a estrutura inicial da página, incluindo:

- Identificação e apresentação do projeto.
- Uma área com links para navegar entre os conteúdos.
- Um espaço para concentrar as informações da página.
- Informações finais, como autoria, contato ou outros dados pertinentes.

Os links de navegação deverão permitir acessar diferentes partes da própria página.

**Elementos esperados:**

`<!DOCTYPE html>`, `<html>`, `<head>`, `<title>`, `<body>`, `<header>`, `<nav>`, `<main>` e `<footer>`.

### MISSÃO 02 — Organização dos conteúdos

Amplie o conteúdo da página, acrescentando informações relacionadas ao tema escolhido.

Procure apresentar diferentes tipos de conteúdo, contemplando:

- Pelo menos dois assuntos ou áreas de informação.
- Um conteúdo que possua título e informações próprias, como uma publicação, atividade, serviço ou apresentação.
- Uma informação adicional que complemente o restante da página.
- Títulos, subtítulos e textos que permitam compreender a organização dos conteúdos.

Utilize também recursos para destacar informações importantes nos textos.

**Elementos esperados:**

`<section>`, `<article>`, `<aside>`, `<h1>`, `<h2>`, `<h3>`, `<p>`, `<strong>` e `<em>`.

### MISSÃO 03 — Apresentação de informações

Acrescente informações que possam ser organizadas e consultadas de maneira estruturada.

Crie uma tabela relacionada ao tema do projeto. Ela deverá apresentar pelo menos três registros, com informações organizadas em colunas e uma linha final contendo algum resumo, total ou informação complementar.

Inclua também informações relacionadas a datas, horários ou formas de contato, conforme a proposta escolhida.

**Elementos esperados:**

`<table>`, `<caption>`, `<thead>`, `<tbody>`, `<tfoot>`, `<tr>`, `<th>`, `<td>`, `<time>` e `<address>`.

### MISSÃO 04 — Conteúdo complementar

Acrescente recursos para complementar as informações da página.

Inclua:

- Pelo menos uma imagem relacionada ao projeto.
- Uma legenda para acompanhar a imagem.
- Uma área com pelo menos duas perguntas e respostas sobre o tema.
- Um destaque para alguma informação importante apresentada na página.

As imagens deverão estar organizadas no diretório `assets/` e apresentar descrições adequadas.

**Elementos esperados:**

`<figure>`, `<figcaption>`, `<img>`, `<details>`, `<summary>` e `<mark>`.

### MISSÃO 05 — Formulários e interação

Acrescente uma possibilidade de interação relacionada à proposta do projeto.

Crie um formulário para coletar informações dos visitantes. A finalidade fica a seu critério, desde que tenha relação com o conteúdo da página.

O formulário deverá conter:

- Pelo menos três campos para preenchimento.
- Identificação de cada campo.
- Uma organização adequada para as informações solicitadas.
- Um botão para envio.

**Elementos esperados:**

`<form>`, `<fieldset>`, `<legend>`, `<label>`, `<input>` e `<button>`.

Não é necessário implementar o processamento dos dados ou utilizar JavaScript.

### MISSÃO 06 — Revisão e finalização

Revise o projeto completo e verifique se todas as etapas foram implementadas corretamente.

Confira:

- Organização e indentação do código.
- Hierarquia dos títulos.
- Utilização adequada dos elementos HTML.
- Funcionamento dos links de navegação.
- Imagens e seus respectivos textos alternativos.
- Organização das informações e dos formulários.
- Presença dos comentários explicativos antes dos elementos semânticos utilizados.

Atualize o `README.md`, incluindo uma breve descrição do projeto e explicações sobre a finalidade dos elementos semânticos utilizados.

Finalize integrando todas as alterações realizadas durante as missões à versão principal do projeto.

## 4. Organização dos arquivos

Mantenha uma estrutura organizada para facilitar a localização dos arquivos.

Uma sugestão:

```text
projeto-html-semantico/
├── index.html
├── README.md
└── assets/
    └── imagens utilizadas no projeto
```

A estrutura poderá ser adaptada conforme a necessidade do projeto.

## 5. Entregáveis

Ao finalizar, o projeto deverá conter:

- **`index.html`:** página completa, funcional e desenvolvida com HTML semântico.
- **`README.md`:** descrição do projeto e explicações sobre os elementos semânticos utilizados.
- **`assets/`:** diretório com as imagens utilizadas.
- **Histórico Git:** registro das etapas de desenvolvimento e integração das missões na branch principal.

## 6. Resultado esperado

Uma página HTML organizada, funcional e construída a partir de uma proposta própria.

O objetivo é compreender como os elementos semânticos ajudam a representar e organizar os conteúdos de uma página, aprendendo a escolher cada elemento de acordo com sua finalidade.

**Lembre-se:** desenvolver não é apenas fazer funcionar. Também é importante compreender suas escolhas, organizar o código e construir soluções com significado!
