📱 Análisis Express de APK

Análisis rápido y pasivo de seguridad para archivos APK
ideal para revisiones educativas.
<img width="400" height="400" alt="image" src="https://github.com/user-attachments/assets/cddb1336-db05-44fc-ad4c-43996b72812a" />



---

# 📱 Análisis APK Exprés

Este workflow realiza una **análisis estática exprés** de un archivo APK utilizando herramientas como `apktool` y `grep`. Ideal para revisiones rápidas, automatizadas y educativas.

---

## 🚀 ¿Qué hace este workflow?

1. Instala herramientas necesarias.
2. Decompila el APK usando `apktool`.
3. Busca:
   - Permisos peligrosos.
   - URLs embebidas.
   - Flags inseguras (`debuggable`, `allowBackup`).
   - Posibles secretos o tokens expuestos.
4. Muestra un resumen en pantalla.
5. Sube el archivo `resumen_apk.txt` como artefacto.

---

## 🧩 Entradas requeridas

| Nombre      | Descripción                                    | Por defecto |
|-------------|------------------------------------------------|-------------|
| `apk_name`  | Nombre del archivo APK (ej: `app.apk`)         | `app.apk`   |

---

## 📋 Salida del análisis (resumen_apk.txt)

El archivo final contiene secciones como:

- 🔐 **Permisos peligrosos**  
- 🌐 **URLs encontradas**  
- ⚠️ **Flags de seguridad**  
- 🧪 **Posibles secretos expuestos**  



- Entrenamiento en seguridad móvil
- Validaciones básicas de riesgo
- Revisión de apps antes de publicar
