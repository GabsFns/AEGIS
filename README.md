# AEGIS: Post-Quantum Security Platform

![Versão](https://img.shields.io/badge/version-Beta%201.1.2V-orange)
![Status](https://img.shields.io/badge/status-Architectural%20Study-blue)

A **AEGIS** é uma plataforma de segurança digital projetada para enfrentar os desafios da transição para a era da computação quântica. O projeto foca em resiliência criptográfica e arquitetura de sistemas de alta criticidade.

## 📑 Visão Geral

Atualmente, a segurança da internet baseia-se em problemas matemáticos que computadores clássicos levam milênios para resolver. Entretanto, com o avanço da Computação Quântica e o surgimento do **Algoritmo de Shor**, essa barreira pode ser quebrada em minutos.

A AEGIS mitiga o risco de ataques do tipo **"Harvest Now, Decrypt Later"** (Coletar agora, descriptografar depois), onde dados são interceptados hoje para serem decifrados no futuro.

## Diferenciais da Arquitetura

A plataforma utiliza uma abordagem de **Criptografia Híbrida**, combinando algoritmos clássicos com novos padrões pós-quânticos (PQC) baseados em reticulados (*lattices*) selecionados pelo NIST.

### Stack Tecnológica (Modelo Poliglota)
*   **Backend Core:** Java com Spring Boot para gestão de identidade e regras de negócio.
*   **Alta Performance:** Go para processamento criptográfico intensivo e streaming de eventos.
*   **Inteligência de Risco:** Python para análise comportamental e predição de vulnerabilidades via IA.

### Persistência Poliglota (Polyglot Persistence)
O sistema utiliza o mecanismo de armazenamento mais adequado para cada domínio:
*   **PostgreSQL:** Dados transacionais, identidades e chaves criptográficas.
*   **MongoDB:** Logs de auditoria massivos e eventos de telemetria.
*   **Redis:** Cache distribuído para autenticação de baixa latência e rate limiting.

## Pilares de Segurança

1.  **Criptografia Pós-Quântica:** Integração nativa de algoritmos como **CRYSTALS-Kyber** (chaves) e **CRYSTALS-Dilithium** (assinaturas).
2.  **Auditabilidade via Blockchain:** Registro imutável de eventos críticos para garantir transparência e não-repúdio.
3.  **Segurança Zero Trust:** Comunicação entre microsserviços protegida e autenticada continuamente.
4.  **Análise de Risco Preditiva:** Engine que detecta anomalias comportamentais em tempo real antes que vulnerabilidades sejam exploradas.

## Status do Projeto

Este repositório contém atualmente a **Documentação Técnica Completa (Versão Beta 1.1.2V)**.
- [x] Concepção da Arquitetura de Microsserviços
- [x] Modelagem de Dados Relacional e Documental
- [ ] Implementação do Projeto (em desenvolvimento)
- [ ] Expansão do Glossário Técnico

## Documentação
O documento técnico detalhado com diagramas de sequência, modelos ER e justificativas teóricas pode ser encontrado na pasta `/docs`.

---
**Autor:** Gabriel Fernandes Moura dos Santos (2026)
