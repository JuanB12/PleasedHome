<div align="center">

<img src="https://dev-to-uploads.s3.amazonaws.com/uploads/articles/th5xamgrr6se0x5ro4g6.png" alt="Logo de PleasedHome" width="120" />

# 🏠 PleasedHome

**Plataforma web para contratar servicios domésticos y de cuidado de niños, que conecta a familias con proveedores calificados y confiables.**

![Next.js](https://img.shields.io/badge/Next.js-14-0B1220?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-18-3776AB?style=flat-square&logo=react&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-0B1220?style=flat-square&logo=typescript&logoColor=FFD43B)
![Tailwind](https://img.shields.io/badge/Tailwind_CSS-3776AB?style=flat-square&logo=tailwindcss&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Neon-0B1220?style=flat-square&logo=postgresql&logoColor=FFD43B)

</div>

---

## 📌 Descripción

Encontrar a alguien de confianza para el hogar o para cuidar a los niños suele depender del voz a voz. **PleasedHome** centraliza ese proceso: los proveedores publican sus servicios y su experiencia, y los clientes buscan, comparan por calificaciones y contratan.

## ✨ Funcionalidades

- 🔎 **Búsqueda avanzada** por tipo de servicio, ubicación, tarifa y calificación.
- 👤 **Perfiles detallados** de proveedores: habilidades, experiencia y disponibilidad.
- ⭐ **Reseñas y calificaciones** (escala de 1 a 10) para decidir con información.
- 📄 **Hojas de vida** adjuntas y actualizables.
- 📅 **Agenda** de entrevistas y servicios directamente con el proveedor.
- 🛠️ **Panel de administración** para moderar contenido y gestionar usuarios.

## 🗂️ Estructura

```
├── app/
│   ├── (root)/               # Página de inicio
│   ├── (login)/  (sign-up)/  # Autenticación
│   └── (dashboard)/          # Panel: publicaciones y perfil
├── components/               # Componentes de UI (Navbar, PublishCard, StarRating…)
├── actions.ts                # Server Actions
└── bd/services.sql           # Esquema de la base de datos
```

## 🎨 Paleta de colores

| Uso | Color |
|---|---|
| Principal: navegación, encabezados y marca | `#00796B` |
| Secundario: elementos interactivos e íconos | `#4DB6AC` |
| Fondo limpio | `#FFFFFF` |
| Fondo alterno: tarjetas y paneles | `#F5F5F5` |
| Llamados a la acción y alertas | `#FFA000` |

## 🚀 Cómo ejecutarlo

```bash
# 1. Clonar e instalar
git clone https://github.com/JuanB12/PleasedHome.git
cd PleasedHome
npm install

# 2. Variables de entorno: copiar el ejemplo y poner tu conexión a PostgreSQL
cp .env.example .env

# 3. Servidor de desarrollo
npm run dev
```

Abre [http://localhost:3000](http://localhost:3000).

## 🔗 Recursos

- [Mockup en Figma](https://www.figma.com/design/YXvZzmoRoUVdnWMIf3VBS4/pleasedHome?node-id=0-1&t=7vqjbB9ZM91UT75x-1)

## 👥 Equipo

- [Angie Moya](https://github.com/AngieMoya)
- [Jeider Foronda](https://github.com/Jeider-fp)
- [Juan Barrios](https://github.com/JuanB12)
