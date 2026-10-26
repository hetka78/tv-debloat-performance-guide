# TV Debloat & Performance Guide

Documentação em português (Brasil) para orientar a avaliação e otimização de Smart TVs e TV Boxes com foco em desempenho, redução de processos supérfluos e preservação da recuperação do sistema.

## Objetivos

- Identificar corretamente a plataforma antes de sugerir qualquer procedimento.
- Priorizar ajustes reversíveis e documentados.
- Não inventar resultados de RAM, compatibilidade ou atualizações.
- Registrar riscos, exceções, estado anterior e método de recuperação.
- Separar claramente procedimentos Android TV/Google TV dos procedimentos webOS, Tizen e Fire OS.

## Compatibilidade por plataforma

| Plataforma | Procedimento Android ADB/`pm` deste projeto |
|---|---|
| Android TV / Google TV | Pode ser aplicável, após identificar modelo, firmware e pacotes reais. |
| Fire OS | Base Android com restrições próprias; avaliar separadamente. |
| LG webOS | **Não aplicável.** Não usar comandos Android `pm`, listas de pacotes Android ou APKs. |
| Samsung Tizen | **Não aplicável.** Usar apenas opções e atualizações documentadas para Tizen. |

Leia [`platforms/lg-webos.md`](platforms/lg-webos.md) antes de orientar uma TV LG com webOS.

## Conteúdo

- `docs/android-tv-original-spec.md` — cópia do procedimento de referência fornecido, preservada para consulta.
- `platforms/lg-webos.md` — limites e fluxo seguro para TVs LG com webOS.
- `CONTRIBUTING.md` — regras para contribuições e segurança.

## Princípios de segurança

1. Confirmar marca, modelo e plataforma antes de qualquer alteração.
2. Nunca remover/desativar componentes essenciais por tentativa e erro.
3. Não executar scripts remotos sem inspeção.
4. Não alegar que RAM foi liberada sem medição antes/depois em condições comparáveis.
5. Não aplicar comandos, listas ou ferramentas de uma plataforma em outra.
6. Registrar o que foi testado, o que falhou e o que não pôde ser verificado.

## Estado

Este é um scaffold inicial de repositório criado a partir do material fornecido. Não representa um repositório remoto publicado no GitHub.
