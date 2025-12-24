# careto
Careto es una aplicación gráfica para Debian 13 que permite configurar y controlar fácilmente la visualización de la cámara web USB, con múltiples opciones de personalización.

<img width="932" height="859" alt="careto6" src="https://github.com/user-attachments/assets/1c9806fd-812b-4863-8e9e-340b0e5188be" />

---

## 🚀 Características

* Aplicacion diseñada para KDE Plasma 6 (qt).
* Interfaz intuitiva**: Diseño moderno con switches personalizados.
* Detección automática de cámaras**: Detecta todas las cámaras USB disponibles en el sistema.
* Configuración de visualización personalizada.

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
2. Pulse la tecla de Windows y arrástrela la imagen con el botón izquierdo del ratón.

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
