## 📘 Diccionario de Datos - House Prices 🏠

---

### `MSSubClass` – Tipo de vivienda involucrada en la venta
- 20: 1 planta (1946 o más nueva, todos los estilos)
- 30: 1 planta (1945 o más vieja)
- 40: 1 planta con ático terminado (todas las edades)
- 45: 1 planta y media – sin terminar (todas las edades)
- 50: 1 planta y media – terminada (todas las edades)
- 60: 2 plantas (1946 o más nueva)
- 70: 2 plantas (1945 o más vieja)
- 75: 2 plantas y media (todas las edades)
- 80: Niveles múltiples
- 85: Split Foyer
- 90: Dúplex – todos los estilos y edades
- 120: 1 planta PUD (Urbanización planificada) – 1946 o más nueva
- 150: 1 planta y media PUD – todas las edades
- 160: 2 plantas PUD – 1946 o más nueva
- 180: PUD multinivel – incluye split level / foyer
- 190: Conversión a 2 familias – todos los estilos y edades

---

### `MSZoning` – Clasificación general de zonificación de la propiedad
- A: Agrícola
- C: Comercial
- FV: Residencial tipo "Floating Village"
- I: Industrial
- RH: Residencial de alta densidad
- RL: Residencial de baja densidad
- RP: Residencial baja densidad con parque
- RM: Residencial de densidad media

---

### `LotFrontage` – Largo (en pies) del frente conectado a la calle

---

### `LotArea` – Tamaño del lote en pies cuadrados

---

### `Street` – Tipo de acceso vial a la propiedad
- Grvl: Calle de grava
- Pave: Calle pavimentada

---

### `Alley` – Tipo de acceso por callejón
- Grvl: Grava
- Pave: Pavimento
- NA: Sin acceso por callejón

---

### `LotShape` – Forma general del terreno
- Reg: Regular
- IR1: Ligeramente irregular
- IR2: Moderadamente irregular
- IR3: Irregular

---

### `LandContour` – Relieve del terreno
- Lvl: Casi plano / nivelado
- Bnk: Elevado – subida rápida desde la calle a la casa
- HLS: Ladera – pendiente significativa de lado a lado
- Low: Depresión

---

### `Utilities` – Servicios disponibles
- AllPub: Todos los servicios públicos (Electricidad, Gas, Agua y Cloacas)
- NoSewr: Electricidad, Gas y Agua (pozo séptico)
- NoSeWa: Solo Electricidad y Gas
- ELO: Solo electricidad

---

### `LotConfig` – Configuración del terreno
- Inside: Terreno interior
- Corner: Terreno en esquina
- CulDSac: Calle sin salida
- FR2: Frente a calle en 2 lados
- FR3: Frente a calle en 3 lados

---

### `LandSlope` – Inclinación del terreno
- Gtl: Suave
- Mod: Moderada
- Sev: Severa

---

### `Neighborhood` – Ubicación física dentro de los límites de la ciudad de Ames
- Blmngtn: Bloomington Heights  
- Blueste: Bluestem  
- BrDale: Briardale  
- BrkSide: Brookside  
- ClearCr: Clear Creek  
- CollgCr: College Creek  
- Crawfor: Crawford  
- Edwards: Edwards  
- Gilbert: Gilbert  
- IDOTRR: Iowa DOT y Ferrocarril  
- MeadowV: Meadow Village  
- Mitchel: Mitchell  
- Names: North Ames  
- NoRidge: Northridge  
- NPkVill: Northpark Villa  
- NridgHt: Northridge Heights  
- NWAmes: Northwest Ames  
- OldTown: Old Town  
- SWISU: Sur y oeste de la Universidad Estatal de Iowa  
- Sawyer: Sawyer  
- SawyerW: Sawyer West  
- Somerst: Somerset  
- StoneBr: Stone Brook  
- Timber: Timberland  
- Veenker: Veenker


---

### `Condition1` – Proximidad a condiciones externas (primaria)
- Artery: Adyacente a calle arterial
- Feedr: Adyacente a calle secundaria
- Norm: Normal
- RRNn: Dentro de 200 pies del ferrocarril norte-sur
- RRAn: Adyacente a ferrocarril norte-sur
- PosN: Cerca de característica positiva (parque, zona verde, etc.)
- PosA: Adyacente a característica positiva
- RRNe: Dentro de 200 pies del ferrocarril este-oeste
- RRAe: Adyacente a ferrocarril este-oeste

---

### `Condition2` – Proximidad a condiciones externas (secundaria, si hay más de una)
(*Mismas categorías que Condition1*)

---

### `BldgType` – Tipo de vivienda
- 1Fam: Casa unifamiliar aislada
- 2FmCon: Conversión a dos familias (originalmente una sola)
- Duplx: Dúplex
- TwnhsE: Townhouse, unidad en esquina
- TwnhsI: Townhouse, unidad interior

---

### `HouseStyle` – Estilo de vivienda
- 1Story: Una planta
- 1.5Fin: Una planta y media, con segundo piso terminado
- 1.5Unf: Una planta y media, con segundo piso sin terminar
- 2Story: Dos plantas
- 2.5Fin: Dos plantas y media, segundo piso terminado
- 2.5Unf: Dos plantas y media, segundo piso sin terminar
- SFoyer: Split Foyer
- SLvl: Niveles divididos (Split Level)

---

### `OverallQual` – Calidad general de materiales y terminaciones (1 a 10)
- 10: Excelente
- 9: Muy excelente
- 8: Muy buena
- 7: Buena
- 6: Por encima del promedio
- 5: Promedio
- 4: Por debajo del promedio
- 3: Regular
- 2: Pobre
- 1: Muy pobre

---

### `OverallCond` – Condición general de la casa (1 a 10)
(*Mismas categorías que OverallQual*)

---

### `YearBuilt` – Año de construcción original

---

### `YearRemodAdd` – Año de remodelación o ampliación  
(*Igual a YearBuilt si no hubo cambios*)

---

### `RoofStyle` – Estilo de techo
- Flat: Plano
- Gable: A dos aguas
- Gambrel: Tipo granero
- Hip: A cuatro aguas
- Mansard: Mansarda
- Shed: A un agua

---

### `RoofMatl` – Material del techo
- ClyTile: Teja o cerámica
- CompShg: Teja asfáltica compuesta (standard)
- Membran: Membrana
- Metal: Metal
- Roll: Enrollado
- Tar&Grv: Asfalto y grava
- WdShake: Teja de madera
- WdShngl: Madera

---

### `Exterior1st` – Material de revestimiento exterior primario
- AsbShng: Tejas de asbesto
- AsphShn: Tejas asfálticas
- BrkComm: Ladrillo común
- BrkFace: Ladrillo visto
- CBlock: Bloques de cemento
- CemntBd: Cemento
- HdBoard: Madera dura
- ImStucc: Estuco imitación
- MetalSd: Revestimiento metálico
- Other: Otro
- Plywood: Contrachapado
- PreCast: Prefabricado
- Stone: Piedra
- Stucco: Estuco
- VinylSd: Revestimiento vinílico
- Wd Sdng: Revestimiento de madera
- WdShing: Tejas de madera

---

### `Exterior2nd` – Material de revestimiento exterior secundario
(*Mismas categorías que Exterior1st*)

---

### `MasVnrType` – Tipo de revestimiento de mampostería
- BrkCmn: Ladrillo común
- BrkFace: Ladrillo visto
- CBlock: Bloque de cemento
- None: Ninguno
- Stone: Piedra

---

### `MasVnrArea` – Área de mampostería en pies cuadrados

---

### `ExterQual` – Calidad del material exterior
- Ex: Excelente
- Gd: Buena
- TA: Típica / promedio
- Fa: Regular
- Po: Mala

---

### `ExterCond` – Condición del material exterior
(*Mismas categorías que ExterQual*)

---

### `Foundation` – Tipo de cimiento
- BrkTil: Ladrillo y cerámica
- CBlock: Bloque de cemento
- PConc: Hormigón armado
- Slab: Losa
- Stone: Piedra
- Wood: Madera

---

### `BsmtQual` – Altura del sótano
- Ex: Excelente (más de 100 pulgadas)
- Gd: Buena (90-99 pulgadas)
- TA: Típica (80-89 pulgadas)
- Fa: Regular (70-79 pulgadas)
- Po: Pobre (menos de 70 pulgadas)
- NA: Sin sótano

---

### `BsmtCond` – Condición general del sótano
- Ex: Excelente
- Gd: Buena
- TA: Típica (ligera humedad)
- Fa: Regular (algo de humedad, grietas o asentamiento)
- Po: Pobre (grietas severas, mucha humedad)
- NA: Sin sótano

---

### `BsmtExposure` – Exposición del sótano al exterior
- Gd: Buena exposición
- Av: Exposición promedio
- Mn: Exposición mínima
- No: Sin exposición
- NA: Sin sótano

---

### ℹ️ Notita sobre `BsmtFinType1` y `BsmtFinType2`  
Una casa puede tener más de una zona del sótano terminada, con diferentes usos o calidades.  
- `BsmtFinType1`: el tipo principal de área terminada (la más grande o importante)  
- `BsmtFinType2`: otro tipo secundario de área terminada, si existe una segunda sección distinta  

Ambas tienen su área correspondiente en pies cuadrados: `BsmtFinSF1` y `BsmtFinSF2`.

---

### `BsmtFinType1` – Clasificación del área terminada del sótano (tipo 1)
- GLQ: Buena calidad habitable
- ALQ: Calidad habitable promedio
- BLQ: Calidad habitable inferior
- Rec: Sala de recreación
- LwQ: Baja calidad
- Unf: Sin terminar
- NA: Sin sótano

---

### `BsmtFinSF1` – Pies cuadrados de área terminada (tipo 1)

---

### `BsmtFinType2` – Clasificación del área terminada del sótano (tipo 2)
(*Mismas categorías que BsmtFinType1*)

---

### `BsmtFinSF2` – Pies cuadrados de área terminada (tipo 2)

---

### `BsmtUnfSF` – Pies cuadrados del área del sótano sin terminar

---

### `TotalBsmtSF` – Superficie total del sótano (terminada + sin terminar)

---

### `Heating` – Tipo de calefacción
- Floor: Piso radiante
- GasA: Calefacción a gas con aire forzado
- GasW: Calefacción a gas por agua caliente o vapor
- Grav: Estufa de gravedad
- OthW: Calefacción por agua/vapor que no es a gas
- Wall: Estufa de pared

---

### `HeatingQC` – Calidad y condición de la calefacción
- Ex: Excelente
- Gd: Buena
- TA: Promedio / típica
- Fa: Regular
- Po: Mala

---

### `CentralAir` – Aire acondicionado central
- Y: Sí
- N: No

---

### `Electrical` – Sistema eléctrico
- SBrkr: Disyuntores estándar + cableado Romex
- FuseA: Caja de fusibles + cableado Romex (más de 60 AMP)
- FuseF: Caja de fusibles de 60 AMP + cableado Romex en su mayoría
- FuseP: Caja de fusibles de 60 AMP + cableado tipo perilla y tubo (obsoleto)
- Mix: Mezcla de sistemas eléctricos

---

### `1stFlrSF` – Pies cuadrados del primer piso

---

### `2ndFlrSF` – Pies cuadrados del segundo piso

---

### `LowQualFinSF` – Pies cuadrados terminados de baja calidad (en cualquier piso)

---

### `GrLivArea` – Área habitable sobre el nivel del suelo (pies²)

---

### `BsmtFullBath` – Cantidad de baños completos en el sótano

---

### `BsmtHalfBath` – Cantidad de medios baños en el sótano

---

### `FullBath` – Cantidad de baños completos por encima del nivel del suelo

---

### `HalfBath` – Cantidad de medios baños por encima del nivel del suelo

---

### `Bedroom` – Dormitorios por encima del nivel del suelo  
(*No incluye dormitorios en el sótano*)

---

### `Kitchen` – Cantidad de cocinas por encima del nivel del suelo

---

### `KitchenQual` – Calidad de la cocina
- Ex: Excelente
- Gd: Buena
- TA: Promedio / típica
- Fa: Regular
- Po: Pobre

---

### `TotRmsAbvGrd` – Total de ambientes por encima del nivel del suelo  
(*No incluye baños*)

---

### `Functional` – Funcionalidad general de la casa  
(*Se asume funcional típica a menos que se indique lo contrario*)
- Typ: Funcionalidad típica
- Min1: Deducciones menores 1
- Min2: Deducciones menores 2
- Mod: Deducciones moderadas
- Maj1: Deducciones importantes 1
- Maj2: Deducciones importantes 2
- Sev: Severamente dañado
- Sal: Solo apto para salvamento

---

### `Fireplaces` – Cantidad de chimeneas

---

### `FireplaceQu` – Calidad de la(s) chimenea(s)
- Ex: Excelente – Chimenea de mampostería excepcional
- Gd: Buena – Chimenea de mampostería en planta principal
- TA: Promedio – Chimenea prefabricada en living o mampostería en sótano
- Fa: Regular – Chimenea prefabricada en sótano
- Po: Pobre – Estufa tipo Ben Franklin
- NA: Sin chimenea

---

### `GarageType` – Ubicación del garaje
- 2Types: Más de un tipo de garaje
- Attchd: Adjunto a la casa
- Basment: Garaje en el sótano
- BuiltIn: Integrado (parte de la casa, generalmente con espacio arriba)
- CarPort: Cochera
- Detchd: Separado de la casa
- NA: Sin garaje

---

### `GarageYrBlt` – Año de construcción del garaje

---

### `GarageFinish` – Terminación interior del garaje
- Fin: Terminado
- RFn: Terminación rústica / parcial
- Unf: Sin terminar
- NA: Sin garaje

---

### `GarageCars` – Capacidad del garaje (en cantidad de autos)

---

### `GarageArea` – Tamaño del garaje en pies cuadrados

---

### `GarageQual` – Calidad del garaje
- Ex: Excelente
- Gd: Buena
- TA: Promedio / típica
- Fa: Regular
- Po: Pobre
- NA: Sin garaje

---

### `GarageCond` – Condición del garaje  
(*Mismos valores que GarageQual*)

---

### `PavedDrive` – Entrada de auto pavimentada
- Y: Pavimentada
- P: Parcialmente pavimentada
- N: Tierra / grava

---

### `WoodDeckSF` – Superficie del deck de madera (en pies²)

---

### `OpenPorchSF` – Superficie del porche abierto (en pies²)

---

### `EnclosedPorch` – Superficie del porche cerrado (en pies²)

---

### `3SsnPorch` – Superficie del porche de tres estaciones (en pies²)

---

### `ScreenPorch` – Superficie del porche con mosquitero (en pies²)

---

### `PoolArea` – Superficie de la pileta (en pies²)

---

### `PoolQC` – Calidad de la pileta
- Ex: Excelente
- Gd: Buena
- TA: Promedio / típica
- Fa: Regular
- NA: Sin pileta

---

### `Fence` – Calidad del cerco
- GdPrv: Buena privacidad
- MnPrv: Privacidad mínima
- GdWo: Buena madera
- MnWw: Madera/alambre mínimo
- NA: Sin cerco

---

### `MiscFeature` – Características misceláneas no cubiertas por otras columnas
- Elev: Ascensor
- Gar2: Segundo garaje (si no está descripto en sección de garaje)
- Othr: Otro
- Shed: Cobertizo (más de 100 pies²)
- TenC: Cancha de tenis
- NA: Ninguna

---

### `MiscVal` – Valor monetario de las características misceláneas ($)

---

### `MoSold` – Mes de la venta (MM)

---

### `YrSold` – Año de la venta (YYYY)

---

### `SaleType` – Tipo de venta
- WD: Escritura con garantía – Convencional
- CWD: Escritura con garantía – Pago en efectivo
- VWD: Escritura con garantía – Préstamo VA
- New: Casa recién construida y vendida
- COD: Escritura judicial / sucesión
- Con: Contrato con 15% de anticipo y términos normales
- ConLw: Contrato con bajo anticipo e interés bajo
- ConLI: Contrato con interés bajo
- ConLD: Contrato con bajo anticipo
- Oth: Otro

---

### `SaleCondition` – Condición de la venta
- Normal: Venta normal
- Abnorml: Venta anormal – trueque, ejecución hipotecaria, etc.
- AdjLand: Compra de terreno contiguo
- Alloca: Asignación – propiedades vinculadas con escrituras separadas (ej. condo + garaje)
- Family: Venta entre familiares
- Partial: Vivienda no terminada al momento de ser tasada (asociado a "New")

