# Vasaloppet-fakta

En enkel GitHub Pages-sajt med fakta om Vasaloppet och Gustav Vasa samt ett interaktivt quiz.

## Sidor

| Fil | Beskrivning |
|-----|-------------|
| `index.html` | Faktasida med 34 fakta om Vasaloppet och Gustav Vasa |
| `quiz.html` | Interaktivt quiz med 13 frågor och automatisk rättning |

## Aktivera GitHub Pages

1. Gå till **Settings** i repot.
2. Välj **Pages** i vänstermenyn.
3. Under *Source*, välj **Deploy from a branch**.
4. Välj branch **main** och mapp **/ (root)**.
5. Klicka **Save**.

Efter några minuter är sajten tillgänglig på:

```
https://magpern.github.io/Vasaloppet-fakta/
```

## QR-kod till quizet

Skanna koden nedan för att öppna quizet direkt på din mobil:

[![QR-kod till quizet](qr-quiz.png)](https://magpern.github.io/Vasaloppet-fakta/quiz.html)

## Lokal förhandsvisning

Öppna `index.html` direkt i webbläsaren, eller starta en lokal server:

```bash
python3 -m http.server 8080
# Besök sedan http://localhost:8080
```