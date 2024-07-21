###   MATEMATICA FINANCIERA   ###

Es una parte de la matematica que calcula como va cambiando con el tiempo el valor del dinero.

- Concepto:
	*Interes: es la compensacion que paga el deudor al acreedor por haber recibido cierta cantidad de dinero.
	El interes tiene distintas variables que lo condicionan:
	. I = f(P,t,i,s.c.)
	I = interes
	P = Valor del dinero prestado (monto)
	t = tiempo que el deudor devuelva el prestamo
	i = tasa de interes (tasa de referencia que acuerdan el deudor y el acreedor, se calcula cuanto debe pagar el deudor cada $100 en concepto de interes al transcurrir cierta cantidad de tiempo. Por ejemplo una tasa de interes por 18% anual indica que cada año cada $100 va a pagar $18)
	s.c. = sistema de capitalizacion. Es el metodo con el cual se calcula el interes:
	. Simple: el interes generado en cada periodo se va apartando.
	. Compuesto: el interes generado se agrega al capital inicial, en el segundo periodo se agrega al capital acumulado generando un interes mas elevado y asi sucesivamente.
	Ej: Sistema de capitalizacion simple: Una persona presta a otra 145000, con capitalizacion simple, pactando una tasa de interes del 18.3% bimestral, por un plazo de 175 dias.
	$100 ............ $ 18,30
	$145.000 ........ x = ($145.000 * $18,30) / $100 = $26.535 => Por bimestre
	
	1 bimestre ...... $ 26.535
	175 dias ........ Z = [(26.535 * 175) / 1 bimestre] * 1 bimestre/60 dias => I = $77.393,80
	Expresion General  I = P * i * n
	n = numero de periodos
	
	Si queremos calcular el monto que recibe el acreedor al  final va a ser:
	F = P + I
	F = P + P * i * n
	F = P( 1 + i * n)

	Ejemplo: Que tasa de interes anual se aplico a un prestamo con capitalizacion simple, si el acreedor recibio el 50% mas de lo que presto, luego de 416 dias?
	i = [(F / P)-1] / n
	i = [(1,5P / P) - 1]/416 dias * (1 año/360 dias) = 0,433 / año
	i = 43,3% anual

	
	Ejemplo de Capitalizacion Compuesta:

	0		1		2		3		4
	0 ... P
	1 ... P + I1 = P + P * i * 1 = P (1 + i)
	2 ... P(1+i) + I2 = P(1+i) + P(1+i) * i * 1 = P(1+i) * (1+i) = P(1+i)e2
	3 ... P(1+i) + I3 = P(1+i)e2 + P(1+i)e3 * i * 1 = P(1+i)e2 * (1+i) = P(1+i)e3
	  ...
	n ... P (1+i)n

	Expresion General F = P(1 + i)n

	A considerar al realizar calculos con capitalizacion compuesta:
	*Es utilizada comercialmente (no se aclara), en cambio si es capitalizacion simple si hay que aclarar.
	*La expresion de calculo es exponencial. El error se propaga rapidamente. Lo que obliga a no aproximar o redondear los datos. Utilizar todos los datos que admita la calculadora.
	*El periodo de capitalizacion es el mes. El tiempo y la tasa de interes deben convertirse a esta unidad. Es importante fijar un periodo de capitalizacion.

	Ejemplo: Que monto de dinero se coloco a plazo fijo hace 178 dias si hoy se retiraron $198200? La tasa aplicada fue 26,5% na(anual)
	P = F/(1+i)^n = $198.200/(1+0,265/año * 1 año / 12 mes) 178 dias * 1 mes/30 dias
	P = $174.107,80


	* DESCUENTO: es una operacion comercial que consiste en el intercambio de un documento con vencimiento futuro por efectivo. El que entrega el documento recibe una actualizacion o descuento, en concepto de interes.
	D = F - P
	D = F - F/(1+i)n
	D = F * [ 1 - (1 + i)^-n ]

	Ejemplo: Cual fue el importe que recibio una persona que entrego un cheque de pago diferido, si al actualizarlo recibio un descuento de $12.700, a 139 dias del vencimiento y con una tasa de interes del 75% anual?.
	P = F - D
	P = D /[ 1 - (1 + i)^-n ] - D
	P = 12.700/[ 1 - (1+0,75/12) - 139/30] - 12.700
	P = $39.159,70
	


###   DIAGRAMAS DE FLUJO   ###

Es una representacion grafica de una cantidad de dinero en un eje de tiempo, se elige una escala conveniente.

Escala
$ 10.000 = 1cm

INGRESOS	    0   		1		   2		    3
--------------------|-------------------|------------------|----------------|
EGRESOS


- Serie Uniforme: esta constituida por flujos monetarios constantes todos del mismo valor en forma ininterrumpida desde el primero al ultimo periodo aplicando siempre la misma tasa de interes.


0    1      2      3      4				n-2    n-1     n   
-----|------|------|------|------------------------------|------|------|------> t
     A      A      A      A  ........................... A      A      A
								       F
					i

F = A(1+i)n-1 + A(1+i)n-2 + A(1+i)n-3 + ... + A(1+i)2 + A(1+i)1 + A     1

Multiplicamos miembro a miembro por (1+1)

F(1+i) = (1+i) [A(1+i)n-1 + A(1+i)n-2 + A(1+i)n-3 + ... + A(1+i)2 + A(1+i)1 + A]
F(1+i) = A(1+i)n + A(1+i)n-1 + A(1+i)n-2 + ... + A(1+i)3 + A(1+i)2 + A(1+i)    2
Restamos miembro a miembro 2 - 1
F(1+i) - F = A(1+i)n - A
F * i = A[(1+i)n -1]

Expresion final =>   F = A*[(1+i)n - 1] / i

Ejemplo: que monto de dinero hay que depositar mensualmente a plazo fijo para reunir $1.200.000 en 5 años?. Considerar una tasa de interes del 12,8% anual.

F = A*[(1+i)n - 1] / i
A = F * i / (1+i)^n - 1

A = 1.200.000 * 0,128/12 / (1 + 0,128/12)60 - 1
A = $ 14.381


###   ANALISIS E INTERPRETACION DE ESTADOS CONTABLES   ###

- Fuentes: informes que presentan las empresas cuando culminan un ejercicio economico. Los informes fundamentales son el Balance General y el Estado de Resultado. Hay otros que amplian la informacion, denominados notas o cuadros anexos:
	*Notas: desarrollos o descripciones que no tienen un orden particular.
	*Cuadros: son estructuras predeterminadas.
	*Estado de evolucion del patrimonio neto: siempre tiene que aparecer cuando el patrimonio neto se muestra con un unico valor en el Balance General. Muestra las variaciones que muestran cada uno de los rubros del patrimonio neto.
	*El cuadro de bienes de uso: hace una descripcion de todas las cuentas que forman parte de este rubro. Aumentos, reducciones, valores netos, amortizaciones.
	*Estado de origen y aplicacion de fondos: cash flow, muestra como se llega al valor actual o ultimo del rubro Caja y Bancos.
	*Cuadro de gastos: es obligatorio para Sociedades Anonimas. Complementa informacion con las cuenta de egresos. Detalle de cada cuenta. El valor que corresponde a cada tipo de gasto (Operativo, Comercializacion, Costo de Ventas, Otros).

- Destinatarios:
	*Propios: Dueños, Gerenciadores (administradores), Empleados.
	*Ajenos: Proveedores, Clientes, Bancos, Inversores, Estado.

###   ESTADO DE LA EMPRESA   ###

¿ Que es lo que se quiere conocer ?

- Estado Patrimonial: muestra la esctructura de la empresa, que es lo que tiene, que es lo que le deben, a quien le debe, que cantidad le debe a cada uno, en que momento tiene que pagar, costos de cada sector, que le queda neto, etc, etc...

- Estado economico: indica la capacidad que tiene la entidad para generar ganancias, siempre teniendo en cuenta de un monto invertido. El estado economico regleja la capacidad de rentabilidad que tiene la empresa.

- Estado financiero: muestra la capacidad que tiene la entidad de pagar las deudas que contrajo. Hace una relacion entre recursos disponibles y obligaciones contraidas.


###   METODOS DE ANALISIS   ###

- Porcentajes Verticales: es un metodo considerado estatico, hace un estudio en un momento determinado de la empresa en la culminacion de un ejercicio economico. Es como analizar una foto de la empresa. Se elige un elemento que se toma como base y se hacen comparaciones. Por ejemplo se puede tomar como base el Activo Corriente, se van a relacionar todos los rubros que forman parte del activo corriente contra ese elemento principal, se establece que porcentaje de participacion tiene cada uno en el Activo Corriente. Se pueden elegir diferentes conceptos que se considere escenciales y establecer la relacion que hay con otros que estan subordinados a ellos.
Permite obtener informacion patrimonial, como esta conformado el activo, el pasivo, en que gasta la empresa, cual es la rentabilidad neta que obtiene. Permite establecer el estado patrimonial.

- Porcentajes Horizontales: estudio dinamico, analiza la empresa a traves del tiempo. Al anterior metodo lo comparamos con una foto, este metodo seria como una pelicula. Se estudia la evolucion de la empresa a traves del tiempo. Se toma un ejercicio economico como modelo/patron/referencia y se van a comparar todos los estados contables que se quieran contra ese modelo y se van a establecer las diferencias que aparecen. Es importante elegir bien, no elegir ni el mejor ni el peor estado contable, tiene que ser un estado contable promedio, referenciado.

- Numeros Indices: establecer relaciones entre cuentas o grupo de cuentas, de distinto tipo. Las relaciones que se pueden establecer son multiples. Hay que tener en cuenta que tipo de empresa se esta estudiando, pequeña, mediana o grande, a que se dedica, que rubro explota, si es industrial, comercial o de servicios, su ubicacion, tipo de actividad economica del pais, valores de las variables economicas, PBI, etc. Todo esto hay que considerarlo para dar un informe particular para la empresa.


###   Ejemplos   ###

###   METODO DE PORCENTAJES VERTICALES   ###

Activo			7424223			100%

Activo Corriente	3193977		100%	43%	(3193977 / 7424223) * 100
Caja y Bancos		872009		27%	12%
Cred por Ventas		402995		13%	5%
Otros Creditos		693070		22%	9%
Bienes de Cambio	1225903		33%	17%

Activo no Corriente	4230246		100%	57%
Otros Creditos 		3245978		77%	44%
Bienes de uso		984268		23%	13%


Pasivo			6728347			100%	91%

Pasivo Corriente	4728347		100%	70%
Cuentas por Pagar	232757		5%	3%
Remun. Y C. Soc.	98426		2%	1%
Deudas Fiscales		141400		3%	2%
Deudas Financieras	4116887		87%	61%
Otras Deudas		138877		3%	2%

Pasivo no Corriente	2000000			30%
Deudas Financieras	2000000			30%

Patrimonio Neto		695876				9%
Pasivo + P. Neto	7424223				100%


Estado de Resultados

Ventas			6740035		100%
Costo de Ventas		(5841797)	86.7%
Resultado Bruto		898238		13.3%

Gs de Administracion	(320919)	4.8%
Gs de Comerc.		(4633)		0.1%
Gs Financieros		(386573)	5.7%
Result ant de imp.	186113		2.8%

Imp. a las Ganancias	(136787)	2%

Resul. del ejerc.	49326		0.7%


###   METODO DE PORCENTAJES HORIZONTALES   ###

Activo			Año Base	Indices		2018		Indices		2019		Indices

Activo Corriente	4935315		100		3349727		68		3193977		65

Caja Y Bancos		773374		100		398063		51		872009		113
Cred. por Ventas	1668208		100		806954		48		402995		24
Otros Creditos		943928		100		796312		84		693070		73
Bienes de Cambio	1549805		100		1348398		87		1225903		79

Activo No Corriente	4083079		100		3179671		78		4230246		104

Otros Creditos		2957940		100		1985015		67		3245978		110
Bienes de Uso		1125139		100		1194656		106		984268		87

Total Activo		9018394		100		6529398		72		7424223		82

Se divide el valor del concepto por el valor del año base y se multiplica por 100. Ej. (3349727/4935315)*100 = 68
Si esta por debajo de 100 hubo una involucion o un decrecimiento del rubro, y si esta por encima de 100 hubo un crecimiento. Mientras mas alejado del 100 esta quiere decir que hubo mas cambio.


Pasivo + Patrimonio Neto			Indices			Indices			Indices

Pasivo Corriente		7371844		100	5216691		71	5628347		76

Cuentas por pagar		5982492		100	4556775		76	4232757		71
Remun. y C. Soc.		174138		100	139663		80	298426		171
Deudas Fiscales			52521		100	85534		163	341400		650
Deudas Financieras		1033333		100	336719		33	616887		60
Otras Deudas			129360		100	98000		76	138877		107

Pasivo no Corriente		1000000		100	700000		70	800000		80

Deudas Financieras		1000000		100	700000		70	800000		80

Total Pasivo			8371844		100	5916691		71	6428347		77

Patrimonio Neto			646550		100	612707		95	995876		154

Total Pasivo + PN		9018394		100	6529398		72	7424223		82




E. De Resultados		Año Base	Indices	2007		Indices	2008		Indices

Ventas				9170180		100	8554714		93	9740035		106
Costo de Ventas			(7931669)	100	(7642092)	96	(8241797)	104
Ganancia Bruta			1238511		100	912622		74	1498238		121

Gastos de Comerc.		(117061)	100	(93749)		80	(114633)	98
Gastos de Administ.		(854751)	100	(728483)	85	(920919)	108
Resultados Financ.		(66604)		100	(46853)		70	(66573)		100
Utilidad Operativa		200095		100	43537		22	396113		198

Imp. a las Ganancias		(53500)		100	(12560)		23	(136787)	256
Result. del Ejercicio		146595		100	30977		21	259326		177	


###   NUMEROS INDICES   ###

- Indices de Actividad: van a mostrar distintas facetas del accionar que tiene la entidad, por ejemplo el tiempo que tarda en cobrarle a sus clientes.
	*Rotacion del Activo Fijo = Ventas / Activo Fijo. Marca el grado de utilizacion que le da la empresa a los elementos que dispone, el numero de veces que lo utiliza. Mientras mas alto sea la rotacion del activo mas provechoso va a ser para la empresa. Siempre teniendo en cuenta el rubro de la empresa. Por ejemplo en una empresa industrial el activo fijo es bastante alto por lo cual no va a tener una rotacion muy elevada. Pasa lo contrario en una empresa de servicios, la rotacion va a ser mucho mas elevada.
	*Rotacion del Activo = Ventas / Activo
	*Indice de Inmovilizacion = (Activo Fijo / Patrim. Neto) * 100
	*Inventarios sobre Capital de Trabajo = (Bienes de Cambio / Capital de Trabajo) * 100. Hace una relacion entre las mercaderias y las materias primas con respecto al capital de trabajo, o como se llama el capital corriente (la diferencia entre el activo corriente y el pasivo corriente). El colchon del cual dispone la empresa para realizar inversiones o gastos.
	*Creditos sobre Capital Corriente = (Cuentas por Cobrar / Capital de Trabajo) * 100
	*Indice de Existencias = (Bienes de Cambio / Ventas) * 100
	*Rotacion del Inventario = Mercaderias / (costo de Mercaderias Vendidas / 360 dias)
	*Plazo Medio de Cobranzas = Creditos / (Ventas / 360 dias). Aca lo que se calcula es la cantidad promedio de dias que tarda la empresa en cobrar los creditos que concede. Mientras mas alto sea este valor es peor para la empresa. El plazo medio de cobranza tiene que ser lo mas bajo posible.
360 es la cantidad de dias comerciales en un año.

- Indices de Estructura: estos indicadores permiten determinar como estan costituidos distintos aspectos de la organizacion. Estos indicadores si se aplico anteriormente el metodo de Porcentajes Verticales ya se calcularon.
	*De Mantinimiento = (Gs de Mantenimiento / Ventas) * 100
	*De Publicidad = (Publicidad / Ventas) * 100
	*De Gs de Comercializacion = (Gs de comercializacion / ventas) * 100
	*De Gs Administrativos = (Gs de Administrativos / Ventas) *100

- Indices de Endeudamiento: nos van a permitir evaluar que tan consolidada esta la empresa teniendo en cuenta la composicion de sus pasivos y la relacion con el Activo y el PN.
	*De Endeudamiento = (Pasivo / Activo) * 100. Cuanto de lo que se le debe a terceros es parte de lo que tiene la empresa.
	*De Deuda Corriente = (Pasivo Corriente / Pasivo) * 100. Cuanto de lo que se le debe a terceros hay que pagarlo antes del año.
	*De Deuda no Corriente = (Pasivo no corriente / Pasivo) * 100. Cuanto de lo que se le debe a terceros hay que pagarlo despues del año.
	*De Estructura de Capital = (Pasivo Total / Patrimonio neto) * 100. Relaciona todo lo que se debe a terceros con todo lo que se le debe a los dueños.

- Indices de Liquidez: son escenciales, unicos para calcular los estados financieros.
	*De Solvencia o Liquidez Corriente = (Activo Corriente / Pasivo Corriente) * 100. Relaciona lo que la empresa tiene dentro del año con lo que tiene que pagar dentro del año. Deberia dar encima de 100 para que la empresa este tranquila sabiendo que va a disponer mas de lo que tiene que pagar.
	*De Liquidez = (Caja y Bcos + Inversiones Temporarias + Cred. corto plazo * 100) / Pasivo Corriente. Hace una relacion mas pretenciosa, relaciona lo que hay que pagar dentro del año con lo que se tiene ahora. Nos debe dar un numero menor que el de Solvencia o Liquidez Corriente.
	*De Liquidez Inmediata (Prueba acida) = (Caja y Bancos / Deudas a corto plazo) * 100. Es el que hace un analisis a la brevedad. Se compara lo que hay que pagar inmediatamente con lo que se tiene a mano. Con este indicador sabriamos si en el corto plazo va a hacer falta recurrir a un financiamiento externo o no.

- Indices de Rentabilidad: nos van a mostrar la capacidad que tiene la empresa para generar ganancias. Nos van a exibir el estado economico.
	*Margen de Utilidad Bruta = ( (Ventas - Costo de Ventas) / Ventas ) * 100
	*De Rentabilidad del Patrimonio = (Utilidad Neta / Patrim. al inicio del ejercicio) * 100. El mas importante o fundamental. Relaciona el resultado neto del ejercicio con respecto al patrimonio. Se debe comparar lo que se gano con lo que se invirtio, no con lo que se tiene al final. Hay que buscar el valor del patrimonio cuando comenzo este ejercicio que se esta estudiando. 
	*De Rentabilidad del Activo = (Utilidad Neta / Activo) * 100
	*Margen de Resultados sobre Ventas = (Utilidad Neta / Ventas) * 100
	*Rendimiento por accion = Utilidad Neta / Acciones emitidas. Nos permite saber cuanto se gano por accion emitida. Esta informacion le interesa al propietario porque va a saber cuanto le rindio cada accion.


###   Otros Indicadores   ###

- Efecto Palanca o Leverage = (Resultado Neto / Patrimonio Neto) / (Resultado Neto + RFPLP / P. Neto + Pasivo no Cte.). Lo que hace es comparar los beneficios que obtiene la empresa con la inversion que realizo y lo que paga en concepto de financiacion ajena. Si da mayor a 1 la empresa le esta sacando jugo a lo pedido prestado.

- Du Pont = (Utilidad Neta / Ventas) * (Ventas / Activo). Cuanto se gana con respecto a lo que tiene la empresa.

- Pares = (Ventas/Activo) * (BAII/Ventas) * (Activo/Capital Propio) * (BAI/BAII) * (Beneficio Neto/BAI)
Rotacion - Margen - Apalancamiento Financiero - Efecto fiscal
Nos a permitir obtener la rentabilidad del patrimonio
