

# Memory Analyzer

Memory Analyzer es una herramienta basada en Python para analizar y manipular la memoria de procesos en ejecución en un sistema Windows. Te permite listar procesos, buscar procesos por nombre o PID, escanear la memoria en busca de valores específicos, escribir valores en la memoria y verificar cambios en los valores de memoria.

## Características

- Listar todos los procesos en ejecución
- Buscar procesos por nombre o PID
- Escanear la memoria en busca de valores específicos
- Escribir valores en direcciones de memoria específicas
- Verificar cambios en los valores de memoria

## Estructura del Proyecto

```
.gitignore
main.py
src/
    config/
        config.py
    memory/
        memory_reader.py
        memory_scanner.py
        memory_writer.py
    process/
        process_list.py
        process_search.py
```

## Instalación

1. Clona el repositorio:
    ```sh
    git clone https://github.com/Andronovo-bit/Basic-Memory-Scanner-Changer.git
    cd Basic-Memory-Scanner-Changer
    ```

2. Instala las dependencias requeridas:
    ```sh
    pip install -r requirements.txt
    ```

## Uso

Ejecuta el script principal para iniciar el Memory Analyzer:
```sh
python main.py
```

### Opciones del Menú Principal

1. **Listar Procesos**: Lista todos los procesos en ejecución.
2. **Buscar Proceso por Nombre**: Busca procesos por nombre.
3. **Buscar Proceso por PID**: Busca un proceso por su PID.
4. **Escanear Memoria**: Escanea la memoria de un proceso en busca de un valor específico.
5. **Escribir en Memoria**: Escribe un valor en una dirección de memoria específica de un proceso.
6. **Verificar Cambios de Memoria**: Verifica cambios en los valores de memoria de un proceso.
7. **Salir**: Sale del Memory Analyzer.

### Ejemplo de Uso

1. **Listar Procesos**:
    - Selecciona la opción [`1`](command:_github.copilot.openSymbolFromReferences?%5B%22%22%2C%5B%7B%22uri%22%3A%7B%22scheme%22%3A%22file%22%2C%22authority%22%3A%22%22%2C%22path%22%3A%22%2Fe%3A%2FProjects%2FPython%2Fmemory_analyzer%2Fmain.py%22%2C%22query%22%3A%22%22%2C%22fragment%22%3A%22%22%7D%2C%22pos%22%3A%7B%22line%22%3A9%2C%22character%22%3A11%7D%7D%5D%2C%2266ab22f5-0029-4c68-ba8b-ec2b26cc2e5e%22%5D "Go to definition") para listar todos los procesos en ejecución.

2. **Buscar Proceso por Nombre**:
    - Selecciona la opción [`2`](command:_github.copilot.openSymbolFromReferences?%5B%22%22%2C%5B%7B%22uri%22%3A%7B%22scheme%22%3A%22file%22%2C%22authority%22%3A%22%22%2C%22path%22%3A%22%2Fe%3A%2FProjects%2FPython%2Fmemory_analyzer%2Fmain.py%22%2C%22query%22%3A%22%22%2C%22fragment%22%3A%22%22%7D%2C%22pos%22%3A%7B%22line%22%3A10%2C%22character%22%3A11%7D%7D%5D%2C%2266ab22f5-0029-4c68-ba8b-ec2b26cc2e5e%22%5D "Go to definition") e ingresa el nombre del proceso a buscar.

3. **Buscar Proceso por PID**:
    - Selecciona la opción [`3`](command:_github.copilot.openSymbolFromReferences?%5B%22%22%2C%5B%7B%22uri%22%3A%7B%22scheme%22%3A%22file%22%2C%22authority%22%3A%22%22%2C%22path%22%3A%22%2Fe%3A%2FProjects%2FPython%2Fmemory_analyzer%2Fmain.py%22%2C%22query%22%3A%22%22%2C%22fragment%22%3A%22%22%7D%2C%22pos%22%3A%7B%22line%22%3A11%2C%22character%22%3A11%7D%7D%5D%2C%2266ab22f5-0029-4c68-ba8b-ec2b26cc2e5e%22%5D "Go to definition") e ingresa el PID del proceso a buscar.

4. **Escanear Memoria**:
    - Selecciona la opción [`4`](command:_github.copilot.openSymbolFromReferences?%5B%22%22%2C%5B%7B%22uri%22%3A%7B%22scheme%22%3A%22file%22%2C%22authority%22%3A%22%22%2C%22path%22%3A%22%2Fe%3A%2FProjects%2FPython%2Fmemory_analyzer%2Fmain.py%22%2C%22query%22%3A%22%22%2C%22fragment%22%3A%22%22%7D%2C%22pos%22%3A%7B%22line%22%3A12%2C%22character%22%3A11%7D%7D%2C%7B%22uri%22%3A%7B%22scheme%22%3A%22file%22%2C%22authority%22%3A%22%22%2C%22path%22%3A%22%2Fe%3A%2FProjects%2FPython%2Fmemory_analyzer%2Fsrc%2Fmemory%2Fmemory_scanner.py%22%2C%22query%22%3A%22%22%2C%22fragment%22%3A%22%22%7D%2C%22pos%22%3A%7B%22line%22%3A76%2C%22character%22%3A64%7D%7D%5D%2C%2266ab22f5-0029-4c68-ba8b-ec2b26cc2e5e%22%5D "Go to definition"), ingresa el PID del proceso a escanear y el valor a buscar.

5. **Escribir en Memoria**:
    - Selecciona la opción [`5`](command:_github.copilot.openSymbolFromReferences?%5B%22%22%2C%5B%7B%22uri%22%3A%7B%22scheme%22%3A%22file%22%2C%22authority%22%3A%22%22%2C%22path%22%3A%22%2Fe%3A%2FProjects%2FPython%2Fmemory_analyzer%2Fmain.py%22%2C%22query%22%3A%22%22%2C%22fragment%22%3A%22%22%7D%2C%22pos%22%3A%7B%22line%22%3A13%2C%22character%22%3A11%7D%7D%5D%2C%2266ab22f5-0029-4c68-ba8b-ec2b26cc2e5e%22%5D "Go to definition"), ingresa el PID del proceso, la dirección de memoria (en formato hexadecimal) y el nuevo valor a escribir.

6. **Verificar Cambios de Memoria**:
    - Selecciona la opción [`6`](command:_github.copilot.openSymbolFromReferences?%5B%22%22%2C%5B%7B%22uri%22%3A%7B%22scheme%22%3A%22file%22%2C%22authority%22%3A%22%22%2C%22path%22%3A%22%2Fe%3A%2FProjects%2FPython%2Fmemory_analyzer%2Fmain.py%22%2C%22query%22%3A%22%22%2C%22fragment%22%3A%22%22%7D%2C%22pos%22%3A%7B%22line%22%3A14%2C%22character%22%3A11%7D%7D%5D%2C%2266ab22f5-0029-4c68-ba8b-ec2b26cc2e5e%22%5D "Go to definition") e ingresa el PID del proceso para verificar cambios en la memoria.

## Configuración

La configuración se encuentra en [`src/config/config.py`](command:_github.copilot.openRelativePath?%5B%7B%22scheme%22%3A%22file%22%2C%22authority%22%3A%22%22%2C%22path%22%3A%22%2Fe%3A%2FProjects%2FPython%2Fmemory_analyzer%2Fsrc%2Fconfig%2Fconfig.py%22%2C%22query%22%3A%22%22%2C%22fragment%22%3A%22%22%7D%2C%2266ab22f5-0029-4c68-ba8b-ec2b26cc2e5e%22%5D "e:\Projects\Python\memory_analyzer\src\config\config.py"). Puedes modificar los ajustes de configuración según sea necesario.

## Contribuir

¡Las contribuciones son bienvenidas! Por favor, abre un issue o envía un pull request para cualquier mejora o corrección de errores.

## Licencia

Este proyecto está licenciado bajo la Licencia MIT. Consulta el archivo LICENSE para más detalles.

## Agradecimientos

- [psutil](https://github.com/giampaolo/psutil) - Una biblioteca multiplataforma para obtener información sobre procesos en ejecución y el uso del sistema.
- [ctypes](https://docs.python.org/3/library/ctypes.html) - Una biblioteca de funciones externas para Python.
