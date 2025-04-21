# Projeto de Desenvolvimento Web - Cadastro de Currículos

## 🎓 FMU - Faculdades Metropolitanas Unidas  
**Curso:** Engenharia da Computação  
**Disciplina:** Desenvolvimento Web  
**Fase:** 1 (Front-End) 

**Grupo:**   
- Nome: Caio Marques de Souza - RA: 1303757
- Nome: Flávia Aragão Lopes - RA: 2163501
- Nome: João Vitor Piola - RA: 2472597
- Nome: Matheus Ribeiro - RA: 1648262
- Nome: Victor Hiromi Maisaka - RA: 2322323

---

## 📌 Descrição do Projeto
Este projeto tem como objetivo desenvolver um formulário de **Cadastro de Currículos** utilizando **HTML, CSS, JavaScript e jQuery**, atendendo aos requisitos funcionais e não funcionais descritos abaixo. O projeto está dividido em duas fases: a primeira contempla a parte **frontend**, e a segunda (futura) contemplará o **backend**.

---

## 📂 Estrutura de Pastas

Cadastro de Currículos/
│
├── CSS/                → Folhas de estilo (arquivos .css)  
├── JS/                 → Scripts JavaScript/jQuery (arquivos .js)  
├── Imagens/            → Arquivos de imagem (.jpg, .jpeg, .png, .gif)  
├── Resources/          → Arquivos de mídia (áudio/vídeo)  
├── index.html          → Página principal do formulário  
├── README.md           → Este documento de requisitos e orientações

---

## 📄 Documento de Requisitos e Negócios

### ✅ Levantamento de Requisitos

#### Funcionais
- O formulário deve permitir o cadastro de dados pessoais (nome, e-mail, telefone).
- Permitir cadastro de currículo (dados como formação acadêmica, experiência profissional, habilidades, idiomas e portfólio).
- Coletar informações acadêmicas e experiências profissionais.
- Validar os campos obrigatórios antes do envio.
- Exibir mensagens de sucesso ou erro.

#### Não Funcionais
- O formulário deve ser responsivo.
- A validação deve ocorrer no cliente (navegador) com JavaScript/jQuery.
- Interface amigável e visualmente agradável.
- Os arquivos devem ser organizados conforme estrutura de pastas definida.

---

### 🎨 Design do Formulário

- **Layout e Estrutura:** Estrutura com seções (dados pessoais, formação, experiência, portfólio).
- **Componentes Utilizados:**  
  - input[type="text"], input[type="email"], input[type="tel"], input[type="date"], input[type="url"], input[type="file"], input[type="checkbox"]
  - select, textarea, button, label, div (para agrupamento e organização de campos)
- **Estilo Visual:** Layout desenvolvido com CSS para tornar a interface atrativa, utilizando fontes legíveis, espaçamento adequado e cores suaves.

---

## ⚙️ Implementação

### HTML/CSS
- Toda a estrutura do formulário está no arquivo index.html.
- O CSS externo está na pasta /CSS.

### JavaScript/jQuery
- Validações de campos obrigatórios.
- Validação de CPF.
- Máscara de telefone.
- Adiciona seções de formação acadêmica, experiência profissional e idioma.
- Adiciona checkbox de habilidades.
- Feedback ao usuário com mensagens dinâmicas.
- Scripts organizados na pasta /JS.

---

## 📊 5W2H (Planejamento do Projeto)

| 5W      | Descrição                                                       |
|---------|------------------------------------------------------------------|
| **What**   | Criação de um sistema web para cadastro de currículos         |
| **Why**    | Facilitar o envio e o gerenciamento de currículos             |
| **Where**  | Aplicação Web, hospedada localmente ou em servidor online     |
| **When**   | Fase 1: até data N1 / Fase 2: até data N2                     |
| **Who**    | Equipe com até 5 integrantes                                   |
| **How**    | Usando tecnologias web: HTML, CSS, JS/jQuery e futuramente backend (PHP ou Node.js) |
| **How Much** | Não se aplica neste contexto acadêmico                      |

---

## 📥 Instruções de Uso

### 1. Clonando o Projeto

Clone o repositório para a sua máquina local utilizando o comando Git:

```bash
git clone https://github.com/SEU_USUARIO/NOME_DO_REPOSITORIO.git
```

### 2. Abrindo o Projeto


Abra o projeto em um editor de código, como o VS Code.

---

## 🚀 Tecnologias Utilizadas

- **HTML** - Linguagem de marcação para estruturação do conteúdo web.
- **CSS** - Folhas de estilo para personalização visual.
- **JavaScript** - Linguagem de programação para interatividade e validação de formulários.
- **jQuery** - Biblioteca JavaScript para facilitar a manipulação do DOM e a interação com o usuário.

---

## 📚 Bibliotecas e Instalação

Este projeto usa a biblioteca jQuery para facilitar as interações com o DOM. Não é necessário instalar nada adicionalmente para este projeto, pois o jQuery está incluído diretamente no arquivo index.html via CDN.

Caso queira usar o jQuery localmente, basta adicionar o seguinte trecho ao seu HTML dentro da tag `<head>`:

```html
<script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
```

## 🛠️ Recomendação de Ferramentas

### 1. VS Code (Visual Studio Code)

O VS Code é uma excelente ferramenta para edição de código. Ele possui uma interface limpa, suporte a várias linguagens de programação, e diversas extensões úteis.

**Como instalar o VS Code:**
- Baixe e instale o VS Code em [https://code.visualstudio.com/](https://code.visualstudio.com/).

**Como usar o VS Code:**
- Abra o VS Code.
- Clique em **File > Open Folder** e selecione a pasta do seu projeto clonado.

### 2. Extensão Live Server no VS Code

A extensão Live Server permite que você visualize as alterações em tempo real, sem precisar recarregar manualmente o navegador.

**Como instalar a extensão Live Server:**
- Abra o VS Code.
- Vá até a aba de extensões (ícone de quadrado à esquerda).
- Pesquise por "Live Server" e clique em **Install**.

**Como usar o Live Server:**
- Após abrir o projeto no VS Code, clique com o botão direito no arquivo `index.html`.
- Selecione a opção **Open with Live Server**.

O navegador será aberto automaticamente com a versão atualizada do seu projeto. Isso permitirá que você veja todas as modificações em tempo real enquanto trabalha.

---

## 📜 Licença

Este projeto está licenciado sob a **MIT License** - veja o arquivo LICENSE para mais detalhes.
