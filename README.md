Proyecto Final - Programa de Ventas en Java

## 🧠 Descripción General
Este proyecto corresponde al desarrollo final del módulo de programación en Java.  
El objetivo es crear un programa que reciba información de **vendedores**, **productos** y **ventas**, y que posteriormente genere **reportes de ventas por vendedor y por producto**, siguiendo las especificaciones del documento **“Generación y clasificación de datos.pdf”**.

El repositorio contiene la versión funcional y documentada del programa, desarrollada por los integrantes del grupo del escenario 7.

---

## 🧑‍💻 Integrantes del equipo
- Ana Milena Rodríguez Ibarra  
- Daniel David Moreno Morales  
- Sebastián Camilo Cuervo Baquero
- Yessica Paola Ramos Cortes
- Monica Tatiana Murillo Patiño

---

## 🗂️ Estructura del proyecto
ProyectoArchivosJava/
│
├── src/
│ ├── GenerateInfoFiles.java # Clase que genera archivos de datos pseudoaleatorios
│ ├── ReportGenerator.java # Clase que procesa los archivos y genera reportes
│
├── data/
│ ├── vendedores.txt
│ ├── productos.txt
│ ├── ventas.txt
│
├── output/
│ ├── reporte_vendedores.txt
│ ├── reporte_productos.txt
│
├── README.md
└── Entrega_Final_Proyecto_Java.docx

yaml
Copiar código

---

## ⚙️ Instrucciones de ejecución

1. **Clonar el repositorio**
   ```bash
   git clone https://github.com/DanielM003/ProyectoArchivosJava.git
   cd ProyectoArchivosJava
Compilar los archivos Java

bash
Copiar código
javac src/*.java -d bin
Ejecutar el generador de datos

bash
Copiar código
java -cp bin GenerateInfoFiles
➜ Este paso crea los archivos de entrada vendedores.txt, productos.txt y ventas.txt.

Ejecutar el generador de reportes

bash
Copiar código
java -cp bin ReportGenerator
➜ Este paso genera los reportes:

reporte_vendedores.txt

reporte_productos.txt

Verificar resultados
Los reportes se guardan dentro de la carpeta output/ y pueden abrirse con cualquier editor de texto.

📊 Ejemplo de salida esperada
mathematica
Copiar código
=== Reporte de Ventas por Vendedor ===
Vendedor 101 - Total Vendido: 1,240,000
Vendedor 102 - Total Vendido: 980,500

=== Reporte de Ventas por Producto ===
Producto A - 35 unidades vendidas
Producto B - 22 unidades vendidas
Producto C - 14 unidades vendidas
🧩 Tecnologías utilizadas
Lenguaje: Java SE 17

Paradigma: Programación orientada a objetos (POO)

Manejo de archivos: Lectura y escritura de archivos planos (FileReader, BufferedReader, PrintWriter)

Control de versiones: Git y GitHub

📚 Reflexión final
Durante el desarrollo de este proyecto, el equipo fortaleció sus habilidades en:

Manipulación de archivos en Java.

Creación de estructuras de datos para organizar información.

Trabajo colaborativo mediante GitHub.

Aplicación práctica de buenas prácticas de programación.

El proyecto tiene aplicación real en sistemas de control de inventario, reportes administrativos y gestión de ventas.

🏁 Créditos
Proyecto desarrollado para el módulo de Programación en Java - Escenario 7 y 8.
Universidad / Plataforma educativa: (añadir nombre si aplica).
Fecha de entrega: Octubre 2025.

yaml
Copiar código

---

## 🧰 **Comandos Git para subir todo**

Abre tu terminal o Git Bash en la carpeta del proyecto y ejecuta paso a paso:

```bash
# 1️⃣ Verifica que estás en la carpeta del proyecto
cd ProyectoArchivosJava

# 2️⃣ Agrega el documento Word y el README
git add README.md
git add "Entrega_Final_Proyecto_Java.docx"

# 3️⃣ Confirma los cambios con un mensaje descriptivo
git commit -m "Entrega final del proyecto - Documento Word y README incluidos"

# 4️⃣ Sube los cambios al repositorio remoto
git push origin main
