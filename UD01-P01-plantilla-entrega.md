# Entrega Práctica UD01 · Auditoría y fortificación Clínica Dental Sonrisas

- **Nombre y apellidos del alumno/a:**
- **Grupo:** 2º SMR
- **Fecha de realización:**

---

### Actividad 1 · Mecanismos y objetivos de la seguridad informática

| ID | Mecanismo | Objetivo principal (C, I, D, NR) | Física / Lógica | Activa / Pasiva | Justificación |
|:---|:---|:---:|:---:|:---:|:---|
| 1.1 | SAI servidor |Disponibilidad |Física |Pasiva | |
| 1.2 | Cifrado BitLocker |Disponibilidad |Lógica |Pasiva | |
| 1.3 | Cortafuegos perimetral |Confidencialidad |Lógica |pasiva | |
| 1.4 | Copias de seguridad NAS |Disponibilidad |lógica |pasivo | |
| 1.5 | Antivirus corporativo |Integridad |lógica |pasiva | |

---

### Actividad 2 · Cadena del incidente de seguridad

1. **Activos afectados:**
   - Activo 1: Datos de pacientes
   - Activo 2: Registros de citas de la semana siguiente
2. **Amenaza:** El atacante remoto
3. **Vulnerabilidad y clasificación:** La no actualización del servidor servicio remoto
Conocido sobre software instalado, por que ya había una actualización para poder aplicar y q no hubiera esa vulnerabilidad
4. **Riesgo previo:** El riesgo consistía en que un atacante remoto, consiguiera permisos de administrador y pudiera copiar datos de clientes 
5. **Ataque:** La no actualización del servicio de acceso remoto desde hacía un año
6. **Impacto:**
   - Impacto cuantitativo:\perdida de 3.200€
   - Impacto cualitativo:\
   suspensión de la atención médica desde el lunes por la mañana\
   Quejas de pacientes

---

### Actividad 3 · Plan de contingencia

1. **Clasificación de medidas:**
   - Medida A:Plan de respaldo 
   - Medida B:Plan de respaldo
   - Medida C:Plan de recuperación
   - Medida D:Plan de emergencia
   - Medida E:Plan de respaldo 
   - Medida F:Plan de respaldo 
2. **Diferencia entre plan de respaldo y plan de recuperación:**
El plan de respaldo es para antes de un ataque, (prevenir un ataque), por ejemplo hacer una copia de la base de datos de una empresa\
Y el plan de recuperación es para después del ataque, por ejemplo reinstalar un sistema operativo

---

### Actividad 4 · Software malicioso y test de intrusión

#### 4.1. Diagnóstico de malware
- **Caso 1:**
  - Tipo de malware:Troyano
  - Justificación (archivo anfitrión e intervención usuario): Al abrir el PDF con extensión .exe, lo q ha hecho es crear una puerta trasera
  Si, requiere de un archivo anfitrión 
  No, no requiere una interacción activa del usuario para propagarse
- **Caso 2:**
  - Tipo de malware:Gusano
  - Justificación (archivo anfitrión e intervención usuario):Se propago por la red al no haber parcheado el fallo en el protocolo de compartición de archivos
  No,no requiere de un archivo anfitrión 
  No, no requiere una interacción activa del usuario para propagarse
- **Medida preventiva para Caso 2:**
Revisar diariamente si hay fallos en la red local, y si hay, revisar también si tiene posible parcheo

#### 4.2. Secuenciación de test de intrusión
- Secuencia ordenada cronológicamente (letras):
- Fases correspondientes:
  - Acción Z: Fase footprinting
  - Acción X: Fase Fingerprinting
  - Acción W: Fase Búsqueda de vulnerabilidades
  - Acción Y: Fase Parcheo/informe

---

### Actividad 5 · Contraseñas e identificación digital

#### 5.1. Contraseñas
1. **Comparativa de seguridad frente a fuerza bruta:**
La contraseña 2 será más difícil y costará más tiempo debido al uso de letras mayúsculas, minúsculas, números y símbolos especiales, aparte de que no es ninguna palabra
A diferencia de la contraseá 1 que solo utiliza letras minúsculas y números, encima las letras son una palabra y los números es un año 
2. **Política de contraseñas (3 reglas):**
   - Regla 1:Utilizar mayúsculas, minúsculas, números y símbolos especiales
   - Regla 2:Una longitud mínima de 10 a 12 caractéres
   - Regla 3:No utilizar palabras o números específicos

#### 5.2. Identificación digital
3. **Mecanismos aplicados:**
   - Trámite A: Documento electrónico que vincula identidad verificada y claves criptográficas; lo emite una autoridad de certificación.
   - Trámite B: Vincula a una persona con el contenido de un documento; aporta autoría, integridad y no repudio.
4. **Objetivo de seguridad garantizado y diferencia con usuario/contraseña:**
Garantiza la confidencialidad y la diferencia que tiene con el usuario/contraseña es que no todo el mundo puede conseguir tu firma digital, ya que una firma digital es un sello de identidad propio 