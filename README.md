# Ejercicios-Cypress
CP001 - Validar cuotas en compra de equipo -Cuotas.3 -Equipo.A14 
Descripción: El objetivo del caso de prueba es visitar la tienda de Movistar (https://tiendaonline.movistar.com.ar), luego realizar la búsqueda del equipo A14 e ingresar al mismo y verificar que se pueda pagar en 3 cuotas sin interes
Resultado esperado:
- Que se pueda ingresar a la página indicada
- Que el equipo seleccionado sea el A14
- Que se indique en el equipo que puede ser pagado en 3 cuotas sin interes

De no estar disponible el equipo A14 tomar alguno que si lo esté.

CP002 - Aplicar filtro de equipos  -Memoria Interna.128GB -Precio Entre 200Ky300K
Descripción: El objetivo del caso de prueba es visitar la tienda de Movistar (https://tiendaonline.movistar.com.ar), luego utilizando los filtros de la página, filtrar por Memoria Interna 128GB y precio entre “$200.000 - $300.000” e indicar cuantos equipos devuelve la búsqueda
Resultado esperado:
- Que se pueda ingresar a la página indicada
- Que se pueda aplicar los filtros
- Que se obtengan equipos luego del filtrado validando la cantidad mostrada

De no estar disponible alguno de los filtros indicados reemplazar por otro que si lo esté.

CP003 - Validar cuotas en compra de equipo -Cuotas.60 -Equipo.Tercero de la lista -Banco.Credicoop -Tarjeta.Visa 
Descripción: El objetivo del caso de prueba es visitar la tienda de Movistar (https://tiendaonline.movistar.com.ar), luego ingresar al tercer equipo de la lista inicial que se obtenga y verificar que NO exista el método de pago de 60 cuotas para el banco Credicoop con Tarjeta VISA. 
Resultado esperado: 
- Que se pueda ingresar a la página indicada 
- Que el equipo seleccionado sea el tercero de la lista 
- Que no exista un medio de pago con 60 cuotas para el banco Credicoop con tarjeta VISA 

CP004 - Agregar un caso que creas conveniente plantear y sea diferente a los 3 anteriores.
Algunos de los puntos que serán tenidos en cuenta en la resolución de los casos.
- Utilización de localizadores apropiados
- Utilización correcta de métodos de Assertions para validaciones 
- Utilización de comandos nuevos, tales como cy.screenshot, cy.url, cy.viewport, cy.*.as, etc. (https://docs.cypress.io/api/api/table-of-contents.html) 
- Utilización del modelo Page Objects (https://www.toolsqa.com/cypress/page-object-pattern-in-cypress/)
