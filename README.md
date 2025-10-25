# Proyecto de Automatización de Login - SauceDemo

## 📌 Propósito del proyecto
Este proyecto tiene como objetivo automatizar el flujo de **login** en el sitio [https://www.saucedemo.com](https://www.saucedemo.com), utilizando **Selenium WebDriver** y **Pytest**.  
La automatización valida que un usuario con credenciales válidas pueda acceder correctamente a la página de inventario, comprobando tanto la redirección a `/inventory.html` como la presencia del texto “Products” o “Swag Labs”.

## 🧰 Tecnologías utilizadas
- **Python** - Lenguaje de programación
- **Pytest** – Framework de testing  
- **Selenium WebDriver** – Automatización de interacción con navegador  
- **Webdriver-Manager** – Gestión automática del driver de Chrome  
- **Git y GitHub** – Control de versiones

## ⚙️ Instalación de dependencias

Antes de ejecutar las pruebas, asegurate de tener Python instalado.  
Luego, instalá las dependencias ejecutando el siguiente comando en tu terminal:

```bash
pip install selenium
pip install pytest
pip install webdriver-manager
pip install pytest-html
    
