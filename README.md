# Análisis SQL de libros, reseñas y calificaciones

Nota: El nombre de la empresa ha sido anonimizado por motivos de confidencialidad.

¿Qué hice?

Consultas SQL para analizar libros publicados después de 2000.

Conteo de reseñas y calificación promedio por libro.

Identificación de editoriales con mayor número de libros relevantes (>50 páginas).

Autores con mayor calificación promedio considerando libros con ≥50 ratings.

Número promedio de reseñas de texto por usuarios que calificaron más de 50 libros.

Tecnologías: SQL · Jupyter Notebook


# 📚 Análisis de Libros y Reseñas — SQL

Nota de confidencialidad:
Por motivos de seguridad y protección de datos, el nombre de la empresa y ciertos detalles contextuales han sido adaptados. El análisis refleja la metodología utilizada y los resultados obtenidos, preservando la confidencialidad de la información original.

## 📌 Contexto

Durante la pandemia, aumentó el consumo de libros y surgieron nuevas aplicaciones para lectores. Este proyecto analiza datos de un servicio de libros digitales para identificar patrones de publicación, reseñas y calificaciones que puedan guiar decisiones de producto.

## 🔎 Objetivos

Contar libros publicados después del 1 de enero de 2000.

Analizar la cantidad de reseñas y calificación promedio de cada libro.

Identificar editoriales que publican libros con más de 50 páginas.

Determinar el autor con mayor calificación promedio, considerando solo libros con al menos 50 calificaciones.

Evaluar el número promedio de reseñas de texto entre usuarios que calificaron más de 50 libros.

## 📂 Tablas / Datasets

books → información de libros: ID, autor, título, número de páginas, fecha de publicación, editorial.

authors → información de autores: ID y nombre.

publishers → información de editoriales: ID y nombre.

ratings → calificaciones de usuarios: ID, libro, usuario, rating.

reviews → reseñas de usuarios: ID, libro, usuario, texto.

## 🛠️ Tecnologías

SQL (PostgreSQL / MySQL / SQLite) · Jupyter Notebook · Python (opcional para visualización)
