Documento de Visão do Sistema e Especificação de Requisitos

Time: FlexiMetrics
Alunos: Danilo Pereira, Matheus Serra Lourenço, Pedro dos Santos Garcia, Vinicius Machado
Turma: Projeto Integrador I
Campus: Taguatinga

1. Introdução
1.1 Propósito

Deseja-se o desenvolvimento de um sistema acessível via web, voltado para o registro de resultados de testes realizados em campo ou em ambientes controlados.

1.2 Escopo do Produto
O sistema web deve incluir:

Cadastro e login de usuários

Registro de resultados de testes

Visualização e gerenciamento dos dados coletados

Geração de relatatórios individuais e em grupo

Filtros (data, tipo de teste, usuário, localidade etc.)

Exportação de relatórios em Excel

O sistema não incluirá:

Análise automática (ex.: inteligência artificial)

Integração com sistemas externos (ex.: ERP, CRM) nesta fase

Suporte a múltiplos idiomas (apenas português inicialmente)

Funcionalidades de chat, notificações push ou chamadas

Integração com hardware específico (ex.: sensores ou dispositivos externos)

1.3 Definições, Acrônimos e Abreviações

N/A

1.4 Referências

Manual de medidas, testes e avaliações.

2. Posicionamento do Produto
2.1 Problema

Atualmente, os alunos do curso de Educação Física do CEUB enfrentam dificuldades no registro, organização e análise dos dados relacionados às avaliações físicas, especialmente medições de flexibilidade e outras métricas corporais.

Os processos são geralmente manuais, feitos em papel ou planilhas não padronizadas, o que gera:

Maior risco de erros

Dificuldade no acompanhamento evolutivo

Lentidão

Pouca confiabilidade

Há necessidade de um sistema digital que centralize os dados, automatize cálculos e facilite a análise.

2.2 Posição do Produto

O sistema propõe uma solução especializada para o teste PROESP, oferecendo:

Armazenamento seguro

Cálculos automáticos

Relatórios individuais e coletivos

Interface intuitiva

Acesso via navegador em qualquer dispositivo

O sistema se destaca por ser feito especificamente para o PROESP, oferecendo:

Praticidade

Economia de tempo

Precisão

Acesso web responsivo

3. Descrição das Partes Interessadas e Usuários
3.1 Partes Interessadas

Professores de Educação Física do Ensino Médio

Alunos do Ensino Médio

Graduandos de Educação Física

Professora Juliana Alves

Professor André Arantes

Grupo FlexiMetrics

3.2 Usuários
Aluno (usuário indireto)

Não acessa o sistema diretamente

Depende da precisão das informações cadastradas

Escola (usuário direto)

Acessa dados e relatórios de alunos e turmas

Conhecimento tecnológico variado

Uso moderado

Aluno de Educação Física (usuário direto)

Cadastrar alunos

Gerenciar dados

Gerar gráficos e relatórios

Uso frequente

3.3 Ambiente de Usuário

Dispositivos: computador, notebook, smartphone e tablet

Plataformas: navegador web

Internet: necessária

Ambiente: uso compartilhado ou individual

Dados sensíveis: devem ser protegidos

Frequência de uso: eventual

4. Visão Geral do Produto
4.1 Perspectiva do Produto

N/A

4.2 Lista de Funcionalidades

Cadastrar novos alunos

Editar informações de alunos

Excluir registros

Consultar lista de alunos

Gerar relatórios:

Gerais

Por gênero

Por turma

Consultar dados de alunos

Traçar perfis de usuários

Categorizar usuários

4.3 Restrições

O MVP deve ser entregue até o fim do semestre letivo

O sistema deve ter como base o teste PROESP

Os dados dos alunos devem ser protegidos

5. Requisitos Funcionais
5.1 Funcionalidades agrupadas por MVP

(Conteúdo conforme documento original)

5.2 Canvas MVP

Disponível no link indicado no documento.

6. Requisitos Não Funcionais
6.1 Desempenho

Coleta de dados deve ocorrer em tempo real

Dashboard deve responder em menos de 2 segundos

Suporte a no mínimo 500 usuários simultâneos

Processamento de grandes volumes sem perda de consistência

6.2 Confiabilidade

Armazenamento preciso e sem corrupção

Criptografia de dados sensíveis

Conformidade com normas de segurança

Backups automáticos a cada 24h

6.3 Usabilidade

Interface intuitiva

Execução em ambiente web

Linguagem simples

Design responsivo

6.4 Suporte

Apoio da coordenação/professores

Treinamento contínuo

Equipe multidisciplinar

Plano de gestão da mudança

Integração por APIs

7. Marcos do Projeto
7.1 Cronograma

14/08 — Reunião de Kickoff

15/09 — Mapa de Empatia e Personas

15/09 — Levantamento de requisitos

15/09 — Protótipo de baixa fidelidade

06/10 — Protótipo de navegação

27/10 — Implementação funcional mínima da API

17/11 — Implementação da API

24/11 — Testes com usuários

15/12 — Entrega da versão com API e documentação

7.2 Dependências

N/A

8. Histórico de Revisões

| Versão | Autor   | Data       |
| ------ | ------- | ---------- |
| 1.0    | Gerente | 15/09/2025 |
