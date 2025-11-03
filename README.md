# Projeto-de-Portal-Acad-mico-Online-para-Institui-es-de-Ensino-2.
1. Tema
Portal Acadêmico Online para Instituições de Ensino
2. Descrição
Problema a ser resolvido: Muitas instituições de ensino ainda utilizam sistemas fragmentados ou processos manuais para divulgar cursos, organizar calendários acadêmicos e disponibilizar materiais aos alunos. Isso gera dificuldades de acesso à informação, desorganização e perda de tempo tanto para a instituição quanto para os estudantes.
Justificativa: Um portal acadêmico online centralizado facilita a comunicação entre instituição e alunos, permitindo acesso rápido a informações sobre programas de ensino, cursos e formações. Para os inscritos, oferece uma área restrita com materiais, conteúdos e calendário de aulas, garantindo organização, acessibilidade e praticidade.
Objetivos:
● Criar um site que apresente os programas de ensino, cursos e formações oferecidos pela instituição.
● Disponibilizar uma área exclusiva para alunos inscritos, com acesso a conteúdos, materiais e calendário acadêmico.
● Melhorar a comunicação e gestão acadêmica, reduzindo processos manuais.
● Garantir maior transparência e acessibilidade aos serviços educacionais.
Potenciais clientes/usuários:
● Instituições de ensino (escolas, universidades, cursos livres).
● Alunos (usuários inscritos com login e senha).
● Professores/gestores (que podem alimentar o sistema com cursos, conteúdos e materiais).
● Visitantes (público em geral que acessa as informações de cursos).
3. Diagrama de Caso de Uso (UC)
A nível inicial, ficaria algo assim:
Atores:
● Visitante → consultar cursos, formações, programas.
● Aluno → acessar materiais, calendário, conteúdos.
● Professor/Admin → cadastrar cursos, disponibilizar materiais, gerenciar calendário.
Principais casos de uso:
● Cadastrar/Login
● Visualizar cursos/programas
● Consultar calendário
● Baixar materiais de aula
● Cadastrar cursos/formações (Admin)
● Disponibilizar conteúdos/materiais (Admin)
4. DER (Diagrama Entidade-Relacionamento)
Estrutura inicial de banco (MySQL Workbench):
Entidades e atributos principais:
● Usuário(id_usuario, nome, email, senha, tipo_usuario [Aluno/Admin/Professor])
● Curso(id_curso, titulo, descricao, carga_horaria, nivel)
● Formacao(id_formacao, titulo, descricao)
● Disciplina(id_disciplina, nome, id_curso)
● Material(id_material, titulo, descricao, arquivo, id_disciplina)
● Calendario(id_evento, data, descricao, id_curso)
● Inscricao(id_usuario, id_curso, data_inscricao)
Relacionamentos:
● Usuário 1—N Inscrição N—1 Curso
● Curso 1—N Disciplina
● Disciplina 1—N Material
● Curso 1—N Calendário
● Formação 1—N Curso
