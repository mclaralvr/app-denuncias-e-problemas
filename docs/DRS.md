# Documento de Requisitos de Software (DRS)

## 1. Introdução

### 1.1 Visao Geral
Este sistema tem como objetivo permitir que cidadãos registrem e acompanhem denúncias de problemas urbanos, como buracos em vias, falhas na iluminação pública, acúmulo de lixo, entre outros.

### 1.2 Objetivos do Sistema
Facilitar a comunicação entre população e prefeitura
Agilizar a resolução de problemas urbanos
Melhorar a qualidade de vida na cidade
Criar um histórico de ocorrências

### 1.3 Público Alvo
Cidadãos
Órgãos públicos (prefeitura)
Equipes de manutenção urbana


## 2. Escopo do Sistema

### 2.1 Escopo Incluído
Cadastro de usuários
Registro de denúncias com foto e localização
Acompanhamento do status da denúncia
Notificações de atualização
Painel administrativo para gestão

### 2.1 Escopo Incluído

---

## 3. Requisitos Funcionaís

### RF00 -  Cadastro de Usuário: O sistema deve permitir cadastro com e-mail e senha

### RF01 - Login: O usuário deve conseguir acessar sua conta

### RF02 -  Registrar Denúncia: O usuário pode registrar problemas com descrição, foto e localização
### RF03 – Visualizar Denúncias: O usuário pode ver denúncias próximas
### RF04 – Acompanhar Status: O usuário acompanha o andamento (pendente, em análise, resolvido)
### RF05 – Notificações: O sistema envia atualizações sobre denúncias
### RF06 – Painel Admin: Administradores podem gerenciar denúncias

## 4. Requisitos Não Funcionais

### RNF00 -Usabilidade: Interface simples e intuitiva
### RNF01 – Desempenho: Resposta em até 3 segundos
### RNF02 – Segurança: Dados protegidos (login seguro)
### RNF03 – Disponibilidade: Sistema disponível 24h
### RNF04 – Compatibilidade: Funcionar em Android, iOS e Web


## 5. Arquitetura Técnica 

### 5.1 Stacks

#### 5.1.1 Stack Backend 
Backend
Node.js ou Python (API REST)

#### 5.1.2 Stack Frontend
React (Web)
React Native ou Flutter (Mobile)

#### 5.1.7 Banco de Dados
PostgreSQL ou MongoDB

## 6. Modelo de Dados
Usuário
id
nome
email
senha
Denúncia
id
título
descrição
foto
localização (latitude/longitude)
status
data
