# 🎾 Padel Ranking

**Padel Ranking** busca ser una **app/plataforma** en donde jugadores de pádel puedan **trackear su progreso en el deporte y competir en un ranking global** accesible para todos.

La idea es brindar a los jugadores un medio confiable para registrar los partidos que juegan habitualmente, contabilizar **victorias y derrotas**, y en base a eso calcular un **puntaje global**.  
De esta forma, cada jugador puede conocer a qué **categoría del deporte pertenece** y cómo evoluciona en el tiempo.  

En esta etapa inicial, el sistema será **básico** ya que no existe una manera de verificar con total certeza la validez de los partidos cargados.  
El lanzamiento estará enfocado en la **ciudad de La Plata**, con geolocalización de jugadores y clubes de pádel locales.

---

## 🚀 MVP

### 📝 Registro de partidos
- Formulario simple: rival, fecha, resultado (win/loss).
- Opción de anotar el marcador.

### 📜 Historial personal
- Lista cronológica de partidos jugados.
- Visualización rápida de victorias (**verde**) y derrotas (**rojo**).

### 📊 Estadísticas básicas
- Total de partidos jugados.
- Cantidad de victorias y derrotas.
- Porcentaje de derrotas.
- Racha de victorias o partidos jugados.

### 🏆 Ranking global inicial
- Cada jugador tiene un **puntaje global**.
- Sistema de puntos básico: **+10 por victoria / -5 por derrota**.
- Ranking público visible para todos los usuarios.

### 👤 Perfil de jugador
- Foto, nombre, ciudad/club.
- Puntaje global y estadísticas básicas.

---

## 🛠️ Tecnologías previstas
- **Backend:** Laravel 11 (API REST) + MySQL
- **Web:** Next.js 14 (React, TypeScript, TailwindCSS)
- **Mobile:** Expo (React Native)
- **Autenticación:** Laravel Sanctum
- **UI:** TailwindCSS / NativeWind
- **Infra:** Railway / Render (API & DB), Vercel (Web), Expo Go (Mobile)

---

## 📍 Foco inicial
El desarrollo inicial estará orientado a la comunidad de pádel de **La Plata (Buenos Aires, Argentina)**, con el objetivo de luego expandirse a otras ciudades y clubes.

---

## 👨‍💻 Autor
**Thomas Chaurés**  
[GitHub](https://github.com/ThomasChaures) | [LinkedIn](https://www.linkedin.com/in/thomas-chaures-6b1722177/)
