# 🌍 Sistema de Gestión — Agencia de Viajes

Sistema web desarrollado en JavaScript vanilla con Programación Orientada a Objetos, que simula la gestión completa de una agencia de viajes con dos roles de usuario: **Administrador** y **Cliente**.

🔗 **Demo en vivo:** [https://rodrigoavogadro-uy.github.io/agencia-viajes/](https://rodrigoavogadro-uy.github.io/agencia-viajes/)

---

## 🔑 Credenciales de prueba

Para probar el sistema sin necesidad de registrarte, usá alguno de estos usuarios precargados:

**Administrador**
- Usuario: adminprueba
- Contraseña: `123`

**Cliente**
- Usuario: `cliente_prueba`
- Contraseña: `123`

También podés registrarte como cliente nuevo desde la pantalla de inicio.

---

## ✨ Funcionalidades

### Como Cliente
- Explorar destinos disponibles con imágenes, precios y descripción
- Reservar destinos pagando con dinero o millas
- Ver destinos en oferta
- Consultar historial de reservas y cancelar las pendientes

### Como Administrador
- Aprobar o cancelar reservas pendientes (con validación de cupos y saldo del cliente)
- Agregar nuevos destinos
- Administrar destinos existentes (aumentar/disminuir cupos, activar/pausar, poner en oferta)
- Ver informe de ganancias por destino

### Validaciones destacadas
- Verificación de tarjeta de crédito mediante el **algoritmo de Luhn**
- Validación de contraseña segura (mayúscula, minúscula y número)
- Control de cupos disponibles por destino
- Prevención de reservas duplicadas para un mismo destino

---

## 🛠️ Tecnologías

- **HTML5** — estructura semántica
- **CSS3** — estilos, animaciones y diseño responsive
- **JavaScript (ES6+)** — lógica de negocio con clases, POO y manipulación del DOM

Sin frameworks ni librerías externas — todo implementado desde cero.

---

## 📁 Estructura del proyecto

```
agencia-viajes/
├── index.html          # Estructura de todas las pantallas
├── EstilosP1.css        # Estilos generales
├── ClasesP1.js          # Clases: Cliente, Administrador, Destino, Reserva
├── PrecargadosP1.js      # Clase Sistema + datos precargados + lógica de validación
├── CodigoP1.js           # Lógica de negocio: login, reservas, destinos, informes
├── PantallasP1.js        # Manejo de eventos y navegación entre pantallas
└── Imgs/                 # Imágenes de destinos y fondos
```

---

## 🚀 Cómo correrlo localmente

No requiere instalación ni dependencias. Simplemente:

1. Cloná el repositorio: `git clone https://github.com/rodrigoavogadro-uy/agencia-viajes.git`
2. Abrí `index.html` en tu navegador (o usá la extensión Live Server de VS Code)

---

## 👤 Autor

**Rodrigo Avogadro**
Estudiante de Analista en Tecnologías de la Información — Universidad ORT Uruguay

[LinkedIn](https://www.linkedin.com/in/rodrigo-avogadro-2b933721b/) · [Portfolio](#)