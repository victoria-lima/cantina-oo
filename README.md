<h1 align="center">
  ☕ <br>
  Sistema de Cafeterias
</h1>

<p align="center">
  <b>Aplicação Java (POO) desenvolvida para cadastro, gestão e busca de cafeterias.</b>
</p>

<p align="center">
  <a href="https://www.java.com/" target="_blank">
    <img src="https://img.shields.io/badge/Java-11%2B-ED8B00?style=for-the-badge&logo=java&logoColor=white" alt="Java" />
  </a>
  <img src="https://img.shields.io/badge/Status-Conclu%C3%ADdo-00C853?style=for-the-badge" alt="Status" />
  <img src="https://img.shields.io/badge/UFPB-DCX-0052CC?style=for-the-badge" alt="UFPB DCX" />
</p>

<p align="center">
  <a href="#sobre">💻 Sobre</a> &nbsp;•&nbsp;
  <a href="#funcionalidades">✨ Funcionalidades</a> &nbsp;•&nbsp;
  <a href="#estrutura">🏛️ Estrutura</a> &nbsp;•&nbsp;
  <a href="#pastas">📁 Pastas</a> &nbsp;
</p>

<a id="sobre"></a>
 ##
 💻 Sobre o Projeto

O **Sistema de Cafeterias** é uma aplicação interativa desenvolvida em Java no modelo **CLI (Command Line Interface)**. O projeto permite registrar novos estabelecimentos, realizar buscas dinâmicas com tratamento de exceções e avaliar o porte de cada cafeteria através do número de mesas.

> 🎯 **Objetivo:** Aplicar na prática os pilares de **Programação Orientada a Objetos (POO)** como Encapsulamento, Abstração, Coleções em Memória e Tratamento de Exceções (`try/catch`).


<a id="funcionalidades"></a>
## 
✨ Funcionalidades

- [x] **➕ Cadastrar Cafeteria:** Registra o nome do estabelecimento e suas informações básicas.
- [x] **🔍 Buscar por Nome:** Pesquisa cafeterias cadastradas com tratamento para nomes inexistentes (`Exception`).
- [x] **📏 Verificação de Porte (`ehGrande`):** Método que identifica se a cafeteria é de grande porte (mais de 10 mesas).
- [x] **🖥️ Menu CLI Interativo:** Interface via terminal baseada em opções numéricas com `Scanner`.


<a id="estrutura"></a>
##
🏛️ Estrutura do Código

| Classe | Descrição / Responsabilidade |
| :--- | :--- |
| 📄 `Cafeteria` | **Modelo de Dados:** Guarda `nome`, `endereco`, `quantidadedeMesas` e a lógica `ehGrande()`. |
| ⚙️ `GerenciadorCafeterias` | **Regra de Negócio:** Mantém a lista de cafeterias e executa a busca por nome. |
| 🚀 `Main` | **Ponto de Entrada:** Controla o menu no terminal e interage com o usuário. |


<a id="pastas"></a>
## 
📁 Estrutura de Pastas do Repositório

```text
cafeteria/
└── 📁 src/
    └── 📁 main/
        └── 📁 java/
            └── 📁 br/ufpb/dcx/victoria/cafeteria/
                ├── 📄 Cafeteria.java
                ├── 📄 GerenciadorCafeterias.java
                └── 📄 Main.java
```
👩‍💻 Autora

Desenvolvido por Victoria como parte das atividades da disciplina de Programação / Ciência da Computação - UFPB.
