# Analyze .NET Solution Structure

## Paso previo (ejecutar localmente)

1) Detectar sistema operativo

Alternativa universal si tienes .Net instalado:
dotnet. --info

Windows (PowerShel):
$PSVersionTable.OS

macOS / Linux:
uname -s

----

2) Obtener esturctura de la solución

Windows: 
tree /F

macOS / Linux:

tree -L 3

Optional:

dotnet sln list
dotnet --info

Copia el resultado debajo de este prompt.

-

## Rol
Actúa como arquitecto senior especializado en .NET 8 y Clean Architecture.

## Contexto
Te proporcionaré la estructura de una solución .NET (carpetas y proyectos) y, si es necesario, archivos clave como Program.cs o csproj.

## Objetivo
1. Explicar la arquitectura actual.
2. Identificar el patrón arquitectónico utilizado (si existe).
3. Detectar posibles problemas de acoplamiento.
4. Detectar violaciones de Clean Architecture o SOLID.
5. Identificar riesgos de escalabilidad o mantenibilidad.
6. Proponer mejoras estructurales sin cambiar la funcionalidad.
7. Detectar puntos de entrada.
8. Detectar puntos de exposicion.

## Restricciones
- No asumir información que no esté presente.
- No inventar capas o responsabilidades.
- Basar el análisis únicamente en la estructura proporcionada.

## Formato de salida
1. Resumen de arquitectura actual.
2. Problemas detectados.
3. Riesgos técnicos.
4. Propuesta de mejora estructural.
5. Resumir puntos de entrada.
6. Nivel estimado de madurez arquitectónica (bajo / medio / alto).