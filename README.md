# 🌐 Frontend 2025 alap

Ez egy **Vue 3 + Vite + Vuetify** alapú frontend alkalmazás, amely **Pinia** állapotkezelést és **Vue Router**-t használ.  
Célja egy gyors, moduláris és bővíthető frontend környezet biztosítása.

---

## 🚀 Tech Stack

- ⚡ [Vue 3](https://vuejs.org/) – reaktív keretrendszer
- ⚡ [Vite](https://vitejs.dev/) – gyors fejlesztői környezet és build tool
- 🎨 [Vuetify 3](https://vuetifyjs.com/) – Material Design komponensek
- 📦 [Pinia](https://pinia.vuejs.org/) – állapotkezelés
- 🛣️ [Vue Router](https://router.vuejs.org/) – útvonalkezelés
- 🌐 [Axios](https://axios-http.com/) – API hívások

---

# 🛠 Telepítés & Indítás


## Függőségek telepítése
```bash
pnpm install
```
## Fejlesztői mód indítása
```bash
pnpm dev
```
## Production build készítése
```bash
pnpm build
```
👉 Az elkészült build a dist/ mappába kerül.

## Projektstruktúra
## 📂 Projektstruktúra

```text
src/
 ├─ assets/        statikus fájlok (képek, ikonok, CSS, stb.)
 ├─ components/    újrafelhasználható Vue komponensek
 ├─ router/        útvonalak és guard-ok
 ├─ store/         Pinia store-ok
 ├─ views/         oldalnézetek (HomeView, AboutView, stb.)
 ├─ App.vue        gyökér komponens
 └─ main.js        belépési pont
```

## Hasznos script-ek
```bash
pnpm dev – fejlesztői szerver
pnpm build – production build
pnpm preview – build előnézet
```

## Fejlesztői infó
```text
Fejlesztő: Buzási Gergő
Repo: Frontend2025
```