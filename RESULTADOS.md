# 📊 Análisis de Consultas SQL


## 📈 Resumen
✅ 14 correctas de 20 queries

## ✅ Query 1: Correcto

⏱ Tiempo: 0.44 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 2: Correcto

⏱ Tiempo: 0.35 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 3: Correcto

⏱ Tiempo: 0.29 ms
🔍 No se usó ningún índice en esta consulta.

🚨 **Problemas detectados:**
⚠️ Evitar `SELECT *`. Usar solo las columnas necesarias.

---

## ✅ Query 4: Correcto

⏱ Tiempo: 0.29 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 5: Correcto

⏱ Tiempo: 0.32 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 6: Correcto

⏱ Tiempo: 0.33 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 7: Correcto

⏱ Tiempo: 0.28 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 8: Correcto

⏱ Tiempo: 0.32 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 9: Correcto

⏱ Tiempo: 0.29 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 10: Correcto

⏱ Tiempo: 0.29 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 11: Correcto

⏱ Tiempo: 0.29 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 12: Correcto

⏱ Tiempo: 0.30 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante

---

## ❌ Query 13: Incorrecto
```diff
--- 
+++ 
@@ -1,10 +1,10 @@
-nombre
-Asus
-Crucial
-Gigabyte
-Hewlett-Packard
-Huawei
-Lenovo
-Samsung
-Seagate
-Xiaomi
+codigo | nombre
+1.00 | Asus
+6.00 | Crucial
+7.00 | Gigabyte
+3.00 | Hewlett-Packard
+8.00 | Huawei
+2.00 | Lenovo
+4.00 | Samsung
+5.00 | Seagate
+9.00 | Xiaomi
```

⏱ Tiempo: 0.29 ms
🔍 No se usó ningún índice en esta consulta.

🚨 **Problemas detectados:**
⚠️ Evitar `SELECT *`. Usar solo las columnas necesarias.

---

## ❌ Query 14: Incorrecto
```diff
--- 
+++ 
@@ -1,10 +1,10 @@
-nombre
-Xiaomi
-Seagate
-Samsung
-Lenovo
-Huawei
-Hewlett-Packard
-Gigabyte
-Crucial
-Asus
+codigo | nombre
+9.00 | Xiaomi
+5.00 | Seagate
+4.00 | Samsung
+2.00 | Lenovo
+8.00 | Huawei
+3.00 | Hewlett-Packard
+7.00 | Gigabyte
+6.00 | Crucial
+1.00 | Asus
```

⏱ Tiempo: 0.29 ms
🔍 No se usó ningún índice en esta consulta.

🚨 **Problemas detectados:**
⚠️ Evitar `SELECT *`. Usar solo las columnas necesarias.

---

## ✅ Query 15: Correcto

⏱ Tiempo: 0.32 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 16: Correcto

⏱ Tiempo: 0.28 ms
🔍 No se usó ningún índice en esta consulta.

🚨 **Problemas detectados:**
⚠️ Evitar `SELECT *`. Usar solo las columnas necesarias.

---

## ❌ Query 17: Incorrecto
```diff
--- 
+++ 
@@ -1,3 +1,4 @@
 codigo | nombre
 4.00 | Samsung
 5.00 | Seagate
+6.00 | Crucial
```

⏱ Tiempo: 0.28 ms
🔍 No se usó ningún índice en esta consulta.

🚨 **Problemas detectados:**
⚠️ Evitar `SELECT *`. Usar solo las columnas necesarias.

---

## ❌ Query 18: Incorrecto
```diff
--- 
+++ 
@@ -1,2 +1,2 @@
-nombre | precio
-Impresora HP Deskjet 3720 | 59.99
+codigo | nombre | precio | codigo_fabricante
+10.00 | Impresora HP Deskjet 3720 | 59.99 | 3.00
```

⏱ Tiempo: 0.31 ms
🔍 No se usó ningún índice en esta consulta.

🚨 **Problemas detectados:**
⚠️ Evitar `SELECT *`. Usar solo las columnas necesarias.

---

## ❌ Query 19: Incorrecto
```diff
--- 
+++ 
@@ -1,2 +1,2 @@
-nombre | precio
-GeForce GTX 1080 Xtreme | 755.00
+codigo | nombre | precio | codigo_fabricante
+5.00 | GeForce GTX 1080 Xtreme | 755.00 | 6.00
```

⏱ Tiempo: 0.29 ms
🔍 No se usó ningún índice en esta consulta.

🚨 **Problemas detectados:**
⚠️ Evitar `SELECT *`. Usar solo las columnas necesarias.

---

## ❌ Query 20: Incorrecto
```diff
--- 
+++ 
@@ -1,3 +1,3 @@
-nombre
-Portátil Yoga 520
-Portátil Ideapd 320
+codigo | nombre | precio | codigo_fabricante
+8.00 | Portátil Yoga 520 | 559.00 | 2.00
+9.00 | Portátil Ideapd 320 | 444.00 | 2.00
```

⏱ Tiempo: 0.36 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante

🚨 **Problemas detectados:**
⚠️ Evitar `SELECT *`. Usar solo las columnas necesarias.

---
