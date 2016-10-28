peru-geojson
============
Archivos GeoJSON con los polígonos que representan a departamentos, provincias y distritos del Perú.

Archivos disponibles
--------------------
* peru_departamental_simple.geojson
* peru_provincial_simple.geojson
* peru_distrital_simple.geojson

Información disponible por archivo
----------------------------------
* peru_departamental_simple.geojson

```json
{"type":"Feature","properties":{
"NOMBDEP":"AMAZONAS",
"COUNT":84,
"FIRST_IDDP":"01",
"HECTARES":3930646.567
},
"geometry":
{"type":"Polygon","coordinates":[[]]}}
```

`NOMDEP` es el nombre del departamento, `FIRST_IDDP` es su código de Ubigeo.

* peru_provincial_simple.geojson

```json
{"type":"Feature","properties":{
"COUNT":9,
"FIRST_IDPR":"0301",
"NOMBPROV":"ABANCAY",
"FIRST_NOMB":"APURIMAC",
"LAST_DCTO":"LEY",
"LAST_LEY":"S/N",
"FIRST_FECH":"28/12/1961",
"LAST_FECHA":"21/11/1893",
"MIN_SHAPE_":345827.33624,
"ha":345827.34
},
"geometry":{"type":"Polygon","coordinates":[[]]}
}
```

`NOMPROV` es el nombre del departamento, `FIRST_IDPR` es su código de Ubigeo.

* peru_distrital_simple.geojson

```json
{"type":"Feature","properties":{
"OBJECTID":1,
"IDDIST":"230110",
"IDDPTO":"23",
"IDPROV":"2301",
"NOMBDIST":"CORONEL GREGORIO ALBARRACIN LANCHIPA",
"NOMBPROV":"TACNA",
"NOMBDEP":"TACNA",
"DCTO":"LEY",
"LEY":"27415",
"FECHA":"02/02/2001",
"NOM_CAP":"ALFONSO UGARTE",
"SHAPE_LENG":0.570509667,
"SHAPE_AREA":0.0161399587,
"SHAPE_LE_1":0.57019506331,
"SHAPE_AR_1":0.01598980139,
"AREA_MINAM":18834.14
},
"geometry":{"type":"Polygon","coordinates":[[]]}
}
```

`NOMBDIST` es el nombre del departamento, `IDDIST` es su código de Ubigeo.

* peru_provincias_captial_provincia.geojson

```json
{
	"type": "Feature",
	"properties": {
		"FID": 0,
		"CAPITAL": "CABANA",
		"DEPARTAM": "ANCASH",
		"PROVINCIA": "PALLASCA",
		"DISTRITO": "CABANA",
		"CLASIF02": "URBANO",
		"NOMCAT02": "PUEBLO"
	},
	"geometry": { "type": "Point", "coordinates": [] }
}
```

Fuente
------
Información disponible en formato ShapeFile en la web de [Geoservidor - MINAM](http://geoservidor.minam.gob.pe/geoservidor/download.aspx) y
en [GEOIDEP](http://www.geoidep.gob.pe/)

* Límite Departamental (Fuente: INEI-2007)
* Límite Provincial (Fuente: INEI-2007)
* Límite Distrital (Fuente: INEI-2007)
* Capitales de Provincia (Fuente: IDEP-2016)

Método de transformación de Shapefiles a GeoJSON
------------------------------------------------
Próximamente, no fue una transformación directa.
