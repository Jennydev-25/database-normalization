# 🎓 Database Normalization (3FN) – Students, Classrooms & Courses

> Ejercicio de normalización de una base de datos relacional desde una tabla no normalizada hasta la Tercera Forma Normal (3FN).

---

## 📋 Descripción

El objetivo de este ejercicio es aplicar las tres primeras formas normales (1FN, 2FN y 3FN) a una tabla sin normalizar, eliminando redundancias, dependencias innecesarias y grupos de repetición para obtener un modelo relacional consistente.

Los requisitos principales son:

1. **Normalizar la tabla proporcionada** (hasta la 3FN).
2. **Realizar un diagrama Entidad-Relación (Chen)** para modelar conceptualmente las entidades y sus relaciones.
3. **Realizar un diagrama en notación Crow's Foot (patas de gallo)** para representar el esquema relacional resultante.

---

## 🗂️ Tabla original

Partimos de esta tabla que nos indica en el enunciado: _Los lenguajes de programación dependen del aula_

| id_student |  name_student  | classroom | classroom_description | course1 |     course2      |  course3   |
| :--------: | :------------: | :-------: | :-------------------: | :-----: | :--------------: | :--------: |
|     1      |  Ana Martínez  |   A101    |     Web Frontend      |  HTML   |       CSS        | JavaScript |
|     2      | Luis Fernández |   A102    |      Web Backend      |  Java   | Spring Framework |    SQL     |
|     3      |  Carla Gómez   |   A101    |     Web Frontend      |  HTML   |       CSS        | JavaScript |
|     4      |  Diego López   |   A103    |   Desarrollo Mobile   | Kotlin  |      Swift       |    Dart    |
|     5      | Marta Sánchez  |   A102    |      Web Backend      |  Java   | Spring Framework |    SQL     |
|     6      | Javier Torres  |   A101    |     Web Frontend      |  HTML   |       CSS        | JavaScript |
|     7      |   Laura Ruiz   |   A103    |   Desarrollo Mobile   | Kotlin  |      Swift       |    Dart    |
|     8      | Pablo Ramírez  |   A102    |      Web Backend      |  Java   | Spring Framework |    SQL     |
|     9      | Sofía Navarro  |   A101    |     Web Frontend      |  HTML   |       CSS        | JavaScript |
|     10     |  Tomás Ortega  |   A103    |   Desarrollo Mobile   | Kotlin  |      Swift       |    Dart    |

---
