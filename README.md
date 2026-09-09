## 🏗️ Evidencia: Arquitectura, Escala y Prácticas Reales 
 
No buscamos convencerte con promesas; queremos mostrarte cómo trabajamos realmente. Acá compartimos nuestras decisiones de diseño, métricas de resiliencia y cómo enfrentamos los desafíos y datos reales de producción en el día a día.

<p align="center">
  <img src="02The Beauty of Boring Tech (1).gif" width="600">
</p>

### 🛠️ Filosofía "Boring Technology": Por qué elegimos nuestro stack

Nuestra elección tecnológica es intencional. Utilizamos **Ruby on Rails, PostgreSQL, TypeScript, PHP y Kubernetes**.

En lugar de perseguir la tecnología de moda, priorizamos la **velocidad de entrega y la estabilidad** para responder a la complejidad regulatoria y tributaria de operar simultáneamente en cinco países.

<!-- VIDEO DE JUSTIFICACIÓN DE STACK -->
[▶️ Ver Video: Por qué elegimos Boring Tech](https://drive.google.com/file/d/19sX57zgUO_pkUgP415fEGs_pyfN0Wt4v/view?usp=sharing)

### 🧩 Arquitectura y Resiliencia en Escala (El Monolito)

Trabajamos con una arquitectura híbrida, combinando nuestro **monolito en Rails** con microservicios enfocados en dominios específicos.

### ¿Cómo respondemos a los momentos de mayor demanda?

Contamos con una arquitectura robusta en **Ruby on Rails**, preparada para responder a grandes volúmenes de transacciones. En frontend, trabajamos con **monorepos y librerías de componentes centralizadas** para mantener consistencia y un tipado estricto.

Todo esto se apoya en infraestructura **AWS Multi-Región**, diseñada para mantener una alta disponibilidad incluso en los momentos de mayor demanda.

<!-- VIDEO DECISIONES DE DISEÑO Y ARQUITECTURA -->
[▶️ Ver Video: La arquitectura y el Monolito en Buk](https://drive.google.com/file/d/1sNOn8tAPKEXARGmDW0quZK3zYvmkLRgB/view?usp=drive_link)

### 🚢 Despliegues Estructurados y Cultura de Error

Escalar rápido también significa estar preparados cuando algo falla. Por eso, contamos con prácticas que nos permiten desplegar de forma segura y aprender de lo que ocurre en producción:

* **Integración Continua (CI/CD):** con una alta cobertura de pruebas automatizadas.
* **Feature Flags:** nos permiten separar los despliegues técnicos de los lanzamientos de nuevas funcionalidades.
* **Blameless Post-Mortems:** cuando ocurre un incidente, analizamos la causa raíz sin buscar culpables, poniendo el foco en aprender y mejorar como equipo.

### 👥 El Cliente en el Centro

Como ingenieros en Buk, buscamos entender **qué construimos, por qué lo hacemos y para quién**. Trabajamos con sistemas de nómina y recursos humanos, donde sabemos que cada decisión técnica puede tener un impacto real en miles de organizaciones y sus colaboradores.

Por eso, construimos pensando en esa responsabilidad todos los días.

*Siguiente paso:* 👉 **[Explora nuestro Pilar 3: Conversión (Comunidad, Open Source y nuestro proceso)](https://github.com/Javipizarrot/conversi-n_y_comunidad_buker.git)**
