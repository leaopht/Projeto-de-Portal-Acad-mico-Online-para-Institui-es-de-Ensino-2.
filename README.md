## **Portal Acadêmico**

 ## **Participantes**
* Bruno Felipe Rocha
* Pedro Henrique Tavares
* Cauã Kinsman

## 📘 **Descrição do Projeto**

O **Portal Acadêmico em JavaFX** é uma aplicação desktop desenvolvida para instituições de ensino que desejam gerenciar cursos, formações, disciplinas, materiais e calendário acadêmico.
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
* **Modelos:** entidades que representam formações, cursos, usuários e outros elementos.
* **Serviços:** regras de negócio e validações.
* **Persistência:** comunicação com o banco de dados via JDBC.

---

## 🧩 **Entidades do Sistema**


## 🔗 **Relacionamentos**

* Um usuário possui várias inscrições.
* Uma formação possui vários cursos.
* Um curso contém várias disciplinas.
* Uma disciplina contém vários materiais.
* Um curso pode ter vários eventos no calendário.

---

## 🖥️ **Telas da Aplicação**

### **Tela de Login**

Primeiro contato do usuário com o sistema.
Define acesso ao painel de aluno ou administrador.

---

### **Painel do Aluno**

Mostra cursos inscritos, materiais disponíveis e calendário de eventos.

---

### **Painel do Administrador**

Permite gerenciar:

* Formações
* Cursos
* Disciplinas
* Materiais
* Eventos do calendário
* Usuários e inscrições

---

### **Lista de Cursos**

Exibe todos os cursos disponíveis na instituição.

---

### **Detalhes do Curso**

Apresenta informações completas:
descrição, carga horária, nível, disciplinas e eventos futuros.

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


