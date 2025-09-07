# Fichamento – Lista Base 92
**Título:** Automated Test-Case Generation for REST APIs Using Model Inference Search Heuristic  
**Autores:** Natanael Djajadi, Amirhossein Deljouyi, Andy Zaidman 
**Ano:** 2025  
**Veículo:** arXiv / Conferência Internacional  
**Fonte:** Lista Base (Artigo nº 92)  
**Link:** https://arxiv.org/pdf/2412.03420  

---

## 1. Fichamento de Citações
> “REST APIs dominate modern software systems, but ensuring their reliability requires effective automated testing.”  
>  
> “We propose a model inference search heuristic to generate high-quality test cases for REST APIs automatically.”  
>  
> “Our evaluation shows that automated generation achieves broader coverage with less manual effort.”

---

## 2. Fichamento de Conteúdo
O artigo propõe uma técnica para **geração automática de casos de teste para APIs REST**, usando **heurísticas de inferência de modelos**.  
- **Problema:** APIs REST são fundamentais, mas exigem grande esforço manual para testar múltiplos endpoints, parâmetros e fluxos.  
- **Objetivo:** Automatizar a criação de casos de teste de forma eficiente e com maior cobertura.  
- **Metodologia:**  
  - Proposta de **heurística baseada em inferência de modelos**.  
  - Avaliação empírica em APIs reais, comparando com geração manual.  
- **Resultados:**  
  - Automação gera **mais casos de teste** em menos tempo.  
  - A cobertura funcional foi superior à abordagem manual.  
  - A qualidade dos testes depende de **bons modelos de entrada**, exigindo ajustes para contextos diferentes.  
- **Implicações:**  
  - Reduz custos e esforço de QA.  
  - Apoia times em **migração de testes manuais para automatizados**.  
  - Mostra que o desafio cultural está em **confiar na automação** e integrá-la ao fluxo de desenvolvimento.  

---

## 3. Fichamento Bibliográfico

### 3.1 Conceitos (nas minhas palavras)
- **REST APIs:** interfaces de comunicação baseadas em HTTP, fundamentais em sistemas modernos.  
- **Test-Case Generation:** processo de criar automaticamente entradas e saídas esperadas para validar endpoints.  
- **Model Inference Heuristic:** técnica que gera modelos de comportamento da API e infere testes a partir deles.  

### 3.2 Ferramentas/Sistemas/Bibliotecas
- Ferramentas experimentais de **geração automática de testes para APIs REST** (protótipo desenvolvido pelos autores).  
- **Postman e Swagger/OpenAPI** citados como padrões comuns de teste/manualização de APIs.  

### 3.3 Teorias/Métodos
- **Engenharia de Software Experimental:** avaliação empírica em sistemas reais.  
- **Método quantitativo:** comparação de métricas de cobertura, tempo de execução e esforço.  
- **Heurísticas de busca:** aplicadas à inferência de modelos de APIs.  

---

## Relevância para o TCC
Este artigo é altamente relevante para o tema de **automação em QA** porque:  
- Demonstra como a automação **reduz esforço humano** em tarefas repetitivas.  
- Relaciona-se diretamente à **migração de testes manuais para automatizados** em um contexto real (APIs REST).  
- Mostra tanto **desafios técnicos** (qualidade dos modelos) quanto **culturais** (adoção por times que estão acostumados com testes manuais).  
