# Desafio
Ofertar o melhor produto entre Consórcio ou Financiamento de Veículos baseando-se no perfil, no comportamento do cliente nos canais digitais do banco e sua geolocalização.

## Premissas
 - O sistema de consórcio se encontra em ambiente mainframe.
 - O sistema de financiamento de veículos expõe webservices SOAP que suportam atualmente 10 TPS.
 - Uma oferta é uma proposta do banco para o cliente de algum produto ou serviço que possa ser contratado com as melhores condições dependendo do perfil.
 - A geolocalização capturada em nossos canais digitais são realizadas a partir de uma parceira de TI que utiliza serviços da AWS.
 - Como há dados sensíveis sendo trafegados é importante as camadas de segurança e fraude fazerem parte da jornada de captura.
 - Temos uma previsão de consumo de mais 1000 TPS
 - Se integrar a um Backoffice externo em Salesforce

## Keywords
 - [x] Saga pattern
 - [x] Escalabilidade
 - [x] 12 fatores
 - [x] Event driven
 - [x] Microservices
 - [x] Segurança
 - [x] API first
 - [x] Solução ponta a ponta
 - [x] Observability
 - [x] Omnichannel
 - [x] Clean Archtecture
 - [x] Desacoplamento
 - [x] Banco de dados schemless
 - [x] Cloud

## Principais funcionalidades
 - As ofertas devem ter uma jornada de criação e exposição near real-time.
 - As ofertas serão disponibilizadas através de canais digitais por push ou banners ou meios de comunicação como SMS e e-mail.

## O que esperamos?
Desenho da solução no qual seja possível identificar as principais barreiras sistêmicas e integrações entre as peças que compõe a arquitetura, assim como modelos de disponibilidade.


