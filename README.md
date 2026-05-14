## LÍNEAS DE COMANDOS UTILIZADAS

| Comando                                          | Función                      | Aplicación en el proyecto                         |
| ------------------------------------------------ | ---------------------------- | ------------------------------------------------- |
| `mkdir proyecto_final`                           | Crear carpeta principal      | Generar el directorio del proyecto bioinformático |
| `cd proyecto_final`                              | Entrar a una carpeta         | Acceder al directorio de trabajo                  |
| `mkdir data`                                     | Crear carpeta                | Almacenar datos del proyecto                      |
| `mkdir data/raw`                                 | Crear subcarpeta             | Guardar secuencias FASTA originales               |
| `mkdir resultados`                               | Crear carpeta                | Organizar resultados generados                    |
| `mkdir docs`                                     | Crear carpeta                | Guardar documentación y reportes                  |
| `ls`                                             | Listar archivos y carpetas   | Verificar estructura del proyecto                 |
| `mv MT781409.1.fasta data/raw/`                  | Mover archivos               | Organizar el archivo FASTA descargado             |
| `cd data/raw`                                    | Cambiar directorio           | Acceder a la carpeta de secuencias                |
| `cat MT781409.1.fasta`                           | Mostrar contenido de archivo | Visualizar la secuencia biológica FASTA           |
| `find . -name "*.fasta"`                         | Buscar archivos              | Localizar archivos FASTA dentro del sistema       |
| `wc -l MT781409.1.fasta`                         | Contar líneas                | Obtener estadísticas básicas del archivo          |
| `nano README.md`                                 | Editar archivos de texto     | Crear y editar el README del proyecto             |
| `git init`                                       | Inicializar Git              | Crear repositorio local                           |
| `git status`                                     | Ver estado del repositorio   | Revisar cambios realizados                        |
| `git add .`                                      | Agregar archivos a Git       | Preparar archivos para commit                     |
| `git commit -m "README y documentación técnica"` | Crear commit                 | Guardar cambios realizados                        |
| `git remote add origin URL_REPOSITORIO`          | Vincular repositorio remoto  | Conectar GitHub con el proyecto local             |
| `git push origin main`                           | Subir archivos a GitHub      | Publicar el proyecto en línea                     |
