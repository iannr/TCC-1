# Fichamento – Lista Base 92
**Título:** Automated Test-Case Generation for REST APIs Using Model Inference Search Heuristic  
**Autores:** Natanael Djajadi, Amirhossein Deljouyi, Andy Zaidman 
**Ano:** 2025  
**Veículo:** arXiv / Conferência Internacional  
**Fonte:** Lista Base (Artigo nº 92)  
**Link:** https://arxiv.org/pdf/2412.03420  


## 1. Fichamento de Conteúdo

O artigo propõe uma abordagem para a geração automática de casos de teste em APIs REST utilizando heurísticas baseadas em inferência de modelos. O estudo parte do problema de que a testagem de APIs é frequentemente trabalhosa e demanda esforço manual significativo, devido ao grande número de endpoints, parâmetros e fluxos possíveis. O objetivo dos autores foi reduzir esse esforço e aumentar a cobertura de forma automatizada. Para validar a proposta, foi desenvolvido um protótipo experimental que aplica heurísticas de busca sobre modelos inferidos a partir da especificação das APIs, permitindo a geração sistemática de cenários de teste. A avaliação, realizada em diferentes APIs reais, mostrou que a técnica é capaz de produzir um número expressivo de casos de teste em menos tempo, com cobertura superior à abordagem manual. Entretanto, a qualidade final dos testes ainda depende da qualidade dos modelos de entrada, o que exige ajustes em diferentes contextos. O estudo conclui que a automação desse processo pode reduzir custos e acelerar a validação de sistemas, mas também aponta que a adoção dessa prática exige das equipes de QA uma mudança cultural para confiar em ferramentas automáticas e incorporá-las ao fluxo de desenvolvimento.

---

## 2. Fichamento Bibliográfico

### 2.1 Conceitos
- REST APIs: interfaces de comunicação baseadas em HTTP, fundamentais em sistemas modernos.  
- Test-Case Generation: processo de criar automaticamente entradas e saídas esperadas para validar endpoints.  
- Model Inference Heuristic: técnica que gera modelos de comportamento da API e infere testes a partir deles.  

### 2.2 Ferramentas/Sistemas/Bibliotecas
- Ferramentas experimentais de geração automática de testes para APIs REST (protótipo desenvolvido pelos autores).  
- Postman e Swagger/OpenAPI citados como padrões comuns de teste/manualização de APIs.  

### 2.3 Teorias/Métodos
- Engenharia de Software Experimental: avaliação empírica em sistemas reais.  
- Método quantitativo: comparação de métricas de cobertura, tempo de execução e esforço.  
- Heurísticas de busca: aplicadas à inferência de modelos de APIs.  

---

## 3. Fichamento de Citações
> “REST APIs dominate modern software systems, but ensuring their reliability requires effective automated testing.”  
>  
> “We propose a model inference search heuristic to generate high-quality test cases for REST APIs automatically.”  
>  
> “Our evaluation shows that automated generation achieves broader coverage with less manual effort.”

---

## Relevância para o TCC
Este artigo é altamente relevante para o tema de automação em QA porque:  
- Demonstra como a automação reduz esforço humano em tarefas repetitivas.  
- Relaciona-se diretamente à migração de testes manuais para automatizados em um contexto real (APIs REST).  
- Mostra tanto desafios técnicos (qualidade dos modelos) quanto culturais (adoção por times que estão acostumados com testes manuais).  
