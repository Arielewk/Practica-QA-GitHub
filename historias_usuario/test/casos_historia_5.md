# Casos de Prueba - HU-005: Visualizar Mapa de Incidentes

---

# TC-009

## Título
Visualización correcta del mapa de incidentes.

## Objetivo
Validar que el usuario pueda visualizar correctamente el mapa interactivo con los incidentes reportados.

## Precondiciones

- La plataforma SAFEZONE debe estar disponible.
- Deben existir incidentes registrados con ubicación geográfica.
- El usuario debe haber iniciado sesión.

## Datos de prueba

| Campo | Valor |
|--------|-------|
| Categoría | Robo |
| Nivel de zoom | 100 % |

## Pasos

1. Iniciar sesión en la plataforma.
2. Acceder al módulo **Mapa de Incidentes**.
3. Verificar que el mapa interactivo se cargue correctamente.
4. Observar los marcadores correspondientes a los incidentes registrados.
5. Seleccionar un marcador para visualizar la información del incidente.
6. Aplicar el filtro por categoría **Robo**.
7. Acercar y alejar el mapa utilizando los controles disponibles.

## Resultado esperado

- El mapa se muestra correctamente.
- Cada incidente aparece representado mediante un marcador.
- Al seleccionar un marcador se visualiza la información del incidente.
- Los incidentes corresponden a su ubicación geográfica real.
- El filtro por categoría funciona correctamente.
- El usuario puede acercar y alejar el mapa sin inconvenientes.

## Resultado obtenido

Pendiente de ejecución.

## Estado

Pendiente

## Notas / Evidencias

Pendiente de agregar capturas de pantalla o registros de ejecución.

---

# TC-010

## Título
Visualización del mapa cuando no existen incidentes registrados.

## Objetivo
Validar que el sistema responda correctamente cuando no existen incidentes para mostrar en el mapa.

## Precondiciones

- La plataforma SAFEZONE debe estar disponible.
- No deben existir incidentes registrados para la categoría seleccionada.
- El usuario debe haber iniciado sesión.

## Datos de prueba

| Campo | Valor |
|--------|-------|
| Categoría | Desastre Natural |

## Pasos

1. Iniciar sesión en la plataforma.
2. Acceder al módulo **Mapa de Incidentes**.
3. Aplicar el filtro por la categoría **Desastre Natural**.
4. Esperar la carga del mapa.

## Resultado esperado

- El mapa se carga correctamente.
- No se muestran marcadores debido a la ausencia de incidentes.
- El sistema informa mediante un mensaje que no existen incidentes para los criterios seleccionados.
- La aplicación continúa funcionando normalmente y permite modificar el filtro o realizar una nueva consulta.

## Resultado obtenido

Pendiente de ejecución.

## Estado

Pendiente

## Notas / Evidencias

Pendiente de agregar capturas de pantalla o registros de ejecución.
