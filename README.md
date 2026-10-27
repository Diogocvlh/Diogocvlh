# Diogo Carvalho

**Engenharia de Computação · PUC Goiás**

Projetos de estudo e portfólio em desenvolvimento de software, com foco em aplicações web, APIs e automação. Aqui reúno código, decisões técnicas e instruções para executar os projetos.

[Projeto principal](https://github.com/Diogocvlh/fieldops) · [Documentação técnica](https://github.com/Diogocvlh/fieldops/blob/main/docs/ARCHITECTURE.md)

## Projeto em destaque

### [FieldOps — Gestão de ordens de serviço](https://github.com/Diogocvlh/fieldops)

Sistema para organizar ordens de serviço, equipes técnicas e distribuição de trabalho. Combina **React e TypeScript** na interface com uma **API Java e Spring Boot**.

[![Verificação do FieldOps](https://github.com/Diogocvlh/fieldops/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/Diogocvlh/fieldops/actions/workflows/ci.yml)

![Dashboard do FieldOps com dados fictícios](https://raw.githubusercontent.com/Diogocvlh/fieldops/main/docs/assets/dashboard-desktop.jpg)

- Cinco páginas: dashboard, ordens de serviço, técnicos, distribuição e relatórios.
- Validação de disponibilidade e capacidade dos técnicos, registro de conclusão e histórico de atividades.
- Adaptadores para demonstração em localStorage e integração HTTP com a API Java.
- Migrações PostgreSQL com Flyway, testes automatizados e integração contínua.

**Etapa atual:** MVP de demonstração. A API local ainda não inclui autenticação; a integração com uma instância Supabase depende de configuração e validação.

[Conhecer o projeto](https://github.com/Diogocvlh/fieldops#readme) · [Ver arquitetura](https://github.com/Diogocvlh/fieldops/blob/main/docs/ARCHITECTURE.md) · [Consultar API](https://github.com/Diogocvlh/fieldops/blob/main/docs/API.md) · [Ver testes na CI](https://github.com/Diogocvlh/fieldops/actions)

## Tecnologias nos meus projetos

| Área | Tecnologias utilizadas |
| --- | --- |
| Interface web | React, TypeScript, Tailwind CSS e Vite |
| APIs e regras de negócio | Java, Spring Boot e Python |
| Persistência | PostgreSQL, H2 e migrações com Flyway |
| Qualidade e entrega | Git, GitHub Actions, testes Java e Vitest |
| Experimentos com IA | FastAPI, PyTorch e Diffusers |

## Outros projetos públicos

| Projeto | Proposta | Etapa |
| --- | --- | --- |
| [API de geração de imagens](https://github.com/Diogocvlh/ai-image-generator-api) | Experimento de API em Python com FastAPI, PyTorch e Diffusers para geração de imagens com execução em GPU. | Experimental; requisitos e limitações descritos no repositório. |

## O que estou aprimorando

Organização de código, validação de dados, testes e integração entre interface, API e banco. No FieldOps, os próximos passos incluem autenticação, permissões e proteção contra edições simultâneas.
