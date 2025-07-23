# 📱 Análisis Express de APK

Análisis rápido y pasivo de seguridad para archivos APK, ideal para pipelines CI/CD y revisiones educativas.
<img width="400" height="400" alt="image" src="https://github.com/user-attachments/assets/cddb1336-db05-44fc-ad4c-43996b72812a" />



---

## 🚀 ¿Qué hace?

- 📦 **Decompila** el APK usando ApkTool  
- 🔐 Busca **permisos peligrosos**  
- 🌐 Detecta **URLs expuestas**  
- ⚠️ Revisa **flags de seguridad** (`debuggable`, `allowBackup`, `cleartext`)  
- 🧪 Encuentra **secretos o credenciales** en texto  
- 🧩 Verifica ofuscación (**ProGuard**)  
- 🚪 Lista actividades exportadas (`exported="true"`)  
- 🏷️ Detecta signos de entorno de CI/CD (`dev`, `test`, `internal`)  
- 🔎 Muestra detalles del **certificado del APK**  
- 🔍 Analiza contenido de archivos sospechosos (deep scan)

---

## 🧰 Requisitos

- Archivo `.apk` válido
- Repositorio GitHub con GitHub Actions habilitado

---

## ⚙️ ¿Cómo se usa?

1. Sube tu APK al repositorio
2. Ejecuta el workflow manualmente desde **Actions**
3. Obtén el archivo `resumen_apk.txt` con los hallazgos

---

## 📄 Resultado

El análisis genera:

- 📄 Log resumido en `resumen_apk.txt`
- 📤 Artefacto descargable
- 📺 Resultado visible en pantalla

---

## 📚 Uso educativo

Este análisis **no ejecuta** el APK. Es ideal para:

- Entrenamiento en seguridad móvil
- Validaciones básicas de riesgo
- Revisión de apps antes de publicar
