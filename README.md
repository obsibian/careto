# careto
Careto es una aplicación gráfica para Debian 13 que permite configurar y controlar fácilmente la visualización de la cámara web USB, con múltiples opciones de personalización.

<img width="832" height="1079" alt="careto1" src="https://github.com/user-attachments/assets/e5fbc36e-6e1b-4abe-9c00-2ec57eee9dec" />

---

## 🚀 Características

* Aplicacion diseñada para KDE Plasma 6 (qt).
* Interfaz intuitiva**: Diseño moderno con switches personalizados.
* Detección automática de cámaras**: Detecta todas las cámaras USB disponibles en el sistema.
* Configuración de visualización personalizada.
  
<img width="640" height="480" alt="CARETO" src="https://github.com/user-attachments/assets/a7f32444-0898-4383-b655-0ec45522575d" />

---

## 📦 Instalación

Instala el paquete `.deb` en Debian 13 con:

```bash
sudo dpkg -i careto.amd64.deb
sudo apt-get install -f
```

---

## 🧰 Requisitos

* Sistema operativo: **Debian 13**.
* Dependencias estándar incluidas en el paquete `.deb`.

---

## 📁 Estructura del proyecto

```
/usr/share/
├── applications/careto.desktop      # Entrada de menú
├── doc/careto/
│   ├── translations.json           # Traducciones
│   └── RobotoCondensed-Bold.ttf    # Fuente para superposición de texto
├── pixmaps/careto.svg              # Icono de la aplicación
└── man/man1/careto.1.gz            # Página de manual

/etc/
└── xdg/autostart/careto.desktop    # Para inicio automático (opcional)

~/.config/Careto/Configurador.conf  # Configuración del usuario
```

---

## 🛠 Uso

1. Abre la aplicación Careto.
2. Pulse el botón de Windows y arrástrela la imagen con el botón izquierdo del ratón.

---

## 📜 Licencia

Este proyecto está bajo la **GNU General Public License v3.0**.

---

## 🤝 Contribuciones

¡Las contribuciones son bienvenidas! Especialmente necesitamos ayuda con:

* Traducciones a otros idiomas.

---

## 📧 Contacto

Opcional: telegram @geinux
