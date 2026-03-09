# 📊 Análisis de Consultas SQL


## 📈 Resumen
✅ 0 correctas de 2 queries

## ❌ Query 1: Error
- **Descripción**: 'NoneType' object is not iterable


## ❌ Query 2: Incorrecto
```diff
--- 
+++ 
@@ -1,12 +1,12 @@
-nombre | precio
-Disco duro SATA3 1TB | 86.99
-Memoria RAM DDR4 8GB | 120.00
-Disco SSD 1 TB | 150.99
-GeForce GTX 1050Ti | 185.00
-GeForce GTX 1080 Xtreme | 755.00
-Monitor 24 LED Full HD | 202.00
-Monitor 27 LED Full HD | 245.99
-Portátil Yoga 520 | 559.00
-Portátil Ideapd 320 | 444.00
-Impresora HP Deskjet 3720 | 59.99
-Impresora HP Laserjet Pro M26nw | 180.00
+nombre
+Disco duro SATA3 1TB
+Memoria RAM DDR4 8GB
+Disco SSD 1 TB
+GeForce GTX 1050Ti
+GeForce GTX 1080 Xtreme
+Monitor 24 LED Full HD
+Monitor 27 LED Full HD
+Portátil Yoga 520
+Portátil Ideapd 320
+Impresora HP Deskjet 3720
+Impresora HP Laserjet Pro M26nw
```

⏱ Tiempo: 0.47 ms
🔍 No se usó ningún índice en esta consulta.

🚨 **Problemas detectados:**
🚨 `JOIN` sin índice. Revisar claves foráneas e índices.

---
