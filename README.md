# 🌀 Akatsuki Intelligence System - Pipeline ETL

Este projeto demonstra um fluxo completo de **Engenharia de Dados (ETL)** desenvolvido durante a **Curso da DIO- Santander 2025- Ciências de dados com Python-Explorando IA Generativa em um Pipeline de ETL com Python.**. 

O sistema realiza a extração de dados da organização Akatsuki, processa informações detalhadas e gera alertas de segurança personalizados.



## 🛠️ Tecnologias e Conceitos
* **Linguagem:** Python
* **Bibliotecas:** Pandas (Tratamento de dados), Requests (Consumo de API).
* **Arquitetura:** ETL (Extract, Transform, Load).
* **Resiliência de Software:** Implementação de lógica de *fallback* para tratamento de erros em APIs externas.

## 📈 O Pipeline
1.  **Extract:** Consumo da `dattebayo-api` para obter dados de membros da Akatsuki.
2.  **Transform:** Extração de metadados aninhados (Clãs, Títulos e Afiliações) e geração de alertas dinâmicos baseados no perfil de cada ninja.
3.  **Load:** Exportação dos dados limpos e processados para um arquivo CSV estruturado.

## 👩‍💻 Sobre a Autora
Desenvolvido por **Rayssa Mirelle**, graduanda em **Engenharia de Computação na UFRPE** e membro da equipe de robótica **AUTOBOTS**. Interessada em Ciência de Dados, IA e Automação.
