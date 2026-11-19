# Sistema-BrightFuture---Programa-o-Web-Frontend
Esse é o repositório remoto que a Equipe 7 da segunda unidade da disciplina de Programação Web Frontend 2026.2 vai usar para desenvolver o Tema 5 - Sistema de informação do aluno (BrightFuture)

1. -BrightFuture-
“Cada aluno, um futuro brilhante.”

2. Sobre o projeto:
  É um sistema de Informações do Aluno para a abstração de uma escola chamada BrightFuture, com o cenário imaginado de que é uma escola particular fundada em 2001 em Curitiba (PR), com
Educação Infantil, Ensino Fundamental e Médio, cerca de 900 alunos, 70 professores e 12 funcionários na secretaria. Proposta pedagógica focada em projetos e tecnologia.

2.1  
  Contexto / Problema : Notas e frequência são lançadas em diários de papel e depois digitadas pela secretaria, com atraso de até duas semanas. Contatos de responsáveis ficam desatualizados 
  e registros de ex-alunos formados se acumulam junto aos ativos.

2.2 Solução Arquitetada : Sistema de Informações do Aluno particular para o colégio que gerencie e administre todas as pendências acadêmicas tanto do aluno quanto da coordenação da instituição.
“O BrightFuture permite matricular alunos, lançar notas e frequência e acompanhar o desempenho da turma em um só lugar.”

3. O mínimo de funcionalidades que o sistema pretende entregar/possuir:
Requisitos Mínimos e Telas – Sistema BrightFuture
  1. Login
   * Campos: Usuário, senha e opção "Esqueceu a senha" (exibindo orientação para solicitar redefinição à secretaria ou administrador).
   * Controle de acesso (LGPD): Logins individuais por perfil (Secretaria, Professor e Coordenação), com redirecionamento automático para a tela inicial correspondente, sem precisar selecionar o tipo de perfil no login.
  2. Lista de Alunos (Tela Principal)
   * Exibição: Turma, nome dos alunos, média parcial e indicador visual de frequência (verde para regular e amarelo para atenção).
   * Visão do Professor: Botões "Lançar notas" e "Registrar aula".
   * Visão da Secretaria: Botão "+ Nova Matrícula" e filtro de status (Ativos, Formados e Transferidos) para separar ex-alunos sem apagar o histórico.
  3. Tela de Matrícula
   * Dados do Aluno: Nome completo, CPF, data de nascimento e seleção da turma.
   * Dados do Responsável: Nome, parentesco, telefone/WhatsApp e e-mail (para cumprir a meta de 100% de revisão anual de contatos e segurança de menores de idade).
   * Documentação: Campo opcional para upload do contrato digitalizado (evitando travar a matrícula caso o arquivo seja anexado depois, mantendo o processo abaixo de 10 minutos).
  4. Perfil do Aluno
   * Identificação e Status: Código de matrícula, nome, turma e seletor de situação (Ativo, Formado ou Transferido — funcionando como arquivamento lógico).
   * Contatos: Bloco com dados dos responsáveis, botão "Editar / Confirmar Contatos" e data da última revisão anual.
   * Desempenho: Planilha de notas, média parcial e total de faltas.
  5. Lançamento de Notas e Chamada
   * Lançamento de Notas: Seletor do tipo de avaliação (prova, bônus, etc.), lista de alunos com campo numérico ao lado de cada nome e um único botão "Confirmar Lançamento" ao final da tela.
   * Chamada: Data da aula, resumo do conteúdo ministrado e lista de alunos já pré-marcada como "Presente" (o professor marca apenas quem faltou), finalizando com o botão "Registrar Aula".
  6. Painel da Coordenação
   * Filtros no Topo: Seletores por segmento (Educação Infantil, Fundamental e Médio), turma, disciplina e período letivo.
   * Cards de Resumo: Indicadores rápidos com média geral de notas (verde se regular), taxa de frequência, quantidade de alunos em atenção (destaque em amarelo) e status dos diários (monitorando o prazo máximo de 48h para       lançamento).
   * Lista Prioritária ("Alunos em Atenção"): Tabela automática apenas com alunos ativos que estejam abaixo da média ou com baixa frequência, exibindo turma, motivo do alerta, telefone/WhatsApp do responsável, botão             "Abrir Perfil / Boletim" e atalho "Registrar Contato" para histórico de ligações.
   * Gráficos Comparativos: Barras de média de notas (azul royal) e taxa de frequência (verde ou amarelo) por turma.
   * Privacidade (LGPD): Exibição restrita na listagem geral, mantendo dados sensíveis do menor (como CPF e endereço) protegidos apenas dentro da ficha individual.

4. Tecnologias que o sistema usa:
  HTML, CSS e JavaScript puros.

5. Como Executar:
  -clonar o repositório e abrir o arquivo inicial no navegador.
  -os dados ficam no localStorage, ou seja, se limitam e um navegador em específico, qualquer dado que guardar em um navegador vai pertencer somente àquele.

6. Estrutura de pastas:
   - Projeto BrightFuture
     -> Main/Root
       ->index.html
       ->style.css
       ->script.js
       ->assets

7. Equipe:
   - Thiago Oliveira Gouveia de Mattos (Líder)
   - Ângello Marcus Sobral Cruz
   - Pedro Henrique Carvalho dos Santos

8. Créditos e Observações:
   - Identidade visual do projeto e estudo de caso fornecidos pelo prof. Josimar dos Santos

