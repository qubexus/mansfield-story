# 🗞️ Mansfield Story - Dwujęzyczny Portal Newsowy

**Prosty, darmowy i szybki portal newsowy dla Polonii w Mansfield.**

---

## 🚀 Jak używać

### Krok 1: Edytuj wiadomości
Otwórz plik `newsy.json` i dodaj swoje wiadomości:

```json
{
  "id": 7,
  "breaking": false,
  "title_pl": "Twój tytuł po polsku",
  "title_en": "Your title in English",
  "text_pl": "Treść wiadomości po polsku...",
  "text_en": "News content in English...",
  "image": "https://link-do-obrazka.jpg",
  "date": "2025-03-15",
  "link": "https://x.com/twoj-tweet"
}
```

### Krok 2: Dodaj swój Formspree ID
W pliku `index.html` znajdź linię (~292):
```html
<form id="contact-form" action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
```

Zamień `YOUR_FORM_ID` na swój ID z [Formspree.io](https://formspree.io) (darmowe konto).

### Krok 3: Dodaj zdjęcie reportera
Umieść swoje zdjęcie jako `image_6.png` w tym samym folderze co `index.html`.

### Krok 4: Wrzuć na GitHub Pages
1. Stwórz repozytorium na GitHubie
2. Wrzuć pliki: `index.html`, `newsy.json`, `image_6.png`
3. Włącz GitHub Pages w Settings → Pages
4. Gotowe! 🎉

---

## 📁 Struktura plików

```
mansfield-story/
│
├── index.html       # Główna strona (wszystko w jednym pliku)
├── newsy.json       # Twoje wiadomości
├── image_6.png      # Zdjęcie reportera (opcjonalne)
└── README.md        # Ten plik
```

---

## ✨ Funkcje

✅ **Dwujęzyczność (PL/EN)** - Przełącznik zapisuje wybór w przeglądarce  
✅ **Breaking News** - Czerwony alert na górze strony  
✅ **Responsywny design** - Wygląda świetnie na telefonie  
✅ **Zero kosztów** - GitHub Pages + Formspree (darmowe)  
✅ **Szybki** - Jeden plik HTML, bez komplikacji  
✅ **Profesjonalny** - Granat, złoto, i nowoczesny design  

---

## 🎨 Kolory brandingowe

- **Deep Navy**: `#002147`
- **Gold**: `#D4AF37`
- **Breaking Red**: `#DC2626`

---

## 📝 Jak edytować wiadomości

1. Otwórz `newsy.json`
2. Dodaj nowy obiekt do tablicy `news`
3. Zapisz i wrzuć na GitHub
4. Strona zaktualizuje się automatycznie!

**Tip:** Ustaw `"breaking": true` dla pilnych wiadomości.

---

## 🌐 Hosting na GitHub Pages

1. Stwórz repo (np. `mansfield-story`)
2. Wrzuć pliki przez "Add file" → "Upload files"
3. Idź do **Settings** → **Pages**
4. Source: `main` branch, folder: `/ (root)`
5. Zapisz - po chwili dostaniesz link!

**Twoja strona będzie pod:**  
`https://twoja-nazwa.github.io/mansfield-story/`

---

## 💡 FAQ

**Q: Jak zmienić kolory?**  
A: W `index.html` znajdź sekcję `<style>` na górze i zmień wartości `#002147` (navy) i `#D4AF37` (gold).

**Q: Czy muszę używać Formspree?**  
A: Nie, możesz zastąpić formularz linkiem do Twittera/maila, ale Formspree jest najwygodniejsze.

**Q: Jak dodać więcej newsów?**  
A: Dodaj kolejne obiekty do tablicy w `newsy.json`.

**Q: Czy mogę zmienić zdjęcie reportera?**  
A: Tak! Zamień `image_6.png` lub zmień nazwę w linii ~268 w `index.html`.

---

## 🆘 Wsparcie

Masz problem? Zgłoś na: **contact@mansfieldstory.com**

---

**Stwórz swoją historię. Share your story.** 🇵🇱🇬🇧