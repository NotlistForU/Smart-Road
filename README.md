# Smart-Road


# Documento de Visão e Escopo

## 1. Visão Geral do Projeto

Este projeto consiste no desenvolvimento de um **sistema completo de análise e acompanhamento de informações de um automóvel**, com foco principal em **aprendizado prático de engenharia de software**, utilizando **Java como linguagem central** e **Spring (Spring Boot)** como principal framework de backend.

O sistema permitirá ao usuário registrar, organizar e analisar dados financeiros, operacionais e de manutenção do veículo, apresentando essas informações de forma **intuitiva, visual e acessível**, inclusive em dispositivos móveis, com potencial futuro de publicação na **Google Play Store**.

Mais do que apenas entregar uma aplicação funcional, o objetivo é **percorrer todo o ciclo de vida de um software**, desde a concepção e documentação até a implementação, testes, deploy e evolução.

---

## 2. Objetivos do Projeto

### 2.1 Objetivo Principal

Desenvolver um sistema completo, do zero, que permita analisar custos, uso e histórico de manutenção de um automóvel, **utilizando Java como base**, servindo como um projeto educacional e evolutivo.

### 2.2 Objetivos de Aprendizado

O projeto tem como foco o aprendizado prático dos seguintes tópicos:

* Arquitetura de software (camadas, responsabilidades e boas práticas)
* Desenvolvimento backend com **Java + Spring Boot**
* Modelagem de domínio e banco de dados
* Persistência de dados (JPA / Hibernate)
* Criação de APIs REST
* Consumo de APIs por aplicações móveis
* Autenticação e segurança
* Versionamento com Git
* Documentação técnica e funcional
* Testes automatizados
* Deploy e possíveis estratégias de publicação

O sistema será desenvolvido de forma incremental, priorizando **clareza, organização e aprendizado**, e não apenas velocidade de entrega.

---

## 3. Público-Alvo

* Desenvolvedores iniciantes ou intermediários em Java
* Estudantes de programação e engenharia de software
* Pessoas interessadas em aprender desenvolvimento backend e mobile de forma prática
* Usuários finais que desejam controlar e entender melhor os custos e uso do seu automóvel

---

## 4. Descrição Funcional do Sistema

O sistema permitirá ao usuário registrar e analisar informações relacionadas ao seu automóvel, incluindo:

### 4.1 Dados Financeiros do Veículo

* Valor de compra do automóvel
* Data da compra
* Custos recorrentes (combustível, manutenção, peças)
* Análise de gastos:

  * Diária
  * Mensal
  * Anual

### 4.2 Consumo e Uso

* Registro de abastecimentos

  * Data
  * Valor pago
  * Quantidade de combustível
  * Quilometragem no momento do abastecimento
* Cálculo automático de:

  * Quilômetros por litro (km/L)
  * Média de consumo
  * Custo por quilômetro rodado
* Total de quilômetros rodados em períodos definidos

### 4.3 Manutenção e Oficina

* Registro de idas à oficina

  * Data de entrada
  * Data de saída
  * Tipo de manutenção (preventiva/corretiva)
  * Peças substituídas
  * Valor gasto
* Histórico de manutenções
* Identificação de:

  * Peças que mais apresentaram problemas
  * Frequência de manutenções
  * Tempo total em oficina

---

## 5. Visualização e Experiência do Usuário

Um dos pilares do sistema será **evitar que a inserção de dados seja cansativa ou repetitiva**. Para isso, serão adotadas estratégias como:

* Formulários simples e objetivos
* Reaproveitamento de dados anteriores (ex: última quilometragem)
* Campos inteligentes e cálculos automáticos
* Interface focada em poucos cliques

A visualização das informações será feita por meio de:

* Gráficos intuitivos (linha, barra, pizza)
* Indicadores resumidos (cards)
* Comparações entre períodos

---

## 6. Plataforma e Tecnologias

### 6.1 Backend (Principal Foco)

* **Java**
* **Spring Boot**
* Spring Data JPA
* Spring Security (em fases posteriores)
* API REST

### 6.2 Banco de Dados

* Banco relacional (ex: PostgreSQL ou MySQL)
* Modelagem clara e normalizada

### 6.3 Frontend / Mobile

* Aplicação mobile (inicialmente como cliente da API)
* Possibilidade de uso de:

  * Flutter
  * Android nativo
  * Outra tecnologia, conforme evolução do aprendizado

> Observação: tecnologias além de Java poderão ser utilizadas **apenas como suporte**, mantendo o foco principal no aprendizado do backend.

---

## 7. Arquitetura do Sistema

O sistema seguirá uma arquitetura em camadas, incluindo:

* Camada de Apresentação (API REST)
* Camada de Serviço (regras de negócio)
* Camada de Persistência (repositórios)
* Camada de Domínio (entidades e modelos)

Essa estrutura visa facilitar:

* Manutenção
* Testes
* Evolução futura do sistema

---

## 8. Escopo Inicial (MVP)

Na primeira fase do projeto, o sistema deverá:

* Permitir cadastro do veículo
* Registrar abastecimentos
* Registrar manutenções
* Calcular consumo médio
* Gerar gráficos básicos de gastos e consumo

Funcionalidades mais avançadas serão adicionadas progressivamente.

---

## 9. Evolução e Futuro do Projeto

Possíveis evoluções incluem:

* Suporte a múltiplos veículos
* Autenticação de usuários
* Backup em nuvem
* Publicação na Google Play Store
* Comparativos entre veículos
* Exportação de relatórios

---

## 10. Considerações Finais

Este projeto foi concebido com foco em **aprendizado sólido, prática real e construção de um sistema completo**, priorizando boas práticas de desenvolvimento, organização e clareza.

Mais do que o resultado final, o valor do projeto está no processo de construção, documentação e evolução contínua do sistema.
