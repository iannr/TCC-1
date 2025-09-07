# Fichamento – Lista Base 3
**Título:** Characterizing High-Quality Test Methods: A First Empirical Study  
**Autores:** Victor Veloso, Andre Hora 
**Ano:** 2022  
**Veículo:** ICSE (International Conference on Software Engineering)  
**Fonte:** Lista Base (Artigo nº 3)  
**Link:** https://doi.org/10.1145/3524842.3529092  

---

## 1. Fichamento de Citações
> “High-quality test methods are essential to ensure software reliability and maintainability, but little empirical evidence exists on what characterizes such methods.”  
>  
> “Our study shows that metrics such as readability, assertion density, and independence are strongly correlated with high-quality test methods.”  
>  
> “Automated static analysis can be leveraged to detect low-quality tests early, reducing maintenance costs.”

---

## 2. Fichamento de Conteúdo
O artigo investiga **quais fatores caracterizam métodos de teste de alta qualidade** em projetos de software.  
- **Problema:** Falta de consenso e evidência empírica sobre como definir e identificar testes de qualidade.  
- **Objetivo:** Avaliar métricas quantitativas que podem servir como indicadores de qualidade de testes.  
- **Metodologia:**  
  - Estudo empírico em **milhares de métodos de teste** de repositórios open-source.  
  - Análise de métricas como:  
    - **Readability** (clareza do código de teste).  
    - **Assertion density** (quantidade de asserts por linha de código).  
    - **Independence** (grau de isolamento de cada teste).  
- **Resultados:**  
  - As métricas propostas correlacionam-se fortemente com qualidade de testes.  
  - Testes de qualidade apresentam maior **manutenibilidade** e menor probabilidade de falhas ocultas.  
- **Implicações:**  
  - Automatizar a avaliação da qualidade de testes pode **reduzir custos de QA**.  
  - Fornece diretrizes objetivas para apoiar a **migração de testes manuais para automatizados**, já que testes automatizados podem ser validados pelas métricas.  

---

## 3. Fichamento Bibliográfico

### 3.1 Conceitos (nas minhas palavras)
- **Test Method Quality:** conjunto de atributos (clareza, assertividade, independência) que determinam se um teste é eficaz e confiável.  
- **Assertion Density:** indicador da proporção de verificações em relação ao tamanho do teste.  
- **Independence:** capacidade de um teste rodar sem depender da ordem ou estado de outros testes.  

### 3.2 Ferramentas/Sistemas/Bibliotecas
- **Static Analysis Tools** (ex.: SonarQube, PMD) — usadas para medir métricas automaticamente.  
- **Repositórios GitHub** — base de dados empírica utilizada no estudo.  

### 3.3 Teorias/Métodos
- **Engenharia de Software Experimental:** abordagem científica baseada em coleta e análise de dados reais.  
- **Método Quantitativo:** análise estatística de métricas de qualidade em larga escala.  
- **Validação cruzada:** repetição em múltiplos repositórios para garantir robustez dos resultados.  

---

## Relevância para o TCC
Este artigo contribui para o tema de **adoção de automação em QA** porque:  
- Define métricas objetivas que podem ser usadas para **avaliar testes automatizados**.  
- Ajuda a compreender a **diferença entre testes de alta e baixa qualidade**, essencial na migração de testes manuais.  
- Traz evidências de que automação + métricas de qualidade podem reduzir **desafios técnicos** e apoiar **decisões culturais** nos times de QA.
