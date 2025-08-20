# Setup

## Installere vertkøy

### Sette opp GitHub og SSH key

Sette opp SSH key:

```sh
ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
```

Lag GitHub konto.

Når du er logget inn gå til Profile -> Settings -> SSH and GPG keys -> New Key. Legg til public rsa key.

## Installer fnm og node

Kjør følgende for å installere `fnm` (fast node manager) og så nyeste node.

```sh
curl -fsSL https://fnm.vercel.app/install | bash
fnm install latest
```

## Installer pnpm

Kjør følgende for å installere `pnpm` (performant node package manager).

```sh
curl -fsSL https://get.pnpm.io/install.sh | sh -
```

## Installer Docker Desktop

[Gå til docker sin nettside og last ned Docker Desktop (nederst)](https://docs.docker.com/desktop/)

For windows, pass på at du har [koblet til WSL](https://docs.docker.com/desktop/features/wsl/)

## Last ned cenv

Kjør følgende for å laste ned `cenv` (kontroll av .env filer).

```sh
curl -fsSL https://raw.githubusercontent.com/echo-webkom/cenv/refs/heads/main/install.sh | bash
```

## Ferdig!

Nå kan du begynne med [første prosjekt.](portfolio.md)
