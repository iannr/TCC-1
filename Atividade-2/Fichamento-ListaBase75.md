# Fichamento – Lista Base 75
**Título:** Can ChatGPT Repair Non-Order-Dependent Tests?  
**Autores:** Clinton Cao, Annibale Panichella, Sicco Verwer 
**Ano:** 2024  
**Veículo:** ACM  
**Fonte:** Lista Base (Artigo nº 75)  
**Link:** https://dl.acm.org/doi/pdf/10.1145/3643656.3643900  

---

## 1. Fichamento de Citações
> “Test flakiness, especially order-dependent tests, is one of the major challenges in software quality assurance.”  
>  
> “Large Language Models, such as ChatGPT, show potential in repairing non-order-dependent flaky tests automatically.”  
>  
> “However, automation does not fully eliminate the need for developer oversight.”

---

## 2. Fichamento de Conteúdo
O artigo avalia a capacidade do **ChatGPT** em **corrigir testes instáveis (flaky tests)**, com foco nos **não-dependentes de ordem**.  
- **Problema:** Testes *flaky* reduzem a confiabilidade e dificultam a automação, pois podem falhar ou passar de forma intermitente.  
- **Objetivo:** Explorar se LLMs conseguem reparar automaticamente esses testes.  
- **Metodologia:**  
  - Conjunto de testes instáveis extraídos de repositórios open-source.  
  - Aplicação do ChatGPT para sugerir reparos.  
  - Avaliação da efetividade e precisão das sugestões.  
- **Resultados:**  
  - ChatGPT conseguiu reparar **um número significativo** de casos.  
  - Em alguns casos, os reparos não eram corretos ou introduziam novos problemas.  
  - Conclusão: **viável como ferramenta de apoio**, mas não substitui revisão humana.  
- **Implicações:**  
  - IA pode apoiar a **migração para testes automatizados mais estáveis**.  
  - O desafio cultural é convencer times de QA a **confiar parcialmente na IA**, mantendo supervisão crítica.  

---

## 3. Fichamento Bibliográfico

### 3.1 Conceitos
- **Flaky Test:** teste que apresenta resultados inconsistentes, mesmo sem alteração no código.  
- **Non-Order-Dependent Test:** teste que falha de forma intermitente, mas não devido à ordem de execução.  
- **LLMs (Large Language Models):** modelos de linguagem, como ChatGPT, aplicados para automação em QA.  

### 3.2 Ferramentas/Sistemas/Bibliotecas
- **ChatGPT (OpenAI):** usado como ferramenta de reparo automatizado de testes.  
- **Repositórios GitHub:** base de dados para extração dos flaky tests.  

### 3.3 Teorias/Métodos
- **Estudo empírico:** análise experimental sobre a eficácia do ChatGPT em corrigir testes.  
- **Validação prática:** comparação entre testes originais e reparados.  
- **Análise qualitativa:** classificação dos tipos de reparos bem-sucedidos e falhos.  

---

## Relevância para o TCC
Este artigo é relevante porque:  
- Trata diretamente de **automação de QA com apoio de IA**.  
- Mostra **desafios técnicos**: IA ainda não é 100% confiável.  
- Aborda também **desafios culturais**: times de QA precisam aprender a integrar IA como suporte, e não substituição, no processo de migração de testes manuais.  
