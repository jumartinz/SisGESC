# AraraAzulEDU - Gestão Escolar e Acadêmica 
Projeto acaêmico desenvolvido na disciplina **Banco de Dados** voltado para escolar de **Ensino Fundamental I (1º ao 5º ano)** e II **(6º ao 9º ano)** e **Ensino Médio (1º ao 3º ano)**

# Objetivo
O nosso SisGESC tem como objetivo implementar o **ERP (Enterprise Resource Planning)** para melhoria da gestão administrativa de uma escola de ensino básico.
Além da mogelagem tradicional de banco de dados, o projeto também explora a evolução dos dados desde o nível operacional, administrativo, financeiro, até a geração de analises automáticas de modelos.

# Arquitetura do Projeto
**Estrutura e Evolução dos Dados**
O projeto foi arquitetado para gerenciar a jornada dos dados em três camadas distintas, indo desde a coleta cotidiana até a gereção de inteligencia estratégica.

**1. Camada operacional (OLTP - On-line Transaction Processing)**
Nesta estapa inicial, o sistema foca na **integridade a agilidade** do proxessamento de transações diárias. É onde ocorre a captura granular de eventos escolares:
- **Gestão Administrativa:** Cadastro completo do *corpo docente/funcionários* e monitoramento de ponto.
- **Gestão Acadêmica:** Controle de frequência, *registro de presença* e *lancamento de notas*.
- **Gestão Financeira:** Processamento imediato de mensalidade e recebimentos.

**2. Camada Analítica (OLAP - On-line Analytical Processing)**
Aqui, os dados brutos são consolidados para apoiar a **tomada de decisão gerencial**. O foco é transformar registros isolados em indicadores de desempenho (KPIs):
- **Análise de Performance:** Monitoramento das médias por matéria e engajamento em atividades extras.
- **Saúde Financeira:** Visualização da taxa de inadimplência e apuração dos custo operacional real.
- **Frequência Agregada:** Visão macro da assiduidade escolar para identificar padrões de comportamento.

**3. Camada de Inteligencia (IA - Análise Preditiva)**
O nível mais avançado do sitema utiliza o histórico armazenado para **antecipar cenários**. O objetivo é agir preventivamente através de modelos estatísticos e algorítimicos:
- **Mitigação de Riscos:** Identificação precoce de probabilidade de evasão e previsão de falhas nos pagamentos (inadimplência).
- **Suporte Pedagógico:** Detecção automática de alunos com tendência a baixo rendimento escolar.
- **Planejamento de Recursos:** Estimativa da demanda futura para otimização de infraestrutura e atividades complementares.

# Estrutura Funcional do Sitema (Arquitetura de Módulos)
O AraraAzulEdu é composto por três pilares modulares que integram todas as verticais de uma instituição de ensino fundamental e médio, garantindo a fluidez da informação entre o pedagógico, o financeiro e o administrativo.

**1. Módulo Acadêmico: Inteligência Pedagógica**
Focado na gestão do ciclo de vida estudantil e na organização da estrutura de ensino para o *Ensino Fundamental I e II e Ensino Médio*
- **Gestão de Entidades:** Centraliza o controle de Alunos, Professores, Turmas e Disciplinas, segmentados do 1º ao 5º ano.
- **Fluxo Escolar:** Gerencia o processo de Matrículas e a aplicação de Avaliações.
- **Persistência de Dados:** Armazena registros de Frequência, composição de Notas, Histórico Escolar e o engajamento em atividades extracurriculares.

**2. Módulo Financeiro: Saúde e Sustentabilidade**
Responsável por toda a operacionalização econômica, integrando a receita acadêmica com as obrigações administrativas.
- **Receita Estudantil:** Controle rigoroso de Mensalidades (parcelas, vencimentos e status de liquidação) e monitoramento de inadimplência.
- **Comercialização e Eventos:** Gestão de custos e cobranças de uniformes, materiais didáticos e eventos institucionais (como Formaturas, Festas Temáticas e Passeios Pedagógicos).
- **Integração com RH:** Processamento da Folha de Pagamento, incluindo PLR, Benefícios e transferências bancárias.

**3. Módulo de Recursos Humanos: Gestão de Talentos**
Dedicado à administração do capital humano, com foco especial nas competências diversificadas exigidas no ambiente escolar.
- **Ciclo do Colaborador:** Registro de dados cadastrais, documentação legal, definição de Cargos/Funções e gestão de Férias.
- **Controle Operacional:** Monitoramento de Jornada de Trabalho, Registro de Ponto e gestão de ausências.
- **Diferencial Pedagógico:** Mapeamento de habilidades extras dos funcionários para suporte a atividades especializadas *(como Ballet, Robótica, Música, Jogos interdisciplinares)*, característica essencial para o atendimento integral no *Fundamental I.*

# Modelagem e Arquitetura de Processos
A estruturação do sistema é fundamentada no mapeamento detalhado dos fluxos de trabalho da gestão escolar, utilizando a metodologia de fluxogramas de processos. Essa abordagem garante que a arquitetura do banco de dados suporte fielmente as operações do mundo real.

**Escopo da Modelagem**
Os fluxos foram desenhados para cobrir as jornadas críticas da instituição, incluindo:
- **Ciclo de Vida do Aluno:** Engloba desde o fluxo de Matrícula até a Gestão Acadêmica contínua durante o ano letivo.
- **Operações Financeiras:** Mapeamento do Controle de Mensalidades, recebimentos e fluxos de caixa.
- **Logística Institucional:** Planejamento e execução da Organização de Eventos Escolares.
- **Administração de Capital Humano:** Abrange fluxogramas de Gestão de Funcionários, além do monitoramento de *Férias e Ausências*.

**Ferramental Técnico**
Para a construção dos modelos visuais, está sendo utilizada a ferramenta **Draw.io**, permitindo uma documentação clara, padronizada e de fácil manutenção para a evolução do ERP.
