# pipe-actions-mackenzie
Pipeline CI/CD automatizada Git Actions
---

# 📘 Pipeline de CI/CD com GitHub Actions

### *Atividade – Universidade Presbiteriana Mackenzie*

**Aluno:** Higor Rodrigues – *10424019*

Este projeto demonstra a criação de uma pipeline completa de **CI/CD utilizando GitHub Actions**, incluindo validação de HTML, deploy automático e publicação via GitHub Pages.

A aplicação consiste em uma página HTML simples, validada e publicada automaticamente a cada push na branch principal.

---

## 📁 Estrutura do Projeto

```
.
├── .github/
│   └── workflows/
│       ├── ci-validacao.yml
│       └── ddeploy.yml
└── index.html
```

### 📄 `index.html`

Arquivo HTML principal do projeto:


---

## ⚙️ Workflows do GitHub Actions

O projeto possui **três pipelines** principais, cada uma com uma responsabilidade distinta.

---

### 🧪 1. `ci-validacao.yml` — *Validação do HTML*

Pipeline responsável por:

* Validar o HTML usando ferramentas de lint/validação.
* Garantir que o código siga padrões corretos antes do deploy.
* Rodar automaticamente em todo `push` ou `pull request`.

---

### 🚀 2. `deploy.yml` — *Deploy Contínuo*

Responsável por:

* Executar build (se houver).
* Publicar artefatos ou arquivos necessários do projeto.
* Preparar o conteúdo para publicação.

Ideal para cenários em que existe etapa de build ou empacotamento.

---

## 🛠️ Como funciona o fluxo completo

1. **Push ou PR enviado para o repositório**
   ⮕ aciona a pipeline de *validação*.

2. **Validação concluída com sucesso**
   ⮕ pipeline de *deploy* é executada.

3. **Deploy realizado**
   ⮕ conteúdo é enviado para a pipeline de *GitHub Pages*.

4. **Publicação automática**
   ⮕ página fica disponível online.

---

## 🌍 Acesso ao Projeto

Assim que o `pages build and deployment` finalizar, o projeto poderá ser visualizado por meio da URL gerada pelo GitHub Pages:

```
https://higorroliver.github.io/pipe-actions-mackenzie/

```

---

## 🧩 Tecnologias Utilizadas

* **GitHub Actions**
* **HTML5**
* **Validador de HTML**
* **GitHub Pages**

---

## 📌 Objetivo da Atividade

* Demonstrar conhecimento em automações com GitHub Actions.
* Validar HTML automaticamente.
* Implementar fluxo de CI/CD.
* Publicar página estática com GitHub Pages.

---

## 📄 Autor

**Higor Rodrigues – 10424019**
---
