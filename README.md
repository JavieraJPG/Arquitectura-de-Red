# 🌐 Fundamentos de Redes para Developers

Guía simple y práctica para entender cómo funciona la red desde cero, con analogías de la vida cotidiana y enfoque en desarrollo.

---

## 🧩 1. Conceptos base

| Concepto | Definición simple | Nivel técnico breve | Ejemplo real |
|---|---|---|---|
| Modelo OSI | Forma de entender cómo viaja la información en pasos. | Modelo de 7 capas que separa funciones de red. | Una request web pasa por varias capas. |
| Subnet | División de una red grande en partes pequeñas. | Segmentación usando IP y máscara (CIDR). | Red de empresa separada en áreas. |
| DNS | Traduce nombres a direcciones IP. | Sistema distribuido de resolución de nombres. | google.com → IP |

---

## 🧱 2. Modelo OSI

### 🧠 ¿Qué es?
Modelo que explica cómo viajan los datos entre sistemas.

### 🎯 ¿Para qué sirve?
- Entender redes
- Detectar errores

---

### 📦 Analogía: envío de paquete

| Capa | Nombre | Analogía |
|---|---|---|
| 7 | Aplicación | Escribes el pedido |
| 6 | Presentación | Se traduce/formatea |
| 5 | Sesión | Mantiene conexión |
| 4 | Transporte | Decide cómo enviarlo |
| 3 | Red | Define la ruta |
| 2 | Enlace | Se mueve en el barrio |
| 1 | Física | Medio de transporte |

---

## 🌐 3. DNS

### 🧠 ¿Qué es?
Sistema que traduce nombres (dominios) a IP.

### ❓ ¿Por qué no usamos IP?
- Difíciles de recordar
- Cambian

---

### 📱 Analogía
Agenda de contactos → buscas nombre, obtienes número.

---

### 🔎 Flujo

1. Escribes `google.com`
2. DNS busca la IP
3. Devuelve la IP
4. Tu navegador se conecta
5. Recibes la web

---

## 🧩 4. Subnets

### 🧠 ¿Qué es?
Dividir una red en partes.

### 🏠 Analogía
Ciudad → barrios (subnets)

---

### 🎯 ¿Para qué sirve?
- Orden
- Seguridad
- Control de tráfico

---

### 💻 Ejemplo

- Subnet pública → frontend
- Subnet privada → base de datos

---

## 💻 5. Conexión con desarrollo

### ❌ Problemas comunes

| Problema | Causa | Analogía |
|---|---|---|
| No encuentra servidor | IP incorrecta | Dirección mal escrita |
| DNS falla | Dominio no resuelve | Contacto inexistente |
| No conecta | Firewall / red | Puerta cerrada |

---

## 🚨 6. Debugging

### Errores

- DNS not found → no existe dominio
- Host unreachable → no hay ruta
- Network error → fallo general

---

### 🔍 Checklist

1. DNS
2. IP
3. Red
4. Puertos
5. Firewall

---

## 🌍 7. Caso práctico

> App deployada pero no accesible

### Posibles causas:

- DNS mal configurado
- Red incorrecta
- Puerto cerrado
- Servidor caído

---

## 🧪 8. Analogías clave

| Concepto | Analogía |
|---|---|
| OSI | Envío de paquete |
| DNS | Agenda |
| Subnet | Barrios |

---

## 📚 Glosario

| Término | Significado |
|---|---|
| IP | Dirección única |
| DNS | Traduce nombres |
| Dominio | Nombre web |
| Servidor | Entrega servicios |
| Cliente | Hace requests |
| Puerto | Entrada de servicio |
| HTTP/HTTPS | Protocolos web |
| TCP | Seguro |
| UDP | Rápido |
| Firewall | Control de acceso |
| Subnet | División de red |
| Router | Conecta redes |
| Switch | Conecta dispositivos |
| MAC | Dirección física |
| Latencia | Tiempo de respuesta |
| Timeout | Tiempo límite |
| VPC | Red en la nube |
| IP pública | Visible |
| IP privada | Interna |
| Load Balancer | Distribuye tráfico |

---

## 🧠 Bonus

### VPC
Red privada en cloud.

### IP pública vs privada
- Pública → internet
- Privada → red interna

### Load Balancer
Distribuye tráfico entre servidores.

---

## 🚀 Objetivo

Entender cómo funciona la red para:
- Debuggear problemas reales
- Diseñar arquitectura básica
- Pensar como developer backend

---
