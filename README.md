# Fontsource

[![Generic badge](https://img.shields.io/badge/fontsource-passing-brightgreen)](https://github.com/fontsource/fontsource) [![codecov](https://codecov.io/gh/fontsource/fontsource/branch/main/graph/badge.svg?token=QEJJF3SE62)](https://codecov.io/gh/fontsource/fontsource) [![Monthly Downloads](https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Ffontsource%2Fdownload-stat-aggregator%2Fmaster%2Fdata%2FbadgeMonth.json)](https://github.com/fontsource/download-stat-aggregator) [![Total Downloads](https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Ffontsource%2Fdownload-stat-aggregator%2Fmaster%2Fdata%2FbadgeTotal.json)](https://github.com/fontsource/download-stat-aggregator) [![License](https://badgen.net/badge/license/MIT/green)](https://github.com/fontsource/fontsource/blob/main/LICENSE) [![GitHub stars](https://img.shields.io/github/stars/fontsource/fontsource.svg?style=social&label=Star)](https://github.com/fontsource/fontsource/stargazers)

Un monorepo in aggiornamento ricco di font self-hostable Open Source, raccolti in pacchetti NPM individuali!

La nostra documentazione completa può essere trovata [qui](https://fontsource.org/).

In alternativa puoi vedere la lista dei font supportati in formato Markdown
[qui](https://github.com/fontsource/fontsource/blob/main/FONTLIST.md).

---

- Il self-hosting porta **guadagni di performance significativi** visto che caricare i font da servizi esterni, come
Google Fonts, porta a richieste aggiuntive (render blocking). Per dare una prospettiva, in siti semplici si è visto che
_raddoppia_ i tempi di caricamento visuale.
  I benchmark si trovano [qui](https://github.com/HTTPArchive/almanac.httparchive.org/pull/607) e
  [qui](https://github.com/reactiflux/reactiflux.com/pull/21).

- I font rimangono **version locked**. Google aggiorna spesso i font
[senza preavviso](https://github.com/google/fonts/issues/1307), cosa che può interferire con il tuo ambiente di
produzione. Così invece puoi gestire i tuoi font come faresti con una normale dipendenza NPM.

- **Privacy**. Google traccia l'utilizzo dei loro font. Usare Google Fonts **NON** è GDPR-compliant. Questa soluzione
sì.

- I font vengono **caricati offline**. Oltre a beneficiarne le PWA, possono esserci altre situazioni, ad esempio
lavoro da remoto, come in aereo o in treno, dove la mancanza di connessione affidabile può impedire il caricamento dei
font.

- **Supporto per font esterni a Google Font**. Questo repository si evolve costantemente con
[altri font Open Source](https://github.com/fontsource/fontsource/blob/main/FONTLIST.md). Sentiti libero di contribuire.

## API

Controlla la documentazione [qui](https://fontsource.org/docs/api/introduction).

## Migrare da versioni precedenti

Vedi [CHANGELOG.md](https://github.com/fontsource/fontsource/blob/main/CHANGELOG.md) per maggiori dettagli.

## Aggiungere nuovi font

Per i font Open Source che non sono automaticamente aggiornati dall'ecosistema Google, abbiamo un packager generico che
costruisce file CSS pronti per il progetto.

Fai una richiesta creando una [issue](https://github.com/fontsource/fontsource/issues)!
Se vuoi fare una PR, controlla la documentazione per sapere come impacchettare i font da solo
[qui](https://github.com/fontsource/fontsource/blob/main/scripts/generic/README.md).

## Licensing

È importante leggere sempre la licenza di ogni font utilizzato.
La maggior parte dei font in questa collezione usa la SIL Open Font Licenze, v1.1. Alcuni font la licenza Apache 2. I
font di Ubuntu usano la licenza Ubuntu Font v1.0.

Puoi trovare la licenza specifica nel `README.md` di ogni pacchetto.

## Altre note

Sentiti libero di mettere una star e di contribuire al repo con nuove idee che vogliano migliorare le performance di
caricamento del font, oltre ad espandere la libreria esistente. Ogni suggerimento o idea può espresso o espressa
tramite una [issue](https://github.com/fontsource/fontsource/issues).

## Community Sponsors

<p align="center" width="100%">
  <a href="https://vercel.com/?utm_source=fontsource&utm_campaign=oss">
    <img width="33%" src="https://www.datocms-assets.com/31049/1618983297-powered-by-vercel.svg">
  </a>
  &nbsp;&nbsp;
  <a href="https://www.jsdelivr.com/">
    <img width="33%" src="https://raw.githubusercontent.com/jsdelivr/jsdelivr-media/master/default/svg/jsdelivr-logo-horizontal.svg">
  </a>
</p>
