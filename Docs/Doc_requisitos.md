● Documento de Visão do Sistema e Especificação de
Requisitos
Time: FlexiMetrics
Alunos: Danilo Pereira, Matheus Serra Lourenço, Pedro dos Santos Garcia, Vinicius
Machado
Turma: Projeto Integrador I
Campus de Taguatinga

1. Introdução
● 1.1. Propósito: Deseja-se o desenvolvimento de um sistema acessível via web,
voltado para o registro de resultados de testes realizados em campo ou em
ambientes controlados.
● 1.2. Escopo do Produto:
○ Sistema web com:
■ Cadastro e login de usuários.
■ Registro de resultados de testes.
■ Visualização e gerenciamento dos dados coletados.
■ Geração de relatórios individuais e em grupo.
■ Filtros por data, tipo de teste, usuário, localidade, etc.
■ Exportação de relatórios em Excel.
■ Não incluirá análise automática dos resultados (ex: inteligência
artificial).
■ Não fará integração com sistemas externos (ex: ERPs, CRMs) nesta
fase.
■ Não haverá suporte para múltiplos idiomas (apenas português,
inicialmente).
■ Não incluirá funcionalidades de chat, notificações push ou chamadas.
■ Não contemplará hardware específico (ex: sensores ou dispositivos
externos).
● 1.3. Definições, Acrônimos e Abreviações: N/A
● 1.4. Referências: Manual de medidas, testes e avaliações.

2. Posicionamento do Produto
● 2.1. Problema: Atualmente, os alunos do curso de Educação Física do CEUB
enfrentam dificuldades no registro, organização e análise dos dados relacionados às
avaliações físicas, especialmente no que se refere às medições de flexibilidade e
outras métricas corporais. Esses procedimentos são frequentemente realizados de
forma manual, por meio de anotações em papel ou planilhas não padronizadas, o
que aumenta o risco de erros, dificulta o acompanhamento evolutivo dos resultados
e torna o processo mais lento e menos eficiente.
A ausência de um sistema automatizado compromete a agilidade e a confiabilidade
dos registros, além de limitar a geração de relatórios comparativos, tanto individuais
quanto coletivos, fundamentais para fins acadêmicos e pedagógicos.
Dessa forma, há uma necessidade clara de uma solução digital que centralize os
dados, realize os cálculos automaticamente e permita uma análise mais precisa e
acessível das medidas obtidas durante as avaliações físicas dos alunos.
● 2.2. Posição do Produto: O sistema para registro e cálculo dos resultados do teste
PROESP propõe uma solução especializada, simples e eficiente para alunos e
professores do curso de Educação Física do CEUB e outras instituições que utilizam
esse protocolo de avaliação física.
Diferentemente de ferramentas genéricas ou processos manuais, nosso produto
automatiza o armazenamento seguro dos dados e realiza os cálculos específicos do
PROESP com precisão e rapidez, eliminando erros humanos comuns na
manipulação manual. Além disso, oferece geração automática de relatórios claros,
facilitando o acompanhamento individual e coletivo do desempenho físico dos
alunos.
Os usuários escolherão esta solução porque ela é desenvolvida sob medida para as
necessidades reais do PROESP, garantindo praticidade, economia de tempo e
confiabilidade. A interface intuitiva e a possibilidade de acesso via dispositivos
móveis e computadores por meio web tornam o sistema acessível em campo ou em
ambiente acadêmico, promovendo maior engajamento e uso contínuo.
Ao focar exclusivamente no PROESP, o produto entrega valor diferenciado ao
oferecer um ambiente dedicado e otimizado, que simplifica processos críticos do
curso de Educação Física, facilitando a análise e a tomada de decisões pedagógicas
baseadas em dados confiáveis.

3. Descrição das Partes Interessadas e Usuários
● 3.1. Resumo das Partes Interessadas: O público alvo dessa aplicação abrange
professores de Educação Física do Ensino Médio, Alunos do Ensino Médio e
Graduandos em Educação Física. Além disso, são investidores do projeto a
Professora Juliana Alves, o professor André Arantes e o grupo FlexiMetrics.
● 3.2. Resumo dos Usuários:
○ Aluno (usuários indireto)
■ Necessidades: não acessa o sistema diretamente, mas precisa que
suas informações estejam corretas.
■ Características: grande número de registros, dependem da
confiabilidade do sistema,
○ Escola (usuários direto)
■ Acessar dados e relatórios de alunos e turmas
■ Características: uso moderado, variado nível de conhecimento em
tecnologia, foco em produtividade e simplicidade.
○ Aluno de Educação Física (usuários direto)
■ Necessidades: Cadastrar novos alunos, gerenciar dados de alunos,
gerar gráficos e relatórios.
■ Características: uso intenso, variado nível de conhecimento em
tecnologia, foco em produtividade e simplicidade.
● 3.3. Ambiente de Usuário:
○ Dispositivos utilizados: computador, notebook, smartphone, tablet.
○ Plataformas: navegador web.
○ Conectividade: acesso à internet..
○ Condições do ambiente: uso compartilhado ou individual, segurança de
dados sensíveis.
○ Perfil de uso: eventual.

4. Visão Geral do Produto
● 4.1. Perspectiva do Produto: N/A
● 4.2. Lista de Funcionalidades:
○ O sistema deve permitir ao usuário cadastrar novos alunos.
○ O sistema deve permitir ao usuário editar informações de alunos.
○ O sistema deve permitir ao usuário excluir registros de alunos.
○ O sistema deve permitir ao usuário consultar a lista de alunos cadastrados.
○ O sistema deve permitir ao usuário gerar relatórios de alunos, incluindo:
■ Relatórios gerais;
■ Relatórios por gênero;
■ Relatórios por turma.
○ O sistema deve permitir ao usuário consultar dados de alunos.
○ O sistema deve permitir ao usuário gerar relatórios
○ O sistema deve traçar perfis de usuários (detalhar quais).
○ O sistema deve categorizar usuários (detalhar critérios).
● 4.3. Restrições:
○ O primeiro MVP deve ser entregue até o final do semestre letivo;
○ O sistema deve ter como base o teste PROESP;
○ Os dados de alunos devem ser protegidos;

5. Requisitos Funcionais
● 5.1. Lista de funcionalidades agrupadas por MPV (Mínimo Produto Viável).
● 5.2. Canvas MVP:

○ https://drive.google.com/file/d/1_bIN5ElvCeTO4jHed9eX0Q4eLewOczUj/v
iew?usp=sharing

6. Requisitos Não Funcionais
● 6.1. Requisitos de Desempenho:
○ A coleta de dados deve ocorrer em tempo real sem atrasos perceptíveis para
o usuário.
○ O dashboard de métricas deve apresentar tempo de resposta inferior a 2
segundos em consulta.
○ A solução deve suportar, no mínimo, 500 usuários simultâneos sem
degradação perceptível de desempenho.
○ O sistema deve ser capaz de processar grandes volumes de dados sem
perda de consistência.
● 6.2. Requisitos de Confiabilidade:
○ O sistema deve armazenar os dados de forma precisa e sem corrupção.
○ Todos os dados sensíveis devem ser criptografados.
○ O sistema deve garantir conformidade com normas de segurança e proteção
de dados.
○ O sistema deve realizar backups automáticos em intervalos não superiores a
24 horas.
● 6.3. Requisitos de Usabilidade:
○ A interface deve ser intuitiva e fácil de usar.
○ O sistema deve ser executado em ambiente web.
○ O sistema deve utilizar linguagem simples e objetiva, evitando termos
técnicos.
○ O sistema deve ser responsivo, permitindo o acesso em diferentes
dispositivos.
● 6.4. Requisitos de Suporte:
○ O projeto deve contar com o apoio da coordenação/professores.
○ A organização deve prover treinamento contínuo para as equipes no uso de
metodologias ágeis e ferramentas de métricas.
○ A equipe deve ser multidisciplinar, incluindo profissionais de negócio,
tecnologia e análise de dados.
○ Deve existir um plano de gestão da mudança para apoiar a adaptação
cultural e operacional da organização.
○ O sistema deve permitir a integração de dados por meio de APIs.

7. Marcos do Projeto
● 7.1. Cronograma de Lançamento:
○ 14/08 - Reunião de Kickoff
○ 15/09 - Mapa de Empatia e Definição de Personas
○ 15/09 - Levantamento e consolidação de requisitos
○ 15/09 - Protótipo de baixa fidelidade
○ 06/10 - Protótipo de navegação
○ 27/10 - Implementação funcional miníma de API para acesso a base de
dados
○ 17/11 - Implementação da API para acesso à base de dados
○ 24/11 - Testes com usuários (professor e graduandos)
○ 15/12 - Entrega da versão com API e Documentação do Projeto
● 7.2. Dependências: N/A
8.Histórico de revisões
Versão Autores Data
1.0 Gerente 15/09/2025
Fonte de Referência: Adaptado do modelo de Visão de Software (Software Vision) descrito no livro "Managing
Software Requirements: A Unified Approach", de Dean Leffingwell e Don Widrig.