# 📚 Projeto Boletim

Olá, pessoal! 👋

Quero aproveitar este README para explicar direitinho o que vocês viram neste projeto. A ideia é que vocês entendam não só o código, mas também o **porquê** de cada parte. Tudo aqui foi pensado para mostrar como o JavaScript, o DOM e a lógica se conectam na prática.

---

## 🎯 **O que estamos aprendendo com este projeto**

Aqui vocês têm um exemplo real de como montar uma interface usando:

* **HTML** para a estrutura
* **CSS** para o visual moderno
* **JavaScript** para criar tudo dinamicamente
* **Módulos ES6** (`import/export`) para organizar melhor o código

Isso já é a base do que um programador utiliza todos os dias.

---

## 🧠 **A lógica por trás do projeto**

O objetivo deste código é mostrar como pegar dados de uma lista de alunos (um array de objetos), montar um card para cada aluno, calcular as médias e ainda adicionar uma interação legal com clique para virar o card.

Cada parte foi organizada de modo que vocês consigam entender a lógica passo a passo.

---

## 🗂️ **Organização dos arquivos**

* **index.html** → estrutura básica da página
* **style.css** → estilos modernos (efeito vidro, background fixo, sombras, animações…)
* **script.js** → onde toda a lógica acontece
* **bancoDados.mjs** → onde deixamos guardados os dados dos alunos

Essa divisão já é uma boa prática profissional.

---

## 🖼️ **Sobre o CSS**

O CSS aqui traz conceitos importantes para vocês:

* `backdrop-filter` para criar o efeito de vidro (glassmorphism)
* `background-attachment: fixed` para o efeito de paralaxe
* `transition` para efeitos suaves
* `box-shadow` e `border-radius` para deixar o design mais profissional

A ideia é mostrar para vocês que CSS, quando bem usado, transforma completamente o visual.

---

## ⚙️ **Sobre o JavaScript**

Aqui está o coração do projeto.

### 🔹 **Importação de módulo**

Mostro como separar dados em outro arquivo e importar para o JS principal:

```js
import { alunos } from "./bancoDados.mjs";
```

Isso deixa o código muito mais organizado.

### 🔹 **Percorrer arrays de objetos**

Vocês aprendem a usar `for...of` para percorrer listas de maneira clara.

### 🔹 **Criar elementos dinamicamente**

Aqui usamos o DOM de verdade, criando cada card via JavaScript:

```js
document.createElement("div")
```

### 🔹 **Montar tabelas e HTML com template strings**

Isso facilita muito quando queremos colocar informações dentro do HTML.

### 🔹 **Calcular a média sem métodos prontos**

A média foi feita na lógica raiz: somando valores e dividindo pelo total. Isso é essencial para entender algoritmo.

### 🔹 **Interatividade: virar o card no clique**

Um dos pontos mais legais!

O card troca completamente o conteúdo e mostra a foto grande quando clicado. Isso mostra para vocês que **o DOM pode ser totalmente reescrito pelo JavaScript**.

---

## 🎓 **Por que esse projeto é tão importante para vocês?**

Porque nele vocês conseguem ver:

* como dados viram interface
* como a lógica cria funcionalidades reais
* como CSS melhora a experiência
* como organizar as partes de um sistema

Isso aqui já é um pedacinho do que vocês vão encontrar no mercado de programação.

---

## 🚀 **O que quero que vocês absorvam**

1. Não tenham medo de escrever código.
2. Aprender programação é um processo — e vocês já estão praticando do jeito certo.
3. Cada função do projeto foi escrita pensando em ensinar lógica.
4. Observem como o JavaScript controla tudo o que aparece na tela.

Esse projeto é para vocês entenderem que dá para criar **coisas grandes** partindo do básico.

---

## 🤝 **Qualquer dúvida, testem, perguntem e experimentem**

A melhor forma de aprender é mexendo, errando, testando e melhorando. Vocês estão no caminho certo!

Vamos em frente! 🚀👨‍🏫
