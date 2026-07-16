# Leonardo Zanon Arruda

Arquiteto de agentes de IA autônomos · MCP · Engenharia de prompts · Diretor Geral — Autoescola Penha Car

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/leonardo-zanon-arruda)
[![Email](https://img.shields.io/badge/Email-lzanonarruda%40gmail.com-D14836?style=flat&logo=gmail&logoColor=white)](mailto:lzanonarruda@gmail.com)

## Sobre mim

Concebo e opero um sistema de agente de IA autônomo com memória persistente em camadas, skills modulares carregadas sob demanda e orquestração via **MCP (Model Context Protocol)**, integrado a múltiplos serviços externos via **Composio**.

Desenvolvi dois módulos de raciocínio especializado:
- **Estrutural** — 7 zonas funcionais, protocolo de 24 cenários
- **Decisório** — 6 disposições cognitivas, 11 heurísticas; validado em suíte de 10 cenários (10/10 aprovados)

## Stack

![Claude Code](https://img.shields.io/badge/Claude_Code-CLI-orange?style=flat)
![MCP](https://img.shields.io/badge/MCP-Orquestração-purple?style=flat)
![Composio](https://img.shields.io/badge/Composio-Integração-blue?style=flat)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![AppSheet](https://img.shields.io/badge/AppSheet-No--Code-green?style=flat)

## Módulos de Raciocínio

- **skill-modulo-raciocinio-estrutural** — módulo cognitivo com arquitetura de 7 zonas funcionais
- **skill-modulo-raciocinio-decisorio** — módulo de decisão validado em suíte de 10 cenários (10/10 aprovados)

## MCP

- **mcp-banco-imagens** — servidor MCP de busca semântica de imagens por embedding (Gemini Vision + Gemini Embeddings), multi-namespace e reutilizável por qualquer projeto

## Qualidade Visual

- **skill-validar-arte-visual** — valida peça visual antes de publicar (12 critérios + 10 regras complementares + relatório estruturado de 6 seções), desacoplada de cliente ou ferramenta de geração

## Confiabilidade de Execução

- **skill-auditoria-execucao** — cria e audita checklist de gates obrigatórios de outra skill (bootstrap/fechamento), reduzindo o risco de uma etapa ser pulada silenciosamente; desacoplada de cliente ou skill específica

## Skills Genéricas de Conteúdo

- **skill-criar-legenda-instagram** — legenda + hashtags para post/carrossel do Instagram, desacoplada de cliente (qualquer marca)

## Marca Certa Digital

- **skill-marca-certa-respostas** — engine genérica de respostas calibrada por brand profile (79 respostas aprovadas no primeiro ciclo)

## Sistema de Conteúdo Visual (client-agnostic)

6 skills de conteúdo, nenhuma com dado ou nome de cliente hardcoded — cada uma lê um `brand-profile.md` por cliente em tempo de execução (schema documentado, exemplo fictício incluso). Regidas por especificação de marca compartilhada e orquestradas por skill de calendário mensal, que gera post/carrossel de Instagram, copy e thumbnail de Google Meu Negócio em lote para cada linha do plano aprovado. Em uso em produção pela Autoescola Penha Car.

- **skill-criar-post-instagram** — post único Instagram (HTML com identidade visual do cliente + exportação PNG 1080×1350px via Playwright)
- **skill-criar-carrossel-instagram** — carrossel multi-slide para Instagram
- **skill-criar-copy-gmn** — copy editorial para Google Meu Negócio
- **skill-criar-thumbnail-gmn** — thumbnail 4:3 (1200×900px) para Google Meu Negócio
- **skill-calendario-conteudo** — planejamento e orquestração do calendário mensal em lote (Instagram + GMN)
- **skill-classificar-icones** — classifica e nomeia ícones novos do banco visual da marca, passo automático antes das demais skills escolherem ícone
