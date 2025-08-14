# Documento do Dia 1: Mapeamento e Definição do Foco

**Projeto:** Sistema de Gestão de Informações do Programa Sukatech
**Data:** 14 de agosto de 2025

## 1. Mapa do Desafio

O objetivo deste mapa é consolidar o entendimento do problema, identificar as partes interessadas e visualizar a jornada principal do usuário em relação ao desafio proposto.

### Descrição do Problema

O Programa Sukatech, focado na logística reversa e economia circular de eletroeletrônicos, carece de um sistema de informação centralizado. A ausência de uma ferramenta unificada dificulta a integração de dados, a medição do impacto da política pública e a transparência no uso de recursos. O fluxo de informações entre a administração pública (SECTI) e o parceiro privado executor é ineficiente, impactando a credibilidade e a agilidade na análise de resultados para a tomada de decisões.

### Atores Envolvidos

| Ator | Organização/Papel | Interesse / Relação com o Desafio |
| :--- | :--- | :--- |
| **Thiago Angelino Martins da Silva** | SECTI / Gerente de Inovação para Economia Circular | Responsável pela gestão da política pública. Necessita de dados confiáveis para tomar decisões, medir o alcance e gerar relatórios sobre o impacto do programa. |
| **Vilmar Simion** | Programando o Futuro (OSC) / Ponto Focal Técnico | Parceiro privado responsável pela execução do programa e por alimentar o sistema com os dados das operações de coleta, recondicionamento, doação e capacitação. |
| **Administração Pública e Setor Privado** | Doadores de Equipamentos | Fontes primárias dos materiais e bens de informática que entram no ciclo do programa. |
| **População e Entidades Sociais** | Beneficiários Finais | Recebem os computadores recondicionados (pontos de inclusão digital) e participam das capacitações profissionais, sendo o alvo final do impacto social e educacional do programa. |

### Fluxo do Usuário (Jornada de Dados)

O fluxo abaixo descreve a jornada da informação dentro do ecossistema do programa, desde a coleta até a análise de impacto.

**`Parceiro Privado (Executor)`** -> **`Sistema Sukatech (Ferramenta)`** -> **`Gestor Público (SECTI)`**

1.  **Entrada de Material:** O Parceiro Privado coleta resíduos eletrônicos da administração pública ou do setor privado.
2.  **Registro de Dados Operacionais:** O Parceiro Privado acessa o sistema e insere os dados sobre a coleta (eixo ambiental), o recondicionamento, as doações realizadas (eixo social) e os alunos certificados nos cursos (eixo educacional).
3.  **Processamento e Armazenamento:** O sistema centraliza e armazena essas informações de forma segura, em conformidade com a LGPD.
4.  **Análise e Tomada de Decisão:** O Gestor Público (SECTI) acessa o sistema para visualizar dashboards, consultar indicadores de desempenho e gerar relatórios detalhados.
5.  **Transparência:** Os dados consolidados sobre o impacto ambiental, social e educacional são utilizados para medir o alcance da política e dar transparência sobre os resultados.

## 2. Perguntas-Chave

Questões que devem ser respondidas ao longo do projeto para garantir que a solução atenda às necessidades.

* **Sobre o Usuário (Parceiro):** Como podemos projetar uma interface que seja simples e rápida para o parceiro privado registrar as informações, garantindo alta adesão e qualidade dos dados?
* **Sobre os Indicadores:** Quais são os indicadores de desempenho (KPIs) mais críticos para cada um dos três eixos (ambiental, social, educacional) que precisam ser exibidos no sistema?
* **Sobre a Gestão (SECTI):** De que forma os dados devem ser visualizados (gráficos, mapas, relatórios) para apoiar efetivamente a tomada de decisão estratégica?
* **Sobre a Tecnologia:** Qual a arquitetura de sistema mais adequada para garantir desempenho, segurança dos dados públicos e escalabilidade futura?
* **Sobre o Sucesso:** Como o sistema pode provar seu valor ao gerar relatórios que meçam de forma clara e confiável os impactos ambiental, educacional e social do programa?

## 3. Definição Clara do Objetivo

Com base na EDT, o objetivo principal do projeto é:

**Desenvolver um sistema de informação que integre todos os dados do Programa Sukatech para dar credibilidade e eficiência ao fluxo de informações entre o parceiro privado e a administração pública. A ferramenta deve ser capaz de gerar relatórios detalhados, medir o alcance da política pública e aumentar a transparência sobre os impactos ambiental, social e educacional gerados, em conformidade com a LGPD.**

## 4. Riscos e Obstáculos

| Risco / Obstáculo | Descrição | Mitigação Proposta |
| :--- | :--- | :--- |
| **Baixa Adoção pelo Usuário** | O parceiro privado, responsável por alimentar o sistema, pode apresentar resistência ou dificuldade no uso da nova ferramenta, resultando em dados desatualizados ou incompletos. | Envolver o parceiro privado (Vilmar Simion) desde as fases iniciais de prototipação para garantir que a ferramenta seja útil e fácil de usar. |
| **Qualidade e Integridade dos Dados** | A precisão dos indicadores e relatórios depende 100% da qualidade dos dados inseridos. Erros de digitação ou falta de padronização podem gerar informações incorretas. | Implementar validações de dados nos formulários, usar listas de seleção (dropdowns) sempre que possível e criar um manual de uso claro. |
| **Manutenção da Conformidade (LGPD)** | Garantir a proteção contínua dos dados públicos conforme a legislação é um desafio técnico e processual. | Adotar as melhores práticas de segurança desde o início do desenvolvimento, como controle de acesso baseado em função (RBAC) e criptografia de dados. |
| **Sustentabilidade Técnica** | A definição da infraestrutura de hospedagem e a garantia de manutenção e evolução do sistema a longo prazo podem ser um obstáculo. | Iniciar a discussão sobre a infraestrutura (nuvem governamental, etc.) e o plano de sustentação do sistema com a equipe técnica da UFG/SECTI. |

## 5. Pesquisas e Insights Relevantes

### Benchmarking (Análise de Similares)

* **VG Resíduos:** Software brasileiro para gestão de resíduos, incluindo logística reversa. Pode oferecer insights sobre funcionalidades de controle de transporte, manifesto e geração de relatórios de sustentabilidade.
* **Plataformas de Gestão de Impacto Social:** Sistemas como o "Prosas" e o "Bússola Social" são usados por OSCs para gerenciar projetos e monitorar indicadores de impacto. A análise de suas funcionalidades de gestão de beneficiários e relatórios de impacto pode ser útil.
* **Ação Necessária:** Realizar uma análise aprofundada dessas e outras plataformas para identificar padrões de interface, funcionalidades-chave e modelos de relatórios que possam ser adaptados ao contexto do Sukatech.

### Dados e Insights dos Usuários (Baseado na EDT)

* **Necessidade do Gestor:** A principal dor do gestor é a falta de uma fonte de dados confiável para tomar decisões e medir o desempenho da política. A solução precisa ser analítica e direta.
* **Papel do Parceiro:** O parceiro é o "operador da ferramenta". Isso significa que a usabilidade na entrada de dados é tão crítica quanto a visualização dos mesmos.
* **Critérios de Aceitação:** O sucesso do projeto está diretamente ligado à capacidade da ferramenta de exibir os indicadores dos eixos ambiental (coleta), social (doação) e educacional (certificados). Este é o requisito fundamental e deve ser o foco principal do desenvolvimento inicial.
