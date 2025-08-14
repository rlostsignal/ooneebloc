# 🚀 OONEEBLOC

Hub central para AI Agents, educación crypto y recursos DeFi.

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Active-success)](https://riostsignal.github.io/ooneebloc)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Version](https://img.shields.io/badge/Version-1.0.0-purple)](https://github.com/riostsignal/ooneebloc/releases)

## 📌 Descripción

OONEEBLOC es una plataforma educativa sobre blockchain, criptomonedas y tecnologías descentralizadas. Nuestro objetivo es democratizar el acceso al conocimiento crypto.

### 🌟 Características

- 📊 **Presentaciones Educativas**: Material actualizado sobre crypto y blockchain
- 🤖 **AI Agents Directory**: 37+ agentes del protocolo Virtuals ACP
- 🔗 **Recursos Esenciales**: Herramientas y plataformas del ecosistema
- 📱 **Diseño Responsive**: Optimizado para todos los dispositivos
- 🌙 **Tema Oscuro**: Interfaz moderna y elegante

## 🚀 Acceso Rápido

🌐 **Sitio Web**: [https://riostsignal.github.io/ooneebloc](https://riostsignal.github.io/ooneebloc)

## 📁 Estructura del Proyecto

```
ooneebloc/
├── index.html          # Sitio principal
├── slides.json         # Base de datos de presentaciones
├── README.md           # Este archivo
└── CNAME              # (Opcional) Para dominio personalizado
```

## 🛠️ Tecnologías

- **Frontend**: HTML5, CSS3, JavaScript ES6+
- **Hosting**: GitHub Pages
- **Embeds**: Canva Presentations
- **Sin dependencias**: 0 frameworks, 100% vanilla

## 📝 Cómo Actualizar Slides

### Método 1: Editar slides.json

1. Abre `slides.json`
2. Agrega un nuevo objeto al array `slides`:

```json
{
  "id": "slide-005",
  "title": "Tu Nueva Presentación",
  "description": "Descripción detallada",
  "category": "crypto",
  "embedUrl": "https://www.canva.com/design/XXXXX/view?embed",
  "order": 5,
  "status": "published"
}
```

3. Commit y push:
```bash
git add slides.json
git commit -m "Agregar nueva presentación"
git push
```

### Método 2: Editar directamente en GitHub

1. Ve a [slides.json](slides.json)
2. Click en el ícono del lápiz (Edit)
3. Agrega tu slide
4. Commit changes

## 🎨 Obtener URL de Canva

1. Abre tu diseño en Canva
2. Click en **Compartir** (botón morado)
3. Selecciona **Más** → **Sitio web**
4. Elige **"Responsive"**
5. Copia el link (debe terminar en `?embed`)

### Formato correcto:
✅ `https://www.canva.com/design/DAGv7J7fXSg/view?embed`  
❌ `https://www.canva.com/design/DAGv7J7fXSg/view`

## 🔧 Desarrollo Local

```bash
# Clonar repositorio
git clone https://github.com/riostsignal/ooneebloc.git

# Entrar al directorio
cd ooneebloc

# Abrir con Live Server (VS Code)
# O con Python:
python -m http.server 8000

# Visitar http://localhost:8000
```

## 📊 Categorías de Slides

- `crypto` - Criptomonedas y mercados
- `blockchain` - Tecnología y fundamentos
- `defi` - Finanzas descentralizadas
- `trading` - Análisis y estrategias
- `seguridad` - Protección de activos

## 🤝 Contribuir

1. Fork el proyecto
2. Crea tu rama (`git checkout -b feature/NuevaCaracteristica`)
3. Commit tus cambios (`git commit -m 'Agregar característica'`)
4. Push a la rama (`git push origin feature/NuevaCaracteristica`)
5. Abre un Pull Request

## 📄 Licencia

Este proyecto está bajo la Licencia MIT - ver el archivo [LICENSE](LICENSE) para detalles.

## 🙏 Agradecimientos

- [Canva](https://www.canva.com) por las herramientas de presentación
- [GitHub Pages](https://pages.github.com) por el hosting gratuito
- Comunidad crypto por el apoyo continuo

## 📞 Contacto

**GitHub**: [@riostsignal](https://github.com/riostsignal)

---

<div align="center">
  Hecho con 💜 por OONEE
</div>
