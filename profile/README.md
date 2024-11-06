# Une nuit pour hacker 2025

## Fonctionnement du Github

Chaque team possède un repo dont le nom correspond à celui de l'équipe.
Voici l'achitecture des repos:

Côté dev:
```shell
├── grX-dev
│   ├── code-review
│   │   └── difficile
│   ├── crypto
│   │   └── difficile
│   ├── misc
│   │   └── moyen
│   ├── osint
│   │   └── moyen
│   ├── sqli
│   │   ├── difficile
│   │   └── moyen
│   └── web
│       └── difficile
```

Côté cyber:
```shell
├── grX-cyb
│   ├── crypto
│   │   └── difficile
│   ├── forensic
│   │   ├── difficile
│   │   └── moyen
│   ├── misc
│   │   └── moyen
│   ├── osint
│   │   └── moyen
│   ├── reverse-pwn
│   │   └── difficile
│   └── web
│       └── moyen
```

Pour les branches, chaque équipe gère à sa manière, le but étant d'avoir une branche `main` qui reste propre et qui pourra servir de source pour déployer la prod

Dans chaque repo d'équipe se trouve des dossiers avec les noms d'utilisateurs de l'équipe. Chaque membre peut donc pousser ses challs individuels dans son dossier attitré.

## Liens utiles

