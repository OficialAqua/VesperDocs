# AGENTS.md

## Objetivo

Este repositório é o mapa central. Não contém a implementação dos componentes.

## Regras para agentes

1. Identifique o componente responsável antes de propor código.
2. Abra o repositório do componente e leia o respetivo `AGENTS.md`.
3. Use o código atual como fonte de verdade técnica.
4. Não classifique planos de chat como implementações.
5. Não duplique documentação técnica extensa aqui.
6. Atualize este mapa apenas quando responsabilidades, fronteiras ou workflow mudarem.
7. Preserve o VesperClient como opcional.
8. Não mova lógica server-side para Client ou Launcher.
9. Não invente APIs ou dependências.
10. Não considere concluída uma feature sem build/testes aplicáveis.
11. Não publique DLLs proprietárias, segredos, saves ou dados pessoais.
12. Utilize branches próprias; não faça merge sem autorização.

## Repositórios

- Core: `OficialAqua/VespelCore`
- Serviços: `OficialAqua/PlayerServices`
- Client: `OficialAqua/VesperClient`
- Launcher: `OficialAqua/VesperLauncher`
- Distribuição: `OficialAqua/Dominio-Escarlate`

## Divergências conhecidas

- O repositório do Core chama-se `VespelCore`, enquanto o produto é VesperCore.
- O Core publicado não corresponde a todas as funcionalidades conhecidas da build atual.
- O código recente PlayerServices/BloodyWallet ainda precisa de sincronização.
- Documentação padronizada permanece em branches de revisão até merge.
