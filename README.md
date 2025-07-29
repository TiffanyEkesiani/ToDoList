# 📂 TO DO LIST - Sistema de Gerenciamento de Tarefas em Java

Este projeto foi desenvolvido como parte do curso *Introdução à Linguagem Java* (Senac Lapa Tito) e representa uma das minhas __primeiras aplicações práticas com orientação a objetos__.

A proposta era criar um sistema simples, executado via terminal, que organizasse tarefas divididas por categorias: pessoal, estudo e trabalho. Ao longo do desenvolvimento, pude reforçar meu entendimento sobre herança, polimorfismo, classes abstratas e entrada de dados com `Scanner`.

---

## ⚙️ Funcionalidades

- 📝 Cadastro de tarefas por categoria:
  - __Tarefas pessoais__
  - __Tarefas de estudo__
  - __Tarefas de trabalho__
- ✅ Marcação de tarefas como concluídas
- 🔍 Visualização de todas as tarefas cadastradas
- ⌛ Verificação de tarefas em atraso (com base na deadline)
- 📌 Exibição do status: pendente ou concluída

---

## 🗂️ Estrutura do Projeto

```
├── Main.java → Classe principal com menu interativo
├── Tarefas.java → Classe abstrata base para as tarefas
├── Personal.java → Subclasse para tarefas pessoais
├── Study.java → Subclasse para tarefas de estudo
├── Work.java → Subclasse para tarefas de trabalho
```

---

## ▶️ Como Executar

1. Compile os arquivos:

```bash
javac *.java
```

2. Execute o programa:

```bash
java Main
```

3. Siga as instruções do menu para adicionar ou visualizar tarefas.
---

### 🖥️ Exemplo de Execução no Terminal

```
====== MENU DE TAREFAS ======
1 - Adicionar tarefa pessoal
2 - Adicionar tarefa de estudo
3 - Adicionar tarefa de trabalho
4 - Listar todas as tarefas
5 - Marcar tarefa como concluída
6 - Sair

Escolha uma opção:

```
---

### 🛠️ Tecnologias e Conceitos Aplicados
- Java 8+

- Programação Orientada a Objetos (POO)

- Classe abstrata, herança e polimorfismo

- Manipulação de datas com LocalDate

- Estruturas de repetição e condicionais

- Entrada de dados com Scanner

- Uso de ArrayList

--- 

## ℹ️ *Observações*
- O sistema roda totalmente no console.

- As tarefas são armazenadas apenas em memória (não há persistência de dados).

- Projeto desenvolvido para fins didáticos, com possibilidade de expansão futura.

---

## 👩‍💻 Desenvolvido por:

###  Tiffany Ekesiani

<a href="https://github.com/TiffanyEkesiani" target="_blank">
  <img src="https://img.shields.io/badge/GitHub-C71585?style=for-the-badge&logo=github&logoColor=white">
</a>
<a href="https://www.linkedin.com/in/tiffanyekesiani/" target="_blank">
  <img src="https://img.shields.io/badge/LinkedIn-C71585?style=for-the-badge&logo=linkedin&logoColor=white">
</a>

</div>

---

### Fernanda Ribeiro

<a href="https://github.com/f3f3h" target="_blank">
  <img src="https://img.shields.io/badge/GitHub-C71585?style=for-the-badge&logo=github&logoColor=white">
</a>
<a href="https://www.linkedin.com/in/f3f3h/" target="_blank">
  <img src="https://img.shields.io/badge/LinkedIn-C71585?style=for-the-badge&logo=linkedin&logoColor=white">
</a>
