# Moje MP3

Jednostránkový prehrávač: 5 skladieb, ku každej 2 verzie. Súbory sú priamo v repozitári, takže ich uvidí a prehrá každý.

## Názvy súborov

Nahraj 10 súborov s presne týmito názvami (alebo ich zmeň v `index.html` v časti `TRACKS`):

```
1-v1.mp3  1-v2.mp3
2-v1.mp3  2-v2.mp3
3-v1.mp3  3-v2.mp3
4-v1.mp3  4-v2.mp3
5-v1.mp3  5-v2.mp3
```

## Postup na GitHube

1. Na github.com klikni **New repository**, daj mu názov (napr. `moje-mp3`), nechaj ho **Public** a vytvor ho.
2. Klikni **uploading an existing file** (alebo **Add file → Upload files**).
3. Pretiahni tam `index.html` a všetkých 10 `.mp3` súborov, potom **Commit changes**.
4. Choď do **Settings → Pages**. V časti **Build and deployment** vyber **Deploy from a branch**, branch **main**, priečinok **/ (root)** a daj **Save**.
5. Po minúte-dvoch bude stránka na `https://TVOJ-NICK.github.io/moje-mp3/`. Tento odkaz pošli komukoľvek.

## Poznámky

- Cez web upload je limit 25 MB na súbor. Cez `git` je limit 100 MB.
- Ak neskôr nahradíš mp3 súbor novým s rovnakým názvom, stránka ho po obnovení použije.
- Názvy skladieb zmeníš v `index.html` v poli `TRACKS` (riadok `title`).
