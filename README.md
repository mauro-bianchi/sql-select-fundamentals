Es mala práctica usar SELECT* en producción porque consume tiempo, memoria y no es eficiente ya que rara vez necesitas toda la información de la tabla. En cuanto a rendimiento, es poco beneficioso traer tantos datos a la vez cuando no los precisas, y en términos de seguridad podes mostrar datos que no precisas mostrar.

Son importantes los ALIAS para un stakeholder no técnico porque puede no saber qué significa el nombre que tiene cada columna, solo maneja información y no está directamente involucrado en la confección de las columnas/tablas. 
Un ALIAS transforma una columna llamada "total_amount" en "cantidad_total" que es entendible por todos.
