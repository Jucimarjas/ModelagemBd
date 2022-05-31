Apresentação

Banco de dados para gerenciamento de uma faculdade

Objetivos do banco de dados:

    * Realizar controle centralizado de 
    * alunos, professores, cursos, diciplinas, historico escolar e turmas

Fases do Projeto

fases:
    * levantamento dos requisitos
    * Identificação de entidades e relacionamentos
    * Modelo E-R : cardinalidades
    * Diagrama E-R : Eliminando N:M
    * Dicionario de Dados
    * Normalização (3-ETAPAS) FN1, FN2, FN3	
    * Implementação
    * Testes Básicos

Regras de negócio

    * Um aluno so pode estar matriculado em um curso por vez
    * Alunos possuem um codigo de identificação (RA)
    * Cursos são compostos por diciplinas
    * Cada disciplina tera no maximo 30 alunos por turma
    * As diciplinas podem ser obrigatorias ou optativas, dependendo do curso
    * As diciplinas pertencem a departamentos especificos
    * Cada disciplina possui um codigo de identificação	
    * Alunos podem trancar matricula, não estando então 
      matriculados em nenhuma disciplina no semestre
    * Em cada semestre, cada aluno pode se matricular em no maximo 9 diciplinas
    * A faculdade terá no maximo 3.000 alunos matriculados 
      simultaneamente, em 10 cursos distintos  
    * entram 300 alunos novos por ano.
    * existem 90 diciplinas no total disponiveis
    * Um histotio escolar traz todas as diciplinas cursadas por um aluno
      incluindo nota final, frequencia e periodo do curso realizado.
    * Professores podem ser cadastrados mesmo sem lecionar diciplinas
    * Existem 40 professores trabalhando na escola
    * Cada professor ira lecionar no maximo 4 disciplinas diferentes
    * Cada professor e vinculado a um departamento
    * Professores são identificados por um codigo de professor

Entidades
  
    * disciplinas , professores, curso , departamento
    * Relacionamentos identificados
    * Aluno esta matriculado em curso
    * Aluno cursa disciplina
    * Aluno realizou diciplina
    * Disciplina pertence a curso
    * Professor ministra diciplina
    * Professor pertence a  departamentos
    * Departamento e responsável por disciplina
    * Departamento controla curso
    * Disciplina depende de disciplina

    