# DELLDeals

Proof of concept for fast scrapping web with nodejs + casperjs.
The spanish Dell webpage is too slow. It is very crazy surf that web.
This is a shell script with nodejs to get spanish super-deals of Dell rack servers directly.

## Getting Started

### Installation

You need `nodejs` and two modules:

```
npm -g install phantomjs
npm -g install casperjs
```

Reminder: PATH_NODE to the correct node modules location

```chmod 755 DELLPrices```

### Usage

If you deployed in your $PATH:
``DELLPrices``

If not: 

``./DELLPrices``

### Output

```
Solicitando informacion a DELL....
Servidores para rack Dell PowerEdge | Dell España
Modelos: 15
Servidor para rack ultracompacto Dell PowerEdge R210 II | Dell España
	Precio: 741€
	Oferta web: 399€
	Oferta Valida: 2014-08-07
Servidor para rack PowerEdge R220 | Dell España
	Precio: undefined
	Oferta web: undefined
	Oferta Valida: undefined
Detalles del servidor para rack PowerEdge R320 | Dell España
	Precio: 955€
	Oferta web: 599€
	Oferta Valida: 2014-08-07
PowerEdge R415 1U Rack Server Details | Dell España
	Precio: 1.437€
	Oferta web: 939€
	Oferta Valida: 2014-08-07
Detalles del servidor para rack PowerEdge R420 | Dell España
	Precio: 1.385€
	Oferta web: 799€
	Oferta Valida: 2014-08-07
PowerEdge R515 2U Rack Server Details | Dell España
	Precio: 1.662€
	Oferta web: 1.049€
	Oferta Valida: 2014-08-07
Detalles del servidor para rack PowerEdge R520 | Dell España
	Precio: 1.650€
	Oferta web: 1.029€
	Oferta Valida: 2014-08-07
Detalles del servidor para rack PowerEdge R620 | Dell España
	Precio: 2.107€
	Oferta web: 1.449€
	Oferta Valida: 2014-08-07
Detalles del servidor para rack PowerEdge R715 de 2U | Dell España
	Precio: undefined
	Oferta web: 3.834€
	Oferta Valida: 2014-08-07
Detalles del servidor para rack PowerEdge R720 | Dell España
	Precio: 2.217€
	Oferta web: 1.349€
	Oferta Valida: 2014-08-07
Detalles del servidor para rack PowerEdge R720xd | Dell España
	Precio: 2.279€
	Oferta web: 1.559€
	Oferta Valida: 2014-08-07
Detalles del servidor para rack PowerEdge R815 | Dell España
	Precio: undefined
	Oferta web: 5.015€
	Oferta Valida: 2014-08-07
Detalles del servidor para rack PowerEdge R820 | Dell España
	Precio: undefined
	Oferta web: 14.327€
	Oferta Valida: 2014-08-07
Detalles del servidor para rack PowerEdge 11G R910 | Dell España
	Precio: undefined
	Oferta web: 10.217€
	Oferta Valida: 2014-08-07
Servidor para rack PowerEdge R920 | Dell España
	Precio: undefined
	Oferta web: 22.176€
	Oferta Valida: 2014-08-07
```
