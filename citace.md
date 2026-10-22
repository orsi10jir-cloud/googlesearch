# Citace a zdroje – projekt `googlesearch`

**Autor:** Jiří  
**Projekt:** Google Search – vlastní front-end (CS50 Web, Project 0: Search) + doplňující zadání  
**Web (GitHub Pages):** https://orsi10jir-cloud.github.io/googlesearch/  
**Repozitář:** https://github.com/orsi10jir-cloud/googlesearch

---

## 1. Zadání

- Harvard University. *CS50's Web Programming with Python and JavaScript – Project 0: Search*. https://cs50.harvard.edu/web/projects/0/search/ [cit. 2026-10-22].
- Doplňující zadání vyučujícího: stránka s formulářovými prvky, odkazy na validaci HTML/CSS, odkaz na citace, odkaz na portfolio, video.

## 2. Použité zdroje

- Google LLC. *Google Search*. https://www.google.com/ [cit. 2026-10-22]. – vzor vzhledu; zjištění GET parametrů `q` (dotaz) a `btnI` (I'm Feeling Lucky).
- Google LLC. *Google Images*. https://images.google.com/ [cit. 2026-10-22]. – parametr `tbm=isch` (vyhledávání obrázků).
- Google LLC. *Google Advanced Search*. https://www.google.com/advanced_search [cit. 2026-10-22]. – parametry `as_q`, `as_epq`, `as_oq`, `as_eq` a rozložení stránky.
- Mozilla. *MDN Web Docs – &lt;form&gt;, &lt;input&gt;, &lt;select&gt;, &lt;textarea&gt;, &lt;datalist&gt;, &lt;output&gt;, &lt;progress&gt;, &lt;meter&gt;, &lt;fieldset&gt;*. https://developer.mozilla.org/ [cit. 2026-10-22].
- W3C. *Markup Validation Service*. https://validator.w3.org/ [cit. 2026-10-22].
- W3C. *CSS Validation Service*. https://jigsaw.w3.org/css-validator/ [cit. 2026-10-22].
- GitHub. *GitHub Pages documentation*. https://docs.github.com/pages [cit. 2026-10-22].
- Anthropic. *Claude* (AI asistent, claude.ai). https://claude.ai [cit. 2026-10-22]. – vygenerování kódu všech stránek, CSS a tohoto souboru.

## 3. Použité prompty

### Prompt 1 – zadání celého projektu (vloženo do Claude)

```
1. Vytvořte na GitHubu nový repozitář googlesearch
2. Otevřete (naklonujte) repozitář ve VS Code jako nový projekt
3. Vytvořte web dle zadání: https://cs50.harvard.edu/web/projects/0/search/
4. Commit & Push a pomocí Github Pages sdílejte řešení (sdílejte link)

Navíc k zadání
1. Vytvořte další stránku v rámci výše uvedeného projektu, která bude obsahovat co největší
   množství formulářových prvků (input, select, checkbox, radio, textarea, button, ...).
   Formulářové prvky nemusí být funkční. Cílem je ukázat, že umíte vytvořit různé typy formulářů.
2. Na všech stránkách projektu budou 2 odkazy na validaci HTML a CSS. Odkazy budou směřovat
   na validátory: https://validator.w3.org/ a https://jigsaw.w3.org/css-validator/ nastavené tak,
   aby validovaly kód dané stránky.
3. Na všech stránkách projektu bude odkaz na soubor obsahující citace a zdroje, které jste použili
   při tvorbě projektu. Odkaz bude na github.com/vášúčet/googlesearch/citace.md.
   Citace obsahují použité prompty (nechte to generovat AI, co vám generuje kód).
4. V rámci google search projektu budete mít i odkaz na své portfolio.
5. Vytvořte video, ve kterém ukážete, že jste splnili všechny body zadání.

V rámci čtvrtletní práce zkontrolujte:
1. všechny stránky obsahují odkazy na validaci html a css.
2. všechny stránky obsahují odkaz na soubor s citacemi a zdroji.
3. všechny odkazy fungují a vedou na správné místo.
4. formuláře, které nefungují označte jako nefunkční (např. šedivě, nebo poznámkou) nebo vymažte.

(+ vložený text zadání CS50 Project 0: Search)
Tohle potřebuji udělat, videa uděláme až jako poslední. Řekni mi, jak budeme postupovat.
```

### Prompt 2 – otevření v Live Serveru

```
Chtěl jsem to otevřít v Live Serveru a tohle se napsalo:
"Open a folder or workspace... (File -> Open Folder)"
```

### Prompt 3 – vytvoření a nahrání projektu

```
Já to asi nemám naklonované, tak udělej to, kdyby ses potřeboval dostat k PC, webu
a VS Code, tak to bude hotové, udělej co potřebuješ.
```

### Prompt 4 – oprava chyb v terminálu (git)

```
(vložený výpis terminálu: git init, "Author identity unknown",
 "src refspec main does not match any")
Tohle je výpis terminálu.
```

### Prompt 5 – nahrání všech stránek na GitHub

```
(snímek obrazovky VS Code po úspěšném git push)
Tak kde a co, jak to mám udělat?
```

### Prompt 6 – odkaz na portfolio

```
https://github.com/orsi10jir-cloud
```

### Prompt 7 – kontrola a dokončení

```
Tak to udělej ty, co můžeš, a já pak udělám to natáčení.
```

### Prompt 8 – oprava odkazu na portfolio

```
A to portfolio musí být tohle: https://orsi10jir-cloud.github.io/EPOX/
```

### Prompt 9 – portfolio jako rozcestník

```
Dobře, musíme udělat web nebo portfolio, ze kterého se půjde proklikat na další
funkční weby a projekty, takže fakt nevím, jak to mám udělat.
(odpověď: portfolio na hlavním webu https://orsi10jir-cloud.github.io/)
```

## 4. Prohlášení

Kód projektu byl vygenerován s pomocí AI (Claude, Anthropic) na základě výše uvedených promptů.
Autor výsledek zkontroloval, otestoval funkčnost formulářů a ověřil validitu HTML a CSS pomocí validátorů W3C.
Logo Google ani jiné grafické prvky Google nebyly kopírovány – nadpis stránky je vlastní textový.
