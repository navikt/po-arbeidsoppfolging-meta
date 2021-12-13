# PO Arbeidsoppfølging meta repository

Meta repository med linking til alle applikasjonene våre

## Setup
For å clone ferdig setup
```
npm i -g meta
meta git clone https://github.com/navikt/po-arbeidsoppfolging-meta.git
```
Hvis du allerede har clonet
```
npm i -g meta
meta git update
```

## Legg til nytt repo
Legge til nytt repo `meta project import [team/repo] [repo url]`

Når du har lagt til et nytt repo husk å legge til mappen i `vcs.xml`. Dette kan også gjøres under `Preferences | Version Control` i intelliJ

For å se mer om hvordan meta funker se: https://github.com/mateodelnorte/meta