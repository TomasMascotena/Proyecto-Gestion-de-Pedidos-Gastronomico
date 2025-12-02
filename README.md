# 🍽️ Sistema de Gestión de Pedidos para Restaurante

Este proyecto implementa un sistema completo para la gestión de pedidos en un restaurante, desarrollado en **Java** utilizando **Spring Boot**, **Maven**, **Lombok**, y principios sólidos de **Programación Orientada a Objetos (POO)**.

Incluye una interfaz web dinámica construida con **HTML**, **CSS**, **Bootstrap**, **Thymeleaf** y manejo de eventos con **JavaScript (axios + fetch)**.

---

## 🛠 Tecnologías utilizadas

### **Backend**
- Java 21  
- Spring Boot  
- Maven  
- Lombok  
- MySQL  
- Spring Data JPA  
- DTOs y Mappers  
- Validaciones (Javax Validation)

### **Frontend**
- HTML5  
- CSS3  
- Bootstrap  
- JavaScript  
- Axios / Fetch  
- Thymeleaf  

---

## ✅ Funcionalidades principales

- ✔️ Creación, edición y consulta de **pedidos**  
- ✔️ Registro detallado de productos pedidos (**detalles del pedido**)  
- ✔️ Control del tiempo:
  - Fecha/hora del pedido  
  - Estado del pedido (EN_PROCESO, ENTREGADO, etc.)  
- ✔️ Gestión precisa de montos (totales y subtotales)  
- ✔️ Administración de mesas  
- ✔️ Carga y actualización de productos disponibles  
- ✔️ Comunicación entre frontend y backend mediante JSON (REST)  
- ✔️ Interfaz clara e intuitiva para el personal del restaurante  
- ✔️ Ordenamiento y filtrado de resultados  
- ✔️ Validaciones automáticas en formularios y entidades  

---

## 💡 Buenas prácticas aplicadas

- 🧩 Programación Orientada a Objetos en todo el dominio del negocio  
- 🔄 Uso de **DTOs**, evitando exponer entidades directamente  
- 🧱 Separación clara entre capas:
  - Controller  
  - Service  
  - Repository  
  - DTO / Mapper  
- 📦 Uso de **interfaces (IService)** para desacoplar lógica  
- 📝 Código limpio, mantenible y modular  
- 🎯 Uso de anotaciones de Spring (`@Service`, `@RestController`, `@Repository`, etc.)  
- ⚙️ Manejo correcto de relaciones entre entidades (OneToMany, ManyToOne)  
- ⏱ Validación de reglas de negocio (cambios de estado, pagos, etc.)  
- 🔐 Manejo robusto de errores y respuestas HTTP  
- 🎨 Frontend adaptado con diseño basado en **Bootstrap**  
- 🔄 Actualización dinámica de vistas mediante **axios/fetch**  

---

## 🧱 Arquitectura del Proyecto

El proyecto sigue un enfoque **MVC + Servicios**, donde:

- **Model** → Entidades JPA + DTOs  
- **View** → HTML + Thymeleaf + JavaScript  
- **Controller** → Endpoints REST  
- **Service** → Lógica y reglas de negocio  
- **Repository** → Persistencia mediante MySQL y JPA  

---

## 👤 Autor

**Tomas Mascotena**  
📧 *tomasnmascotena@gmail.com*

---


