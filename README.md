# 🔤 Assignment: Acrónimos de Arquitectura y Software (Grupo 3)

| Metadata | Detalle |
| :--- | :--- |
| **Autor** | Yohan Sebastian Ospina Gonzalez |
| **Organización** | Blend360 (`ai-scm`) |
| **Repositorio** | `s2026q4a-acronyms-yohanospina` |
| **Proyecto** | `[P2426] semillero-2026-q4_a` |

---

## 📌 Acrónimos Seleccionados

### 1. RAG (Retrieval-Augmented Generation)
* **Significado:** Generación Aumentada por Recuperación.
* **Explicación sencilla:** Es una técnica para conectar un modelo de Inteligencia Artificial (como ChatGPT o Claude) con una base de conocimientos o documentos propios de una empresa. En lugar de que la IA responda solo con lo que aprendió en su entrenamiento, primero busca la información exacta en tus archivos y luego genera una respuesta precisa y fundamentada.

---

### 2. CAP Theorem (Consistency, Availability, Partition Tolerance)
* **Significado:** Teorema CAP (Consistencia, Disponibilidad y Tolerancia a Particiones).
* **Explicación sencilla:** Es una regla fundamental de las bases de datos distribuidas en la nube. Establece que cuando los datos se guardan en múltiples servidores interconectados, solo se pueden garantizar 2 de estas 3 propiedades al mismo tiempo:
  * **Consistencia:** Todos ven los mismos datos exactos al mismo instante.
  * **Disponibilidad:** El sistema siempre responde, aunque algún servidor falle.
  * **Tolerancia a particiones:** El sistema sigue funcionando aunque se corte la comunicación entre servidores.

---

### 3. EDA (Event-Driven Architecture)
* **Significado:** Arquitectura Dirigida por Eventos.
* **Explicación sencilla:** Es un modelo donde los componentes del software no se llaman entre sí de forma fija, sino que reaccionan automáticamente cuando ocurre un "evento" o suceso. Por ejemplo: en AWS, al subir un archivo CSV a un bucket de **S3** (evento), se dispara automáticamente una función **AWS Lambda** para procesarlo.

---

### 4. DDD (Domain-Driven Design)
* **Significado:** Diseño Guiado por el Dominio.
* **Explicación sencilla:** Es una forma de construir software enfocada en entender profundamente el negocio real del cliente. Se busca que la estructura del código y los nombres en las bases de datos hablen el mismo lenguaje que usan los expertos del negocio (por ejemplo, hablar de "Póliza", "Asegurado" o "Reclamación" directamente en el código).

---

### 5. BFF (Backend For Frontend)
* **Significado:** Backend para Frontend.
* **Explicación sencilla:** Es un patrón de diseño donde, en lugar de tener un único servidor pesado para todas las aplicaciones, se crea un pequeño backend a la medida de cada canal (uno optimizado para la app móvil, otro para la página web, etc.). De esta manera, cada pantalla recibe exactamente los datos que necesita sin sobrecargar la red.