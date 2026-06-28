# 🦆 CuaksApp

**La app de mensajería del Ministro Acuacfiestas**

Una PWA que simula WhatsApp con el Ministro Acuacfiestas como personaje interactivo para juegos de pistas.

---

## 🚀 Deploy en Vercel (gratis, 0€)

### Opción A — GitHub + Vercel (recomendado)

1. Sube esta carpeta a un repositorio de GitHub
2. Ve a [vercel.com](https://vercel.com) → New Project → Import tu repo
3. En configuración, asegúrate de que **Output Directory** sea `public`
4. Deploy → ¡listo!

### Opción B — Vercel CLI

```bash
npm i -g vercel
cd cuaksapp
vercel --prod
```

---

## 📁 Estructura

```
cuaksapp/
├── public/
│   ├── index.html      ← App principal (todo en uno)
│   ├── manifest.json   ← PWA manifest
│   ├── sw.js           ← Service Worker (offline)
│   ├── icon-192.svg    ← Icono PWA pequeño
│   └── icon-512.svg    ← Icono PWA grande
├── vercel.json         ← Configuración de despliegue
└── README.md
```

---

## 🎮 Cómo funciona

1. El jugador abre la app y ve la lista de chats estilo WhatsApp
2. Pincha en **🦆 Ministro Acuacfiestas**
3. Habla con él — responde con su rollo chulo y macarra
4. Cuando pide una pista, el Ministro exige una **foto grupal**
5. El jugador adjunta la foto → el Ministro la "analiza"
6. Aparece la pista: **🏖️ IR AL BALCÓN 🏖️**

---

## 📱 Instalar como app (PWA)

- **Android Chrome**: Menú → "Añadir a pantalla de inicio"
- **iOS Safari**: Compartir → "Añadir a pantalla de inicio"
- **Desktop Chrome**: Icono de instalación en la barra de direcciones

---

## 🛠️ Personalización

Todo el contenido está en `public/index.html`. Para cambiar las pistas o respuestas, edita el objeto `respuestas` en el `<script>` al final del archivo.

Para añadir más misiones, modifica la función `acuacRespond()`.

---

*"El cloro es pa los débiles" — Ministro Acuacfiestas* 🦆
