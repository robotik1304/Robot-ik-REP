# Robot-IK App — Prototipo de interfaces

Aplicación web interna de gestión técnica para **Robot-IK**, empresa de robotización industrial.

## 🔗 Ver el prototipo online

👉 **[robot-ik-app.github.io/Robot-ik-REP](https://robotik1304.github.io/Robot-ik-REP)**

## 📱 Stack técnico

- HTML + CSS + JS vanilla — archivos `.html` autocontenidos
- Logo embebido como base64
- Fuentes: Sora + JetBrains Mono (Google Fonts)
- Light mode forzado, diseño responsive (desktop + móvil)

## 🎨 Paleta de colores

| Variable | Color |
|---|---|
| `--brand-blue` | `#0055A4` |
| `--brand-blue-dark` | `#003D7A` |
| `--brand-blue-light` | `#E8F0FB` |
| `--accent` | `#F4A623` |
| `--bg` | `#F0F2F7` |
| `--text-primary` | `#1A1E2E` |

## 👥 Roles de usuario

| Rol | Acceso |
|---|---|
| **Técnico** | Robots, consumibles, repuestos |
| **Administración** | Todo lo anterior + precios + usuarios |

> Los roles se asignan al crear el usuario — nunca en el login.

## 📂 Pantallas

| Archivo | Pantalla |
|---|---|
| `index.html` | Índice de pantallas |
| `html/p03_ficha_cliente.html` | Ficha de cliente |
| `html/p04_consumibles.html` | Catálogo de consumibles |
| `html/p05_repuestos.html` | Catálogo de repuestos |
| `html/p06_alta_robot.html` | Alta / edición de robot |
| `html/p07_ficha_robot.html` | Ficha de robot |
| `html/p08_lista_clientes.html` | Lista de clientes |
| `html/p09_conjuntos.html` | Conjuntos |
| `html/p10_base_datos.html` | Base de datos (catálogo maestro) |
| `html/p11_usuarios.html` | Usuarios y roles |

## 🚀 Próximos pasos

- [ ] Conectar a backend (API REST)
- [ ] Autenticación real con JWT
- [ ] Base de datos (PostgreSQL / Supabase)
- [ ] Módulo de cotizaciones
