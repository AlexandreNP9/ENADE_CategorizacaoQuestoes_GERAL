# ENADE - Categorização de Questões
Repositório central do projeto de categorização das questões do ENADE (Exame Nacional de Desempenho dos Estudantes).

## 🎯 Objetivos
Criar banco de dados categorizado e pesquisável das questões.  
Fornecer material de estudo estruturado para estudantes.  
Oferecer recursos pedagógicos para docentes.  

## Público alvo
Estudantes e docentes de graduação.

## 🗺️ Documentação do Projeto
Mapa Conceitual: Visualizar no CmapsCloud[https://cmapscloud.ihmc.us/viewer/cmap/21XLK9Y20-1LJYJMM-B7NGKH]  
Modelo Instrucional: Visualizar no Excalidraw[https://excalidraw.com/#json=Ov-9QdZZEed1ViFxOVV9K,z2yXPfPwRN_kqyPS1qJNPQ]

## 🏗️ Arquitetura do Sistema
Sistema distribuído com subsistemas especializados:

Tratamento de Imagens: Conversão PDF→PNG, recorte e organização: https://github.com/AlexandreNP9/ENADE_CategorizacaoQuestoes_TratamentoImagens  
Extração de Conteúdo: OCR para extração textual e descrição de figuras dos enunciados: https://github.com/AlexandreNP9/ENADE_CategorizacaoQuestoes_ExtracaoConteudo  
Análise e Categorização: Identificação de conteúdos, habilidades e análise de alternativas para criação de banco de dados: A SER CRIADO  
Interface de Acesso: CRUD com interface pesquisável: A SER CRIADO  

## 🚀 Funcionalidades
Processamento semi-automatizado de imagens e OCR
Categorização inteligente de questões
Identificação de habilidades e competências
Banco de dados estruturado para consulta
Interface web para interface
Projeto em desenvolvimento para facilitar o estudo e análise das questões do ENADE.
