# VesperDocs

Mapa central do ecossistema **Vesper / Domínio Escarlate**.

Este repositório explica responsabilidades, fronteiras e workflow comum. A arquitetura detalhada, build e funcionalidades de cada projeto permanecem no respetivo repositório.

## Componentes

| Componente | Papel | Código |
|---|---|---|
| VesperCore | Plugin server-side principal | [OficialAqua/VespelCore](https://github.com/OficialAqua/VespelCore) |
| PlayerServices | Serviços server-side orientados aos jogadores | [OficialAqua/PlayerServices](https://github.com/OficialAqua/PlayerServices) |
| VesperClient | Plugin client-side opcional | [OficialAqua/VesperClient](https://github.com/OficialAqua/VesperClient) |
| VesperLauncher | Instalação e gestão no computador do jogador | [OficialAqua/VesperLauncher](https://github.com/OficialAqua/VesperLauncher) |
| Domínio Escarlate | Manifestos e distribuição client-side | [OficialAqua/Dominio-Escarlate](https://github.com/OficialAqua/Dominio-Escarlate) |

## Começar

- [Mapa do ecossistema](ECOSYSTEM.md)
- [Workflow ChatGPT, Work, Codex e GitHub](DEVELOPMENT-WORKFLOW.md)
- [Regras para agentes](AGENTS.md)
- [VesperCore](COMPONENTS/VesperCore.md)
- [PlayerServices](COMPONENTS/PlayerServices.md)
- [VesperClient](COMPONENTS/VesperClient.md)
- [VesperLauncher](COMPONENTS/VesperLauncher.md)
- [Domínio Escarlate](COMPONENTS/Dominio-Escarlate.md)

## Fonte de verdade

O GitHub é a fonte de verdade técnica. Chats e Notion podem guardar contexto e planeamento, mas decisões importantes devem chegar a código, documentação, issues, changelog ou commits.

> Uma funcionalidade não está completamente terminada até que código, build/testes aplicáveis e documentação relevante estejam coerentes.
