# PC Virtual Lab

Laboratório educacional usando GitHub Actions.

## O que este projeto demonstra

- GitHub Actions
- Linux Ubuntu
- XFCE
- XRDP
- Tailscale
- GitHub Secrets

## Como executar

1. Abra a aba Actions.
2. Selecione "PC Virtual - Laboratório".
3. Clique em "Run workflow".
4. Aguarde a instalação.
5. Consulte os logs para encontrar o IP do Tailscale.

## Credenciais

O projeto não armazena senhas no código.

São necessários dois GitHub Secrets:

- `TAILSCALE_AUTHKEY`
- `RDP_PASSWORD`

Nunca coloque esses valores diretamente neste repositório.

## Aviso

Este é um laboratório temporário. O ambiente é destruído quando a execução do GitHub Actions termina.
