# 📚 Miniguia de Estudos: Gestão da Qualidade e Controle de Não Conformidades (com NotebookLM)

## 🎯 Contexto e Objetivos
A análise e contenção de desvios operacionais são pilares fundamentais para a melhoria contínua de qualquer processo produtivo. Este caderno temático foi criado utilizando o NotebookLM do Google, com o intuito de organizar e sintetizar conhecimentos sobre as metodologias de garantia da qualidade, tratamento de Produto Não Conforme (PNC) e análise de causa raiz. 

**Objetivos de Estudo:**
1. Consolidar conceitos práticos de ferramentas da qualidade (Ishikawa, 5 Porquês, 5W2H).
2. Estruturar o passo a passo para a elaboração de Relatórios de Não Conformidade (RNC).
3. Entender a correlação entre Procedimentos Operacionais Padrão (POP), Instruções de Trabalho (IT) e a métrica de First Pass Yield (FPY).

---

## 🗂️ Curadoria de Fontes
Para alimentar a inteligência do NotebookLM, selecionei os seguintes materiais abertos e artigos técnicos de referência na área:

1. **Guia Prático da Qualidade:** Artigo sobre a aplicação do Diagrama de Ishikawa (Espinha de Peixe) e os 6Ms.
2. **Procedimentos de Ação Corretiva:** Material teórico sobre a metodologia dos 5 Porquês e elaboração de planos de ação (5W2H e Metas SMART).
3. **Gestão de Chão de Fábrica:** Documentação base sobre o controle e contenção de Produto Não Conforme (PNC) e bloqueio/desbloqueio de lotes.
*(Nota: No NotebookLM, essas fontes foram enviadas em formato PDF e Texto Livre para a base de conhecimento do projeto).*

---

## 🛠️ Engenharia de Prompts e "Cicatrizes" (Troubleshooting)

Durante a interação com o NotebookLM, testei diversas abordagens para extrair o melhor raciocínio analítico da ferramenta.

**Tentativa 1 (Prompt Genérico):**
> *"Como resolver um problema de qualidade na linha de produção?"*
* **Resultado:** A IA gerou uma resposta muito ampla e teórica, sem focar nas ferramentas de causa raiz, citando apenas a "importância de treinar a equipe".
* **Ajuste ("Cicatriz"):** Percebi que precisava direcionar o modelo para usar as fontes e frameworks específicos que eu havia feito upload.

**Tentativa 2 (Prompt Estratégico - Sucesso):**
> *"Com base nas fontes, aja como um Técnico de Qualidade de Produto Final. Uma não conformidade de dimensional foi detectada. Crie um roteiro relacionando o uso do Diagrama de Ishikawa (focado nos 6Ms) em conjunto com a técnica dos 5 Porquês para encontrar a causa raiz desse desvio."*
* **Resultado:** A IA foi cirúrgica. Ela estruturou a resposta listando primeiro as prováveis causas (Máquina, Mão de Obra, Método, etc.) e depois aplicou os "Porquês" em cima da causa mais provável, entregando uma análise prática e aplicável para o preenchimento de um RNC.

---

## 🚀 Miniguia de Estudo (Entrega Final)

### 1. Resumos Estruturados
* **Contenção e RNC:** Quando um desvio é detectado, a primeira etapa é a contenção (bloqueio do produto/lote) para evitar que chegue ao cliente. Em seguida, abre-se um Relatório de Não Conformidade (RNC) documentando o que ocorreu.
* **Análise de Causa Raiz:** Utiliza-se o **Diagrama de Ishikawa** para mapear todas as variáveis possíveis (os 6Ms) que causaram a falha. Após identificar a causa mais provável, aplica-se os **5 Porquês** para aprofundar até o motivo fundamental do erro.
* **Plano de Ação:** Com a causa raiz definida, utiliza-se a matriz **5W2H** (What, Why, Where, When, Who, How, How much) para desenhar um plano de ação e evitar a reincidência, sempre estipulando metas **SMART** (Específicas, Mensuráveis, Alcançáveis, Relevantes e Temporais).

### 2. Glossário
* **PNC (Produto Não Conforme):** Material ou produto que não atende aos requisitos ou especificações predefinidas.
* **RNC (Relatório de Não Conformidade):** Documento formal que registra o desvio encontrado e acompanha o processo de resolução.
* **FPY (First Pass Yield):** Métrica que indica a porcentagem de produtos fabricados corretamente na primeira vez, sem retrabalho ou sucata.
* **POP (Procedimento Operacional Padrão) / IT (Instrução de Trabalho):** Documentos que padronizam a execução das tarefas, garantindo repetibilidade e minimizando desvios de "Método".
* **Os 6Ms (Ishikawa):** Máquina, Material, Mão de Obra, Meio Ambiente, Método e Medida.

### 3. Conjunto de Prompts Reutilizáveis
Caso eu precise revisar esses conceitos futuramente, já deixo os seguintes prompts documentados para inserir no NotebookLM:
* 💡 *"Resuma os passos necessários para bloquear um lote não conforme e as etapas para realizar a sua liberação segura, com base nas fontes anexadas."*
* 💡 *"Gere um simulado com 3 questões discursivas sobre a aplicação do ciclo 5W2H na tratativa de um RNC."*
* 💡 *"Quais são as principais diferenças entre o escopo de um POP e de uma IT no controle de chão de fábrica?"*
