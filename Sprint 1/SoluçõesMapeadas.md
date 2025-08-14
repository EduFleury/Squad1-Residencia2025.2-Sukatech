# Documento do Dia 2: Esboço e Geração de Hipóteses

**Projeto:** Sistema de Gestão de Informações do Programa Sukatech
**Data:** 15 de agosto de 2025

## 1. Lista de Inspirações de Soluções Existentes

Para o desenvolvimento do Sistema Sukatech, podemos nos inspirar em soluções consolidadas no mercado, adaptando suas melhores práticas ao nosso contexto.

* **Sistemas de Gestão de Resíduos (Ex: VG Resíduos):**
    * **Inspiração:** Funcionalidades para o **Eixo Ambiental**. Podemos nos inspirar em como essas plataformas rastreiam a coleta, geram manifestos de transporte e criam relatórios de sustentabilidade. Isso ajuda a estruturar o registro da logística reversa.

* **Plataformas de Gestão de Impacto Social (Ex: Prosas, Bússola Social):**
    * **Inspiração:** Funcionalidades para os **Eixos Social e Educacional**. Essas plataformas são excelentes em cadastrar beneficiários, gerenciar turmas, registrar participação e emitir relatórios de impacto social. O modelo de gestão de cursos e doações pode ser adaptado.

* **Ferramentas de Business Intelligence (BI) (Ex: Power BI, Google Looker Studio):**
    * **Inspiração:** Para o **Dashboard do Gestor Público**. A capacidade de criar painéis visuais, com gráficos interativos, filtros dinâmicos e KPIs em destaque é fundamental para dar suporte à tomada de decisão.

* **Portais de Transparência Governamentais:**
    * **Inspiração:** Para a **Página Pública** do sistema. O foco é na clareza, objetividade e facilidade de acesso à informação para o cidadão, mostrando como os recursos públicos estão sendo utilizados e qual o impacto gerado.

## 2. Esboços de Hipóteses de Soluções

A partir do problema, formulamos três hipóteses centrais que podem ser testadas.

### Hipótese 1: O Dashboard Gerencial Centralizado

* **Acreditamos que**, ao fornecer um dashboard visual e interativo para a SECTI, **conseguiremos** melhorar a capacidade de tomada de decisão e o monitoramento eficiente do programa.
* **Esboço da Solução:**
    * Uma tela principal com três "cards" de destaque, um para cada eixo do programa:
        1.  **Ambiental:** Total de resíduos coletados (kg).
        2.  **Social:** Total de computadores doados.
        3.  **Educacional:** Total de alunos certificados.
    * Gráficos de barras ou linhas mostrando a evolução desses indicadores ao longo do tempo (mensal/anual).
    * Uma tabela simples com os últimos registros inseridos pelo parceiro.

### Hipótese 2: O Módulo de Inserção de Dados Simplificado

* **Acreditamos que**, ao criar um formulário web simples e unificado para o parceiro privado, **aumentaremos** a consistência, a agilidade e a adesão no registro dos dados operacionais.
* **Esboço da Solução:**
    * Uma área de acesso restrito para o parceiro.
    * Um único botão "Adicionar Registro" que abre um formulário com campos claros e objetivos, como: "Tipo de Registro" (Coleta, Doação, Certificação), "Data", "Quantidade" e um campo de "Descrição".

### Hipótese 3: O Portal de Transparência Automatizado

* **Acreditamos que**, ao gerar uma página pública com os principais resultados do programa de forma automática a partir dos dados operacionais, **aumentaremos** a transparência e a credibilidade do Sukatech perante a sociedade.
* **Esboço da Solução:**
    * Uma página web pública, com a identidade visual do programa.
    * Exibição dos mesmos KPIs do dashboard gerencial, mas de forma consolidada e totalizada (Ex: "Desde o início do programa, já recondicionamos X toneladas de equipamentos").
    * Uma breve explicação sobre os objetivos do programa.

## 3. Storyboard da Solução Proposta

Para contextualizar a experiência do usuário, o storyboard abaixo ilustra a jornada principal, validando as **Hipóteses 1 e 2** de forma integrada.

**Título:** Do Registro à Análise: O Fluxo de Dados do Sukatech

* **Cena 1: A Necessidade**
    * **Ator:** Vilmar Simion (Parceiro Privado).
    * **Contexto:** Ao final de uma semana produtiva, Vilmar está em seu escritório com uma pilha de anotações: lotes de equipamentos coletados de secretarias, computadores doados para um telecentro e a lista de formandos da última turma.
    * **Ação:** Ele precisa reportar essas atividades para a SECTI.

* **Cena 2: O Registro Rápido**
    * **Ator:** Vilmar Simion.
    * **Contexto:** Ele acessa o novo "Sistema Sukatech" e entra na área do parceiro.
    * **Ação:** Ele clica em "Adicionar Registro" e preenche rapidamente os formulários: 150 kg de resíduos coletados, 20 computadores doados, 15 alunos certificados. O sistema é intuitivo e leva poucos minutos.

* **Cena 3: A Análise Imediata**
    * **Ator:** Thiago Angelino (Gestor SECTI).
    * **Contexto:** Em seu escritório, Thiago abre o dashboard do Sukatech para preparar uma reunião.
    * **Ação:** Ele vê os números nos cards principais já atualizados com os dados que Vilmar acabou de inserir. O gráfico de "Alunos Certificados" mostra que a meta do mês foi atingida.

* **Cena 4: Tomada de Decisão**
    * **Ator:** Thiago Angelino.
    * **Contexto:** Durante a reunião, Thiago projeta o dashboard.
    * **Ação:** Ele usa os dados confiáveis para discutir o desempenho do programa e propor a expansão das turmas de capacitação para o próximo trimestre, baseando sua decisão em resultados concretos.

* **Cena 5: Transparência para a Sociedade**
    * **Ator:** Um cidadão interessado.
    * **Contexto:** O cidadão ouve sobre o programa e acessa o site da SECTI.
    * **Ação:** Ele encontra o link para o portal de transparência do Sukatech e vê o número total de computadores doados à comunidade e o total de pessoas capacitadas, confirmando o impacto positivo da iniciativa.

## 4. Critérios de Decisão para Prototipagem

Para decidir qual hipótese ou combinação de hipóteses prototipar na próxima fase, usaremos os seguintes critérios ponderados, alinhados aos objetivos do projeto.

| Critério | Descrição | Peso |
| :--- | :--- | :--- |
| **Impacto no Problema Central** | A solução resolve diretamente a ineficiência e a falta de credibilidade no fluxo de dados entre parceiro e gestão? | 40% |
| **Viabilidade Técnica (curto prazo)** | É possível construir um protótipo funcional desta solução no tempo disponível para o projeto de residência? | 30% |
| **Alinhamento com Critérios de Aceitação** | A solução atende diretamente à necessidade de exibir indicadores dos três eixos principais (ambiental, social, educacional)? | 20% |
| **Potencial de Aprendizado** | O teste desta solução nos trará o maior aprendizado sobre os riscos mais críticos (ex: a adoção pelo parceiro)? | 10% |

**Decisão Preliminar:** A combinação das **Hipóteses 1 e 2** (Dashboard + Módulo de Inserção), conforme ilustrado no storyboard, parece ser a mais indicada para a prototipagem, pois possui a maior pontuação combinada nestes critérios, abordando o núcleo do problema de forma viável e alinhada aos requisitos.
