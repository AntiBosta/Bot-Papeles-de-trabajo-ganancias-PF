# Robot descarga de papeles de trabajo para presentar ganancias 2023:

Este documento te guiara en un paso a paso para la ejecucion del robot.: 

## 1. COMPLETAR EXCEL QUE ALIMENTA EL ROBOT (info_papeles_de_trabajo)

- Abrir el archivo de excel `info_papeles_de_trabajo.xlsx` que se encuentra en la carpata raiz del repositorio

- Completar la CUIT, clave de acceso afip y CUIT en pagina de afip (seria el cuit representado)

- La columna CUIT para algunos selectores, agregar al cuit de pagina de afip este formato (20-00000000-0)

- Revisar la direccion de guardado en las formulas: `CONCATENAR("C:\Users\estudio\Documents\UiPath\Papeles de trabajo ganancias pf\REPORTES\";E2;"SISA1.PDF")`

- En los periodos y fechas tener en cuenta poner delante `'` porque sino uipath lo toma como texto

- En firefox tener como impresora predeterminada `IMPRESORA PDF`

## 2. EJECUTAR EL ROBOT:

- Doble clic en main

- click en ejecutar proceso.

## Referencias

Bot creado por Gino Gambarotto

## Redes Sociales

- LinkedIn: https://www.linkedin.com/in/gino-gambarotto-66363b227/

- X: https://x.com/colifa1993

- GitHub: https://github.com/AntiBosta
