# miniguia-estudos-notebooklm-saude
Projeto prático do desafio DIO: Caderno temático sobre Saúde e Alimentação Saudável utilizando o Google NotebookLM como ferramenta de aprendizagem ativa.
# 🥗 Miniguia de Estudos: Saúde, Alimentação Saudável e Nutrição com NotebookLM

<p align="center">
  <img src="https://img.shields.io/badge/NotebookLM-Google-blue?style=for-the-badge&logo=google" alt="NotebookLM" />
  <img src="https://img.shields.io/badge/Aprendizagem%20Ativa-IA%20Generativa-green?style=for-the-badge" alt="Aprendizagem Ativa" />
  <img src="https://img.shields.io/badge/DIO-Desafio%20de%20Projeto-orange?style=for-the-badge" alt="DIO" />
  <img src="https://img.shields.io/badge/Licença-MIT-lightgrey?style=for-the-badge" alt="Licença" />
</p>

> **Projeto Prático – Formação DIO**  
> **Autor:** Wellington  
> Este repositório contém a documentação completa da criação de um **Caderno Temático no NotebookLM**, combinando curadoria de fontes oficiais sobre nutrição, engenharia de prompts, resolução de problemas (*troubleshooting*) e a consolidação de um miniguia de estudos sobre **Saúde, Nutrição e Alimentação Consciente**.

---

## 📌 1. Contexto e Objetivos de Estudo

### Contexto
A busca por uma alimentação saudável é cercada de desinformação, "dietas milagrosas" e mitos nutricionais espalhados pela internet. Para construir um aprendizado baseado em evidências científicas, utilizei o **NotebookLM** como copiloto de IA com ancoragem (*grounding*) exclusiva em guias e manuais oficiais de saúde pública (como o *Guia Alimentar para a População Brasileira* do Ministério da Saúde). O objetivo foi criar uma base confiável de conhecimento para entender os princípios de uma alimentação equilibrada e a prevenção de doenças por meio da nutrição.

### Objetivos de Aprendizagem
- [x] Compreender a **Classificação NOVA** dos alimentos (In natura, Processados e Ultraprocessados).
- [x] Entender a função dos macronutrientes (proteínas, carboidratos, gorduras) e micronutrientes no organismo.
- [x] Desenvolver capacidade crítica para leitura de rótulos nutricionais e identificação de ingredientes nocivos.
- [x] Utilizar a Inteligência Artificial como ferramenta de **estudo ativo**, criando resumos, quizzes interativos e um glossário nutricional.

---

## 📚 2. Curadoria de Fontes

Para garantir a total precisão e confiabilidade das respostas geradas pela IA, foram selecionadas **4 fontes oficiais e científicas abertas**:

| # | Título da Fonte | Instituição / Autor | Formato | Link / Acesso |
|---|------------------|---------------------|---------|---------------|
| **1** | Guia Alimentar para a População Brasileira | Ministério da Saúde (Brasil) | PDF | [Acessar MS](https://www.gov.br/saude) |
| **2** | Diretrizes de Nutrição e Alimentação | Organização Mundial da Saúde (OMS / OPAS) | PDF / Web | [Acessar OMS](https://www.who.int/) |
| **3** | Manual de Promotores da Alimentação Saudável | Fiocruz / SUS | PDF | [Acessar Fiocruz](https://www.fiocruz.br/) |
| **4** | Manual de Rotulagem Nutricional | Anvisa | PDF / Web | [Acessar Anvisa](https://www.gov.br/anvisa) |

> **Nota:** Todos os documentos foram importados diretamente no caderno do NotebookLM, garantindo que qualquer resposta fosse baseada estritamente nesses materiais de referência.

---

## 🧪 3. Engenharia de Prompts & "Cicatrizes" (Troubleshooting)

Abaixo documentam-se os testes de prompts realizados durante o estudo, evidenciando as melhorias e aprendizados no uso da ferramenta.

### Iterações de Prompts

#### 🔴 Teste 1: Prompt Vago (Resultado Insatisfatório)
* **Prompt Enviado:**  
  > *"O que eu devo comer no dia a dia para ter uma vida saudável?"*
* **Problema Encontrado:** O modelo gerou um cardápio genérico com restrições e calorias sem considerar o contexto individual ou as recomendações das fontes do caderno.
* **Cicatriz / Aprendizado:** Prompts abertos levam a IA a agir como "nutricionista prescritivo", o que não é o foco do estudo ativo com fontes oficiais.

#### 🟡 Teste 2: Prompt Estruturado (Melhoria)
* **Prompt Enviado:**  
  > *"Com base no Guia Alimentar do Ministério da Saúde presente no caderno, qual é a recomendação principal sobre o consumo de alimentos in natura versus ultraprocessados?"*
* **Resultado:** O NotebookLM explicou corretamente a regra de ouro: *"Fazer de alimentos in natura ou minimamente processados a base da alimentação"*, citando trechos diretos da fonte.

#### 🟢 Teste 3: Prompt Avançado com Papel e Formatação (Resultado Ideal "Nota 10")
* **Prompt Enviado:**  
  > *"Atue como um educador em saúde. Com base nas fontes do caderno, crie uma tabela comparativa entre: Alimentos In Natura, Alimentos Processados e Alimentos Ultraprocessados. A tabela deve conter: Definição, Exemplos práticos do cotidiano e Impacto na saúde. Ao final, cite quais páginas/seções das fontes justificam essas informações."*
* **Resultado:** Gerou uma tabela estruturada, didática e com citações exatas das páginas do Guia Alimentar do Ministério da Saúde.

---

### 🔧 Diário de Troubleshooting (Resolução de Problemas)

| Desafio Encontrado | Causa Raiz | Solução Aplicada |
|-------------------|------------|------------------|
| A IA gerou termos muito acadêmicos e difíceis de memorizar. | O manual da Anvisa possui linguagem técnica e regulatória. | Incluída a instrução no prompt: *"Explique o conceito técnico usando uma analogia simples e cotidiana"*. |
| O modelo tentou prescrever dietas restritivas (ex: low-carb). | Influência de dados externos do treinamento geral da IA. | Reforçada a instrução: *"Responda utilizando EXCLUSIVAMENTE o conteúdo das fontes anexadas, focando em reeducação e saúde pública"*. |

---

## 📖 4. Miniguia de Estudo (Entrega Final)

### 🧩 Resumos Estruturados do Assunto

#### 1. A Classificação NOVA dos Alimentos
O *Guia Alimentar para a População Brasileira* divide os alimentos em 4 categorias de acordo com o processamento:
* **In Natura / Minimamente Processados:** Alimentos obtidos diretamente de plantas ou animais sem alterações profundas (ex: frutas, legumes, arroz, feijão, ovos, leite).
* **Ingredientes Culinários:** Substâncias extraídas da natureza usadas para temperar e cozinhar (ex: óleo, azeite, sal, açúcar).
* **Alimentos Processados:** Produtos fabricados com a adição de sal, açúcar ou óleo a um alimento in natura para aumentar a durabilidade (ex: queijos, pães artesanais, conservas).
* **Alimentos Ultraprocessados:** Formulações industriais feitas com aditivos, corantes, aromatizantes e pouco ou nenhum alimento inteiro (ex: refrigerantes, salgadinhos de pacote, macarrão instantâneo, biscoitos recheados). **Devem ser evitados.**

#### 2. Os Três Pilares da Alimentação Consciente
1. **Prioridade Visual e Nutritiva:** Pratos coloridos garantem diversidade de vitaminas e minerais.
2. **Ambiente e Atenção Plena:** Comer devagar, em ambientes apropriados e em boa companhia favorece a digestão e a saciedade.
3. **Leitura Crítica de Rótulos:** Quanto maior a lista de ingredientes (e quanto mais nomes desconhecidos houver nela), mais processado é o alimento.

---

### 📚 Glossário de Conceitos Fundamentais

* **In Natura:** Alimento em seu estado natural, sem ter sofrido alterações industriais após a colheita ou abate.
* **Ultraprocessado:** Alimento rico em aditivos químicos, gorduras hidrogenadas e açúcares sintéticos, com baixa densidade nutricional.
* **Macronutrientes:** Nutrientes necessários em grandes quantidades pelo organismo para gerar energia e construir tecidos (Carboidratos, Proteínas e Lipídios).
* **Micronutrientes:** Vitaminas e minerais essenciais em pequenas doses para o bom funcionamento metabólico e imunológico.
* **Densidade Nutritiva:** Quantidade de nutrientes essenciais que um alimento fornece em relação ao seu volume calórico.

---

### 🤖 Biblioteca de Prompts Reutilizáveis (Para Revisões Futuras)

Copie e cole estes prompts no NotebookLM para estudar este ou novos tópicos:

#### 1. Prompt de Síntese para Estudo Rápido
```text
Atue como um tutor em nutrição. Com base nas fontes do caderno, apresente um resumo em 5 tópicos essenciais sobre [INSERIR TÓPICO, ex: Leitura de Rótulos], indicando a fonte de cada afirmação.
