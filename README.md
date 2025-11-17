## **Portal Acadêmico**

 ## **Participantes**
* Bruno Felipe Rocha
* Pedro Henrique Tavares
* Cauã Kinsman

## 📘 **Descrição do Projeto**

O **Portal Acadêmico** é uma aplicação desktop desenvolvida para instituições de ensino que desejam gerenciar cursos, disciplinas e materiais.
O sistema oferece áreas específicas para alunos, professores e administradores, permitindo organização eficiente e centralizada das informações acadêmicas.

---

## 🎯 **Objetivo Geral**

Criar um sistema desktop moderno e funcional que auxilie instituições e alunos no gerenciamento de informações acadêmicas, substituindo processos manuais e fragmentados por uma solução única e intuitiva.

---

## 👥 **Público-Alvo**

* Alunos
* Professores
* Coordenadores
* Administradores
* Instituições de ensino

---

## 🧱 **Arquitetura do Sistema**

O sistema é estruturado em **camadas**, garantindo organização e manutenção simples.

### **Camadas Principais**

* **Interface (JavaFX):** telas, navegação e interação com o usuário.
* **Modelos:** entidades que representam cursos, disciplinas e materiais.
* **Serviços:** regras de negócio e validações.
* **Persistência:** comunicação com o banco de dados via JDBC.

---

## 🧩 **Entidades do Sistema**

![Der Diagrama Portal Acadêmico]("Diagrama Poo.png")



## 🔗 **Relacionamentos**

* Um curso contém várias disciplinas.
* Uma disciplina contém vários materiais.

---

## 🖥️ **Telas da Aplicação**


### **Painel do Aluno**

Mostra Cursos, Disciplinas e Materiais disponível

---

### **Painel do Administrador**

Permite gerenciar:

* Cursos
* Disciplinas
* Materiais 

---

### **Lista de Cursos**

Exibe todos os cursos disponíveis na instituição.

---

### **Detalhes do Curso**

Apresenta informações completas:
descrição, carga horária, nível e disciplinas.

---

### **Materiais da Disciplina**

Mostra todos os conteúdos enviados para aquela disciplina.

---


## 🛠️ **Tecnologias Utilizadas**

* Java
* JavaFX
* FXML
* CSS para estilização
* Banco de dados MySQL.
* JDBC para acesso aos dados

---


