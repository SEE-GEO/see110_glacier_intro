# SEE110 Klimatmodellering: Glaciärer i Skandinavien under 2000-talet

Det här är repot innehåller kursmaterial för att komma igång med projekt fem: Glaciärer i Skandinavien under 2000-talet, som är en del av kursen SEE110 Klimatmodellering på [Chalmers Tekniska Högskola](https://www.chalmers.se/).


## Instruktioner för studenter som arbetar på OGGM Classroom (Rekommenderas)

- Skapa ett konto via [denna länken](https://classroom.oggm.org/hub/signup). Ditt användarnamn ska följa mallen `cth24_{cid}` t.ex. `cth24_eriholmg`. Din handledare kommer godkänna ditt nya konto så snart som möjligt.
- När ditt konto har blivit gondkänt, logga in och välj  `oggm-v161` från "server options".
- Öppna en terminal `File->New->Terminal` och från din hemkatalog kör följande kommandon:
    ```bash
    gitpuller https://github.com/OGGM/oggm-edu-notebooks master edu_notebooks
    gitpuller https://github.com/SEE-GEO/see110_glacier_intro.git main see110_glacier_intro
    ```
    Detta kommer ladda ner två repon med notebooks som är relevanta för att du ska komma igång med OGGM och projektet.
    Dessa kommer vara tillgängliga i mapparna `edu_notebooks` och `see110_glacier_intro`.

## Instruktioner för att arbeta på egen dator

För att arbeta med projeketet på din egen dator kan du antingen ladda ner filerna med
```bash
git clone https://github.com/SEE-GEO/see110_glacier_intro.git
```
eller som en [zip](https://github.com/SEE-GEO/see110_glacier_intro/archive/refs/heads/main.zip).

Du behöver ha följande python-paket, och paket de är beroende av, installerade för att kunna följa med i instruktionerna:
- oggm
- NumPy
- matplotlib
- juypterlab
- xarray
- netcdf4
- cartopy


## Rapportera fel

Hittar du något du tycker verkar tokigt kan du alltid öppna ett "issue" här på GitHub.
