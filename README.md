# projeto-aplicado-4-sem2-2025

``Introdução`` \
  A educação é um pilar fundamental para o desenvolvimento social e econômico de uma nação. No Brasil, um país de dimensões continentais e profundas desigualdades, a análise dos indicadores de fluxo escolar é crucial para compreender a eficácia do sistema de ensino. Indicadores como as taxas de promoção, repetência e evasão servem como um termômetro da qualidade e da equidade educacional, revelando os desafios enfrentados por estudantes em sua trajetória acadêmica. Logo, essa contextualização é importante para ligar ao principal objetivo deste estudo: entender os motivos da repetência e evasão estudantil, ligando os dados expostos aos principais motivos do abandono escolar mapeados pelo Instituto Ayrton Senna (criminalidade, resultados econômicos e saúde mental).\
  Neste contexto, o presente projeto propõe investigar o cenário do fluxo escolar no Brasil, utilizando dados oficiais para identificar padrões, desigualdades e os principais gargalos no sistema de ensino fundamental e médio. Principalmente, entender o que ocorre na etapa de ensino médio no Brasil, que tem a maior taxa de repetência (3,9%) e evasão (5,9%) de estudantes dentre todas as etapas do estudo.

``Pipeline de Solução``\
    1. Coletar os dados através do Instituto Nacional de Estudos e Pesquisas Educacionais Anísio Teixeira (INEP) e Ministério da Educação.\
    2. Pré processamento e limpeza dos dados coletados.\
    3. Análise dos dados obtidos.\
    4. Modelagem a partir da análise dos dados.

    "Cronograma"
    # 📅 Cronograma Acadêmico – Projeto Fluxo Escolar no Brasil

## Etapas, Datas e Entregas

### Definição do Projeto e Equipe  
- **Data de Entrega:** 29/ago  
- **Checkpoint:** 13/ago  
- **Atividades:**  
  - Definição do tema (evasão e repetência no Brasil).  
  - Definição da equipe.  
  - Redação da introdução: contexto da educação no Brasil e relevância social.  
  - Formulação do objetivo principal.  
  - Escolha e descrição inicial da base de dados (INEP/MEC).  
  - Seleção de referências (Instituto Ayrton Senna, MEC, FGV).  
- **Produtos Esperados:**  
  - Documento inicial com: Título, Introdução, Justificativa, Objetivo, Descrição da base de dados.  

---

### Referencial Teórico e Cronograma  
- **Data de Entrega:** 26/set  
- **Checkpoint:** 10/set  
- **Atividades:**  
  - Levantamento e análise de trabalhos correlacionados (fluxo escolar, evasão, desigualdade educacional).  
  - Definição dos conceitos teóricos que embasam o estudo.  
  - Construção do pipeline da solução (coleta → limpeza → análise → modelagem → interpretação).  
  - Elaboração do cronograma detalhado do projeto.  
- **Produtos Esperados:**  
  - Documento com: Referencial Teórico, Pipeline da Solução e Cronograma completo.  

---

### Implementação Parcial  
- **Data de Entrega:** 31/out  
- **Checkpoint:** 08/out  
- **Atividades:**  
  - Coleta dos dados do INEP/MEC.  
  - Pré-processamento: tratamento de dados faltantes, duplicados e inconsistentes.  
  - Análise exploratória inicial: estatísticas e visualizações.  
  - Teste de um modelo de regressão ou classificação (evasão).  
  - Revisão e atualização do cronograma, se necessário.  
- **Produtos Esperados:**  
  - Notebook executável com: Análise Exploratória, Pré-processamento, Modelo Base inicial, Cronograma atualizado.  

---

### Implementação Final e Entrega  
- **Data de Entrega:** 28/nov  
- **Checkpoint:** 12/nov  
- **Atividades:**  
  - Refinamento da análise e modelagem (comparação de modelos estatísticos ou de ML).  
  - Interpretação e discussão dos resultados.  
  - Redação final do artigo em formato acadêmico.  
  - Preparação da apresentação (vídeo de 5–10 min).  
  - Organização e repositório no GitHub com todo o material.  
- **Produtos Esperados:**

    
``Referencial Teórico``\
Este estudo ancora-se em três frentes. Primeiro, no arcabouço de Tinto, que explica a permanência escolar pela integração acadêmica e social: quando o aluno se sente apoiado academicamente e pertencente ao ambiente, sua chance de continuidade aumenta. Usamos Tinto para justificar variáveis de engajamento/pertencimento e práticas escolares (tutoria, clima escolar) no modelo. Em complemento, a revisão de Rumberger sobre 25 anos de pesquisas mostra que a evasão é um processo cumulativo de riscos (baixo desempenho, vulnerabilidade socioeconômica, clima/segurança escolar e fatores do território). Adotamos Rumberger para estruturar a análise multifatorial (econômica, criminalidade/violência e suporte psicossocial) e para selecionar controles em diferentes níveis (indivíduo, família, escola e território). Para o contexto brasileiro, utilizamos estudos do IMDS, que associam evasão a renda familiar, escolaridade dos pais e vulnerabilidades territoriais, reforçando a pertinência de políticas de acolhimento socioemocional e busca ativa no recorte nacional. Esses achados orientam a escolha de variáveis de contexto e de políticas escolares a testar. Por fim, as estatísticas recentes do MEC/INEP situam o ensino médio como etapa crítica (repetência 3,9%; evasão 5,9%), o que justifica o foco empírico deste trabalho nesta fase. Esses números servem como linha de base para avaliar a magnitude dos efeitos estimados. 

``Referências``\
https://agenciagov.ebc.com.br/noticias/202402/ensino-medio-tem-maior-taxa-de-evasao-da-educacao-basica
https://www.cps.fgv.br/ibrecps/rede/finais/Etapa3-Pesq_MotivacoesEscolares_sumario_principal_anexo-Andre_FIM.pdf
https://institutoayrtonsenna.org.br/abandono-escolar/
https://files.eric.ed.gov/fulltext/ED501335.pdf (Tinto — integração acadêmica e social)\
https://eric.ed.gov/?id=ED520179 (síntese sobre a teoria de Tinto)\
https://www.issuelab.org/resources/11658/11658.pdf (Rumberger — revisão de 25 anos sobre evasão)\
https://imdsbrasil.org/doc/ImdsA002-2022-CausasConsequ%C3%AAnciasAbandonoEvas%C3%A3oEscolar.pdf (IMDS — causas e consequências no Brasil)\
https://www.gov.br/inep/pt-br/centrais-de-conteudo/acervo-linha-editorial/publicacoes-institucionais/estatisticas-e-indicadores-educacionais/dicionario-de-indicadores-educacionais-2013-formulas-de-calculo (INEP — dicionário de indicadores)
