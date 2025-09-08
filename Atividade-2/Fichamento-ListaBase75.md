# Fichamento – Lista Base 75
**Título:** Can ChatGPT Repair Non-Order-Dependent Tests?  
**Autores:** Clinton Cao, Annibale Panichella, Sicco Verwer 
**Ano:** 2024  
**Veículo:** ACM  
**Fonte:** Lista Base (Artigo nº 75)  
**Link:** https://dl.acm.org/doi/pdf/10.1145/3643656.3643900  



## 1. Fichamento de Conteúdo
O artigo analisa o uso do ChatGPT como ferramenta de apoio na correção de testes instáveis, conhecidos como flaky tests, com foco naqueles que não dependem da ordem de execução. O problema abordado está no fato de que testes intermitentes prejudicam a confiabilidade do processo de QA e reduzem a confiança na automação, já que podem falhar ou passar sem que o código tenha sido alterado. O objetivo da pesquisa foi verificar se um modelo de linguagem de grande porte é capaz de identificar e reparar automaticamente esses testes, reduzindo o esforço manual. Para isso, os autores selecionaram um conjunto de testes instáveis de repositórios open-source e aplicaram o ChatGPT para sugerir reparos, avaliando a eficácia das correções. Os resultados mostraram que o modelo conseguiu reparar uma parte significativa dos casos, mas também apresentou limitações, como reparos incorretos ou a introdução de novos problemas em alguns cenários. A conclusão é que o ChatGPT pode ser usado como ferramenta complementar, acelerando a correção de testes, mas não substitui a revisão humana. Isso reforça a ideia de que, na migração de testes manuais para automatizados, os desafios não são apenas técnicos, mas também culturais, exigindo que as equipes aprendam a integrar soluções baseadas em IA de forma crítica e supervisionada.

---

## 2. Fichamento Bibliográfico

### 2.1 Conceitos
- Flaky Test: teste que apresenta resultados inconsistentes, mesmo sem alteração no código.  
- Non-Order-Dependent Test: teste que falha de forma intermitente, mas não devido à ordem de execução.  
- LLMs (Large Language Models): modelos de linguagem, como ChatGPT, aplicados para automação em QA.  

### 2.2 Ferramentas/Sistemas/Bibliotecas
- ChatGPT (OpenAI): usado como ferramenta de reparo automatizado de testes.  
- Repositórios GitHub: base de dados para extração dos flaky tests.  

### 2.3 Teorias/Métodos
- Estudo empírico: análise experimental sobre a eficácia do ChatGPT em corrigir testes.  
- Validação prática: comparação entre testes originais e reparados.  
- Análise qualitativa: classificação dos tipos de reparos bem-sucedidos e falhos.  

---

## 3. Fichamento de Citações
> “Test flakiness, especially order-dependent tests, is one of the major challenges in software quality assurance.”  
>  
> “Large Language Models, such as ChatGPT, show potential in repairing non-order-dependent flaky tests automatically.”  
>  
> “However, automation does not fully eliminate the need for developer oversight.”

---

## Relevância para o TCC
Este artigo é relevante porque:  
- Trata diretamente de automação de QA com apoio de IA.  
- Mostra desafios técnicos: IA ainda não é 100% confiável.  
- Aborda também desafios culturais: times de QA precisam aprender a integrar IA como suporte, e não substituição, no processo de migração de testes manuais.  
