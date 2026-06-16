# Proyecto Analisis de ventas con Power Quey y Power Pivot

## Descripción del problema

La empresa necesita un analisis de las ventas del año, pero las bases de datos en excel tiene distintos formatos lo que impide visualizar datos de calidad.

El objetivo del proyecto es limpiar y transformar los datos en Power Query y crear un modelo en Power Pivot que nos permita:

- conocer la venta total por mes.
- Rendimiento por País.
- Top 10 productos mas vendidos.
- Rendimiento por Categoria de productos.
- Canal con mayor demanda.

---

## Fuente de datos

Ralación de distintas Tablas excel:
- Ventas_Raw
- Prodecutos_Raw
- Clientes_Raw

Problemas de datos:
- Distintos formatos de fecha y precio.
- Duplicidad de ID.
- No estandarizados, con espacios, inconcistencia en texto.
- Registros sin trazabilidad.
- Valores faltantes.

---

## Proceso de Anális

La limpieza de datos se realizo en Excel utilizando Power Query y Power Pivot.

Etapas
- Carga de datos a power Query.
-Limpieza y estandarización:
 - normalización de textos.
 - homologación de categorías.
 - conversión de fechas.
- creacion de tabla calendario.
- Carga al modelo en Power Pivot.
- Relación de tablas.
- Construcción de medidas.
- Visualización de datos.
- Analisis de rendimiento.

---

## Resultados

**Ventas por Mes**

- Promedio mensual MM$5
- Mayor venta MM$6 abril, junio, octubre y noviembre
- Menor venta MM4 Febrero

**Rendimiento por País**

- EL País con mayo venta es Chile con MM$14
- El País con menor venta es Maxico con MM$10

**Categorias mas Vendida**

- La categoria mas bendida son los lacteos, sin embargo no hay diferencia significativa con el resto.

**Top 10 Productos mas Vendidos**

- Los 3 productos estrella son el lavaloza con 39 UN, las papas con 38 UN y el jugo con 37
- El producto menos vendido del top es la Energética con 33 UN

**Demanda por Canal**

- El canal con mas demanda es Online representando un 43% seguido del presencial con 41%


Se identifico disminucion de venta en el mes de febrero y en Mexico sin embargo no son señales de alerta debido a que igual se mantienen dentro de un rango cercano.

---

**Insight clave de negocio**

- Estabilidad en venta durante el año. 
- buena distribucion de productos no existe dependencia de un solo producto.
- Presencia regional equilibrada a persar de las pequeñas diferencias.
- El consumo por categoria son concentra en productos de alta rotación.
- El Canal mixto no representa mucho impacto debido a que las compras generalmente se realizan presencial u online.

---

## Imagenes.

***Ventas por Mes***

<img width="3065" height="651" alt="Venta por MES" src="https://github.com/user-attachments/assets/73c353f2-a49c-4c34-929a-f6b4e057f2b9" />

***Ventas por País***

<img width="385" height="264" alt="Por país" src="https://github.com/user-attachments/assets/b04e7b1d-fa32-464d-a929-f24326d58094" />

***Top 10 Productos***

<img width="1231" height="914" alt="Top productos" src="https://github.com/user-attachments/assets/359115a4-47b8-4822-b06f-18bd43c0dc45" />

***Demanda por canal***

<img width="976" height="698" alt="Por Canal" src="https://github.com/user-attachments/assets/8d436c32-f41a-472a-af6d-5a212d82286b" />

***Venta por Caterogia***

<img width="2085" height="702" alt="Por Categoria" src="https://github.com/user-attachments/assets/70d9c840-2dd3-4336-9a62-1eee1d4a657c" />

---

## Conclusión.

El negocio muestra una operación estable y diversificada, con ventas equilibradas entre países, productos y canales. Los mayores impulsores son Chile, la categoría de Lacteos y los canales Online/Tienda. La principal oportunidad está en potenciar Mexico y reforzar estrategias comerciales en los meses de menor desempeño (febrero).

---

## Problemas de calidad de los datos.

Se detectaron productos sin precio y sin descuento lo cual afecta la calidad del resultado.

---

## Recomendaciones

Para obtener un analisis completo y mejorar la toma de decisiones se deben crear las siguientes medidas.
- Visualizar ventas YTD.
- Variacion vs mes anterior.
- Ticket medio.
- Margen Bruto










