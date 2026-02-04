# ☕ Cafeteria Carioca na AWS

Portfolio_Proj_018-Cafeteria_Carioca_na_AWS_Cloud


![AWS](https://img.shields.io/badge/AWS-Cloud-orange?logo=amazonaws)
![Amazon S3](https://img.shields.io/badge/Amazon%20S3-Storage-green?logo=amazons3)
![VPC](https://img.shields.io/badge/Amazon%20VPC-Network-blue?logo=amazonaws)
![IAM](https://img.shields.io/badge/IAM-Security-red?logo=amazonaws)
![Status](https://img.shields.io/badge/Status-Estudo%20Acadêmico-lightgrey)

Projeto acadêmico com foco em **Cloud Computing**, demonstrando a hospedagem de um site institucional estático na AWS e a exploração de serviços fundamentais da nuvem, usando como estudo de caso o site da **Cafeteria Carioca**.

---

## 🌐 Site publicado (versão permanente)

Como os ambientes de laboratório da AWS são temporários, o site também está publicado de forma permanente via **GitHub Pages**:

🔗 **https://SEU-USUARIO.github.io/cafeteria-carioca/**

> Essa versão representa o mesmo site utilizado no laboratório S3.

---

## 📌 Visão geral do projeto

O objetivo deste projeto é demonstrar, de forma prática e conceitual, como uma aplicação simples pode ser hospedada e evoluída dentro da AWS.

O projeto está organizado em **fases**, onde cada fase apresenta um serviço ou conceito da AWS que faria parte de uma arquitetura real para um pequeno negócio.

> ⚠️ Observação: devido às limitações do ambiente de laboratório (AWS Academy / VocLabs), alguns recursos não permanecem ativos após o encerramento da sessão. Por isso, o projeto é documentado com prints, vídeos e explicações arquiteturais.

---

## 🟢 Fase 1 — Hospedagem de Site Estático no Amazon S3

![Amazon S3](https://img.shields.io/badge/Service-Amazon%20S3-green?logo=amazons3)

### 🎯 Objetivo
Hospedar o site institucional da Cafeteria Carioca de forma simples, escalável e sem necessidade de servidor.

### 🔧 Serviço utilizado
- Amazon S3 (Simple Storage Service)

### 🛠️ O que foi feito
- Criação de um bucket S3
- Upload dos arquivos HTML, CSS e imagens do site
- Ativação do **Static Website Hosting**
- Configuração de permissões públicas de leitura
- Acesso ao site via URL pública do S3

### ✅ Resultado
O site ficou acessível diretamente pelo endpoint de site estático do S3.

### 📸 Evidências

**Bucket S3 criado**

[INSERIR PRINT DO BUCKET AQUI]


**Configuração de Static Website Hosting**

[INSERIR PRINT DA CONFIGURAÇÃO AQUI]


**Site funcionando via URL do S3**


[INSERIR PRINT DO SITE NO NAVEGADOR]


**Demonstração em vídeo / GIF**


[INSERIR GIF OU LINK PARA VÍDEO]


### 💡 Por que usar S3?
- Alta disponibilidade
- Baixo custo
- Escalabilidade automática
- Ideal para sites institucionais e landing pages

---

## 🔵 Fase 2 — Rede e Isolamento com Amazon VPC

![Amazon VPC](https://img.shields.io/badge/Service-Amazon%20VPC-blue?logo=amazonaws)

### 🎯 Objetivo
Compreender como a AWS organiza recursos dentro de redes privadas e seguras.

### 🔧 Serviço explorado
- Amazon VPC (Virtual Private Cloud)

### 🛠️ O que foi feito
- Criação de uma VPC com nome relacionado ao projeto
- Análise dos componentes básicos da VPC

### 🔗 Relação com o projeto
Em um cenário real, a VPC seria utilizada para:
- Hospedar servidores EC2
- Isolar banco de dados
- Controlar tráfego de entrada e saída

### 📸 Evidências


[INSERIR PRINT DA VPC CRIADA]


---

## 🔐 Fase 3 — Segurança e Controle de Acesso (IAM)

![IAM](https://img.shields.io/badge/Service-IAM-red?logo=amazonaws)

### 🎯 Objetivo
Entender como a AWS controla acesso a recursos e serviços.

### 🔧 Serviço explorado
- AWS Identity and Access Management (IAM)

### 📘 Conceitos aplicados
- Usuários e permissões
- Políticas de acesso
- Princípio do menor privilégio

### 🔗 Relação com o projeto
No contexto da Cafeteria Carioca:
- Apenas usuários autorizados poderiam alterar o site
- Permissões seriam separadas por função
- Recursos críticos seriam protegidos

### 📸 Evidências


[INSERIR PRINTS DO IAM]


---

## 📊 Fase 4 — Auditoria e Monitoramento (Visão conceitual)

![CloudTrail](https://img.shields.io/badge/Service-CloudTrail-lightgrey?logo=amazonaws)

### 🎯 Objetivo
Compreender como ações na AWS podem ser monitoradas e auditadas.

### 🔧 Serviço explorado
- AWS CloudTrail (conceitual)

### 📘 Aplicação prática
- Registro de acessos ao S3
- Auditoria de mudanças no ambiente
- Suporte a requisitos de segurança

### 📸 Evidências


[INSERIR PRINTS DE TELAS RELACIONADAS]


---

## 🚀 Possíveis evoluções do projeto

Este projeto pode evoluir para uma arquitetura mais completa, incluindo:

- Amazon EC2 para backend dinâmico
- Amazon RDS para banco de dados
- Elastic Load Balancer para alta disponibilidade
- AWS CLI para automação de deploy
- Amazon CloudFront para CDN

Essas evoluções não foram implementadas devido às limitações do laboratório, mas fazem parte da visão arquitetural do projeto.

---

## 📚 Conclusão

O projeto **Cafeteria Carioca na AWS** demonstra:

- Hospedagem eficiente de site estático
- Compreensão de redes e segurança
- Noções de arquitetura em nuvem
- Capacidade de adaptação a ambientes temporários

Mesmo em um contexto acadêmico, o projeto reflete práticas reais de cloud computing.

---

## ✍️ Autora

**Marcinha**  
Desenvolvedora Web  
Projeto desenvolvido para estudos em Cloud Computing / AWS