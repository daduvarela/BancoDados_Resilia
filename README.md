Objetivos:

A Resilia está pensando em lançar um novo sistema de
acompanhamento e para isso precisa de ajuda para modelar um
banco de dados que vai armazenar seus cursos, turmas e alunos.





Perguntas:
⇨ Existem outras entidades além dessas três? 
   Não, apenas as entidades Curso, Turma, Aluno



⇨ Quais são os principais campos e tipos? 
  Id_curso, nome, carga_horaria;
  data_inicio, data_final, id_curso(FK), id_turma(PK);
  cpf, nome, telefone, id_curso, id_turma



⇨ Como essas entidades estão relacionadas?
  A entidade Turma recebe uma chave estrangeira da entidade Curso e a entidade Aluno recebe duas chaves estrangeiras das entidades Curso e Turma.
