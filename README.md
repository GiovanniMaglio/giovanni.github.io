# Sito personale di Giovanni — GitHub Pages + Jekyll (Minimal Mistakes)

## 1) Crea il repository
1. Vai su GitHub e crea un repo **pubblico** chiamato `tuo-username.github.io` (es. `giovanni.github.io`).
2. Scarica questo pacchetto e unzippalo.
3. Carica tutti i file nel repo e fai commit su `main`.

## 2) Abilita GitHub Pages
- Vai su **Settings → Pages** e verifica che il branch `main` sia selezionato.
- L'URL sarà `https://tuo-username.github.io`.

## 3) Personalizza
- Modifica `_config.yml`: nome, email, link GitHub/LinkedIn, descrizione.
- Sostituisci `assets/img/avatar.svg` con la tua foto (stesso nome o aggiorna il path).
- Aggiungi il tuo CV in `assets/CV_Giovanni.pdf` e aggiorna il link in `/about/`.
- Aggiorna i link in **Progetti** e **Ricerca**.

## 4) Post e Pagine
- Post del blog in `_posts/` come `YYYY-MM-DD-titolo.md`.
- Pagine statiche in `/` (già presenti: `about`, `projects`, `research`, `contact`).

## 5) Modifiche locali (opzionale)
Per provare il sito in locale:
```bash
gem install bundler
bundle init
# Aggiungi al Gemfile:
# gem "github-pages", group: :jekyll_plugins
bundle add github-pages --group=jekyll_plugins
bundle exec jekyll serve
```
> Su GitHub Pages non serve il Gemfile: il build avviene in cloud.

Buon lavoro!
