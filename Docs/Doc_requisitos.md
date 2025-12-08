

---

# Documento de Visão do Sistema e Especificação de Requisitos

**Time:** FlexiMetrics
**Alunos:** Danilo Pereira, Matheus Serra Lourenço, Pedro dos Santos Garcia, Vinicius Machado
**Turma:** Projeto Integrador I
**Campus:** Taguatinga

---

## 1. Introdução

### 1.1. Propósito

Deseja-se o desenvolvimento de um sistema acessível via web, voltado para o registro de resultados de testes realizados em campo ou em ambientes controlados.

### 1.2. Escopo do Produto

Sistema web com:

* Cadastro e login de usuários
* Registro de resultados de testes
* Visualização e gerenciamento dos dados coletados
* Geração de relatórios individuais e em grupo
* Filtros por data, tipo de teste, usuário, localidade, etc.
* Exportação de relatórios em Excel
* **Não incluirá:**

  * Análise automática dos resultados (ex: inteligência artificial)
  * Integração com sistemas externos (ex: ERPs, CRMs) nesta fase
  * Suporte a múltiplos idiomas (apenas português, inicialmente)
  * Funcionalidades de chat, notificações push ou chamadas
  * Suporte a hardware específico (ex: sensores ou dispositivos externos)

### 1.3. Definições, Acrônimos e Abreviações

N/A

### 1.4. Referências

Manual de medidas, testes e avaliações.

---

## 2. Posicionamento do Produto

### 2.1. Problema

Atualmente, os alunos do curso de Educação Física do CEUB enfrentam dificuldades no registro, organização e análise dos dados relacionados às avaliações físicas, especialmente no que se refere às medições de flexibilidade e outras métricas corporais.

Esses procedimentos são frequentemente realizados de forma manual, por meio de anotações em papel ou planilhas não padronizadas, o que aumenta o risco de erros, dificulta o acompanhamento evolutivo dos resultados e torna o processo mais lento e menos eficiente.

A ausência de um sistema automatizado compromete a agilidade e a confiabilidade dos registros, além de limitar a geração de relatórios comparativos, tanto individuais quanto coletivos, fundamentais para fins acadêmicos e pedagógicos.

Dessa forma, há uma necessidade clara de uma solução digital que centralize os dados, realize os cálculos automaticamente e permita uma análise mais precisa e acessível das medidas obtidas durante as avaliações físicas dos alunos.

### 2.2. Posição do Produto

O sistema para registro e cálculo dos resultados do teste **PROESP** propõe uma solução especializada, simples e eficiente para alunos e professores do curso de Educação Física do CEUB e outras instituições que utilizam esse protocolo de avaliação física.

Diferentemente de ferramentas genéricas ou processos manuais, nosso produto automatiza o armazenamento seguro dos dados e realiza os cálculos específicos do PROESP com precisão e rapidez, eliminando erros humanos comuns.

Além disso, oferece geração automática de relatórios claros, facilitando o acompanhamento individual e coletivo do desempenho físico dos alunos.

Os usuários escolherão esta solução porque ela é desenvolvida sob medida para as necessidades reais do PROESP, garantindo praticidade, economia de tempo e confiabilidade.

A interface intuitiva e o acesso via dispositivos móveis e computadores tornam o sistema acessível em campo ou em ambiente acadêmico, promovendo maior engajamento e uso contínuo.

Ao focar exclusivamente no PROESP, o produto entrega valor diferenciado ao oferecer um ambiente dedicado e otimizado, que simplifica processos críticos do curso de Educação Física e facilita a análise e a tomada de decisões pedagógicas baseadas em dados confiáveis.

---

## 3. Descrição das Partes Interessadas e Usuários

### 3.1. Resumo das Partes Interessadas

O público-alvo da aplicação abrange:

* Professores de Educação Física do Ensino Médio
* Alunos do Ensino Médio
* Graduandos em Educação Física

**Investidores do projeto:** Professora Juliana Alves, Professor André Arantes e o grupo FlexiMetrics.

### 3.2. Resumo dos Usuários

#### Aluno (usuário indireto)

* **Necessidades:** não acessa o sistema diretamente, mas precisa que suas informações estejam corretas.
* **Características:** grande número de registros; dependem da confiabilidade do sistema.

#### Escola (usuário direto)

* **Necessidades:** acessar dados e relatórios de alunos e turmas.
* **Características:** uso moderado, variado nível de conhecimento em tecnologia, foco em produtividade e simplicidade.

#### Aluno de Educação Física (usuário direto)

* **Necessidades:** cadastrar novos alunos, gerenciar dados e gerar gráficos e relatórios.
* **Características:** uso intenso, variado nível de conhecimento em tecnologia, foco em produtividade e simplicidade.

### 3.3. Ambiente de Usuário

* **Dispositivos utilizados:** computador, notebook, smartphone, tablet
* **Plataformas:** navegador web
* **Conectividade:** acesso à internet
* **Condições do ambiente:** uso compartilhado ou individual; segurança de dados sensíveis
* **Perfil de uso:** eventual

---

## 4. Visão Geral do Produto

### 4.1. Perspectiva do Produto

N/A

### 4.2. Lista de Funcionalidades

* Cadastrar novos alunos
* Editar informações de alunos
* Excluir registros de alunos
* Consultar lista de alunos cadastrados
* Gerar relatórios de alunos:

  * Relatórios gerais
  * Relatórios por gênero
  * Relatórios por turma
* Consultar dados de alunos
* Traçar perfis de usuários (detalhar quais)
* Categorizar usuários (detalhar critérios)

### 4.3. Restrições

* O primeiro MVP deve ser entregue até o final do semestre letivo
* O sistema deve ter como base o teste PROESP
* Os dados de alunos devem ser protegidos

---

## 5. Requisitos Funcionais

### 5.1. Lista de Funcionalidades Agrupadas por MVP

*(A ser detalhada posteriormente.)*

### 5.2. Canvas MVP

[Canvas MVP - Google Drive](https://drive.google.com/file/d/1_bIN5ElvCeTO4jHed9eX0Q4eLewOczUj/view?usp=sharing)

---

## 6. Requisitos Não Funcionais

### 6.1. Requisitos de Desempenho

* Coleta de dados em tempo real sem atrasos perceptíveis
* Dashboard com tempo de resposta < 2 segundos
* Suporte a no mínimo 500 usuários simultâneos
* Processamento de grandes volumes de dados sem perda de consistência

### 6.2. Requisitos de Confiabilidade

* Armazenamento preciso e sem corrupção
* Criptografia de todos os dados sensíveis
* Conformidade com normas de segurança e proteção de dados
* Backups automáticos a cada 24 horas

### 6.3. Requisitos de Usabilidade

* Interface intuitiva e fácil de usar
* Execução em ambiente web
* Linguagem simples e objetiva
* Layout responsivo (acesso em diferentes dispositivos)

### 6.4. Requisitos de Suporte

* Apoio da coordenação/professores
* Treinamento contínuo para uso de metodologias ágeis
* Equipe multidisciplinar (negócio, tecnologia, análise de dados)
* Plano de gestão da mudança organizacional
* Integração de dados via APIs

---

## 7. Marcos do Projeto

### 7.1. Cronograma de Lançamento

| Data  | Marco                                               |
| ----- | --------------------------------------------------- |
| 14/08 | Reunião de Kickoff                                  |
| 15/09 | Mapa de Empatia e Definição de Personas             |
| 15/09 | Levantamento e Consolidação de Requisitos           |
| 15/09 | Protótipo de Baixa Fidelidade                       |
| 06/10 | Protótipo de Navegação                              |
| 27/10 | Implementação funcional mínima da API               |
| 17/11 | Implementação da API para acesso à base de dados    |
| 24/11 | Testes com usuários (professor e graduandos)        |
| 08/12 | Entrega da versão com API e Documentação do Projeto |

### 7.2. Dependências

N/A

---

## 8. Histórico de Revisões

| Versão | Autor   | Data       |
| ------ | ------- | ---------- |
| 1.0    | Gerente | 15/09/2025 |

---
