# 🔧 Jak przetestować stronę Mansfield Story

## Problem: Strona się nie otwiera w środowisku deweloperskim

To **normalne**! Ta strona jest stworzona dla GitHub Pages, nie wymaga serwera deweloperskiego.

---

## ✅ METODA 1: Test lokalny na Twoim komputerze (NAJLEPSZA)

### Krok po kroku:

1. **Pobierz pliki** z tego projektu:
   - `index.html`
   - `newsy.json`
   - Opcjonalnie: `image_6.png` (twoje zdjęcie)

2. **Umieść wszystkie pliki w jednym folderze** na swoim komputerze

3. **Otwórz plik `index.html` bezpośrednio w przeglądarce**:
   - Windows: Kliknij prawym przyciskiem → "Otwórz za pomocą" → Chrome/Firefox/Edge
   - Mac: Przeciągnij plik na ikonę przeglądarki
   - Lub po prostu kliknij dwukrotnie na `index.html`

4. **Strona powinna się otworzyć!** 🎉

---

## ✅ METODA 2: Wrzuć od razu na GitHub Pages (ZALECANA)

To najszybszy sposób na zobaczenie działającej strony:

### 1. Stwórz repozytorium na GitHub
- Zaloguj się na GitHub.com
- Kliknij "+" → "New repository"
- Nazwa: `mansfield-story`
- Publiczne
- NIE zaznaczaj "Add README"

### 2. Wrzuć pliki
- Na stronie repo kliknij "Add file" → "Upload files"
- Przeciągnij: `index.html`, `newsy.json`, `image_6.png`
- Kliknij "Commit changes"

### 3. Włącz GitHub Pages
- Idź do **Settings** (w repo)
- Kliknij **Pages** (w menu po lewej)
- Source: wybierz **main** branch
- Folder: **/ (root)**
- Kliknij **Save**

### 4. Poczekaj 1-2 minuty
GitHub pokaże Ci link, np:
```
https://twoja-nazwa.github.io/mansfield-story/
```

### 5. Gotowe! 🚀
Kliknij w link - strona działa!

---

## ✅ METODA 3: Prosty serwer lokalny (dla zaawansowanych)

Jeśli masz Python na komputerze:

```bash
# Otwórz terminal/cmd w folderze z plikami
cd ścieżka/do/folderu

# Python 3
python -m http.server 8000

# Otwórz w przeglądarce:
# http://localhost:8000/index.html
```

---

## 🐛 Rozwiązywanie problemów

### Problem: "Nie można załadować newsy.json"
**Rozwiązanie**: Upewnij się, że plik `newsy.json` jest w tym samym folderze co `index.html`

### Problem: Nie widać zdjęcia reportera
**Rozwiązanie**: Dodaj swoje zdjęcie jako `image_6.png` lub strona użyje placeholder

### Problem: Formularz kontaktowy nie działa
**Rozwiązanie**: To normalne! Musisz:
1. Załóż konto na Formspree.io (darmowe)
2. Stwórz nowy formularz
3. Skopiuj swój Form ID
4. W `index.html` znajdź linię ~292 i zamień `YOUR_FORM_ID` na swój ID

### Problem: Strona wygląda źle
**Rozwiązanie**: Sprawdź połączenie internetowe - strona używa CDN dla Tailwind CSS i Font Awesome

---

## 📋 Checklist przed startem:

- [ ] Mam plik `index.html` w folderze
- [ ] Mam plik `newsy.json` w tym samym folderze
- [ ] Mam zdjęcie `image_6.png` (opcjonalne)
- [ ] Wszystkie 3 pliki są w **tym samym folderze**
- [ ] Otworzyłem `index.html` w przeglądarce
- [ ] Lub wrzuciłem na GitHub Pages

---

## 💡 Dlaczego to jest lepsze niż React/backend?

✅ **Zero konfiguracji** - żadnego npm, yarn, node_modules  
✅ **Zero kosztów** - GitHub Pages to 100% za darmo  
✅ **Szybki start** - wrzuć pliki i działa  
✅ **Łatwa edycja** - newsy w prostym JSON  
✅ **Zawsze działa** - żadnych zależności, które się psują  

---

## 🎯 Rekomendacja

**Pomiń testowanie lokalne** → Wrzuć od razu na GitHub Pages!

To zajmie 5 minut i od razu zobaczysz działającą stronę na prawdziwym URL.

---

## 🆘 Potrzebujesz pomocy?

1. Sprawdź czy wszystkie pliki są w jednym folderze
2. Spróbuj otworzyć `index.html` bezpośrednio w przeglądarce
3. Jeśli dalej nie działa, wrzuć na GitHub Pages - to **zawsze** zadziała!

**Powodzenia! 🚀**

Stwórz swoją historię. Share your story. 🇵🇱🇬🇧