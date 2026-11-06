# Colima: law history in git

Part of [lexifina/global-law](https://github.com/lexifina/global-law), one git history for every country's law: this is the law of Colima, Mexico, which global-law reads at `mexico/colima/acts/`.

The law of the State of Colima (Estado Libre y Soberano de Colima, Mexico) as a git history: one file per article, one commit per publication that changed it, dated the day it took effect, with the decree as the commit's author. `git blame` names the decree behind every paragraph; `git log` lists every change to an article; checking out a date gives the text in force that day.

It follows the shared design of [lexifina/global-law](https://github.com/lexifina/global-law), which places it at `mx-col/`. Mexico's federal law is in [lexifina/mexico-law](https://github.com/lexifina/mexico-law).

The text is in Spanish, exactly as the source prints it.

## What this repository holds

102 ordenamientos with 864 versions so far: the constitution first, then the codes and laws in force, added in parts. Regulations, decrees and repealed laws are not included yet.

| Folder | Ordenamiento | Versions | History |
| --- | --- | ---: | --- |
| `constitucion-politica/` | CONSTITUCION POLITICA DEL ESTADO LIBRE Y SOBERANO DE COLIMA | 158 | as first published, then each reform: 23 October 1917 to 1 September 2026 |
| `codigo-civil/` | CODIGO CIVIL PARA EL ESTADO DE COLIMA | 97 | as first published, then each reform: 28 September 1954 to 18 May 2025 |
| `codigo-de-procedimientos-civiles/` | CODIGO DE PROCEDIMIENTOS CIVILES PARA EL ESTADO DE COLIMA | 50 | as first published, then each reform: 28 September 1954 to 18 July 2021 |
| `codigo-electoral/` | CODIGO ELECTORAL DEL ESTADO DE COLIMA | 17 | as first published, then each reform: 31 August 2011 to 28 June 2026 |
| `codigo-fiscal/` | CODIGO FISCAL DEL ESTADO DE COLIMA | 8 | as first published, then each reform: 5 October 2003 to 13 July 2025 |
| `codigo-fiscal-municipal/` | CODIGO FISCAL MUNICIPAL DEL ESTADO DE COLIMA | 7 | as first published, then each reform: 26 January 2003 to 23 November 2016 |
| `codigo-penal/` | CODIGO PENAL PARA EL ESTADO DE COLIMA | 56 | as first published, then each reform: 31 December 2014 to 11 October 2026 |
| `ley-de-instituciones-de-asistencia-privada/` | LEY DE INSTITUCIONES DE ASISTENCIA PRIVADA PARA EL ESTADO DE COLIMA | 3 | as first published, then each reform: 17 June 2001 to 24 August 2003 |
| `ley-de-juicio-politico/` | LEY DE JUICIO POLITICO DEL ESTADO DE COLIMA | 1 | as first published: 2 August 2018 |
| `ley-de-justicia-administrativa/` | LEY DE JUSTICIA ADMINISTRATIVA DEL ESTADO DE COLIMA | 3 | as first published, then each reform: 17 June 2018 to 28 September 2025 |
| `ley-de-justicia-alternativa/` | LEY DE JUSTICIA ALTERNATIVA DEL ESTADO DE COLIMA | 5 | as first published, then each reform: 28 September 2003 to 23 November 2016 |
| `ley-de-la-comision-estatal-de-conciliacion-y-arbitraje-medic/` | LEY DE LA COMISION ESTATAL DE CONCILIACION Y ARBITRAJE MEDICO PARA EL ESTADO DE COLIMA | 2 | as first published, then each reform: 24 May 2008 to 19 July 2008 |
| `ley-de-la-juventud/` | LEY DE LA JUVENTUD DEL ESTADO DE COLIMA | 10 | as first published, then each reform: 13 July 2014 to 3 March 2024 |
| `ley-de-la-procuraduria-de-la-defensa-del-adulto-mayor/` | LEY DE LA PROCURADURIA DE LA DEFENSA DEL ADULTO MAYOR PARA EL ESTADO DE COLIMA | 5 | as first published, then each reform: 8 September 2013 to 25 August 2024 |
| `ley-de-las-entidades-paraestatales/` | LEY DE LAS ENTIDADES PARAESTATALES DEL ESTADO DE COLIMA | 2 | as first published, then each reform: 1 November 2021 to 6 March 2022 |
| `ley-de-las-personas-ilustres/` | LEY DE LAS PERSONAS ILUSTRES DEL ESTADO DE COLIMA | 4 | as first published, then each reform: 22 July 2007 to 20 March 2022 |
| `ley-de-los-derechos-de-ninas-ninos-y-adolescentes/` | LEY DE LOS DERECHOS DE NIÑAS, NIÑOS Y ADOLESCENTES DEL ESTADO DE COLIMA | 21 | as first published, then each reform: 19 April 2015 to 10 February 2026 |
| `ley-de-los-trabajadores-al-servicio-del-gobierno-ayuntamient/` | LEY DE LOS TRABAJADORES AL SERVICIO DEL GOBIERNO, AYUNTAMIENTOS Y ORGANISMOS DESCENTRALIZADOS DEL ESTADO DE COLIMA | 29 | as first published, then each reform: 5 January 1992 to 1 March 2026 |
| `ley-de-mejora-regulatoria/` | LEY DE MEJORA REGULATORIA PARA EL ESTADO DE COLIMA Y SUS MUNICIPIOS | 1 | as first published: 30 August 2018 |
| `ley-de-movilidad-sustentable/` | LEY DE MOVILIDAD SUSTENTABLE PARA EL ESTADO DE COLIMA | 14 | as first published, then each reform: 31 January 2017 to 2 August 2026 |
| `ley-de-operaciones-inmobiliarias/` | LEY DE OPERACIONES INMOBILIARIAS PARA EL ESTADO DE COLIMA | 2 | as first published, then each reform: 19 August 2012 to 23 November 2016 |
| `ley-de-participacion-ciudadana/` | LEY DE PARTICIPACION CIUDADANA DEL ESTADO DE COLIMA | 2 | as first published, then each reform: 28 March 2019 to 3 November 2019 |
| `ley-de-pensiones-de-los-servidores-publicos/` | LEY DE PENSIONES DE LOS SERVIDORES PUBLICOS DEL ESTADO DE COLIMA | 10 | as first published, then each reform: 1 January 2019 to 4 October 2026 |
| `ley-de-pesca-y-acuacultura-sustentables/` | LEY DE PESCA Y ACUACULTURA SUSTENTABLES PARA EL ESTADO DE COLIMA | 2 | as first published, then each reform: 2 November 2008 to 13 October 2013 |
| `ley-de-planeacion-democratica-para-el-desarrollo/` | LEY DE PLANEACION DEMOCRATICA PARA EL DESARROLLO DEL ESTADO DE COLIMA | 1 | as first published: 7 August 2016 |
| `ley-de-prestacion-de-servicios-para-la-atencion-cuidado-y-de/` | LEY DE PRESTACION DE SERVICIOS PARA LA ATENCION, CUIDADO Y DESARROLLO INTEGRAL INFANTIL DEL ESTADO DE COLIMA | 3 | as first published, then each reform: 4 August 2013 to 29 January 2023 |
| `ley-de-presupuesto-de-responsabilidad-hacendaria/` | LEY DE PRESUPUESTO DE RESPONSABILIDAD HACENDARIA DEL ESTADO DE COLIMA | 2 | as first published, then each reform: 29 January 2017 to 8 November 2020 |
| `ley-de-presupuesto-y-responsabilidad-hacendaria-para-los-mun/` | LEY DE PRESUPUESTO Y RESPONSABILIDAD HACENDARIA PARA LOS MUNICIPIOS DEL ESTADO DE COLIMA | 1 | as first published: 4 October 2020 |
| `ley-de-profesiones/` | LEY DE PROFESIONES DEL ESTADO DE COLIMA | 8 | as first published, then each reform: 8 October 2006 to 23 August 2026 |
| `ley-de-promocion-e-impulso-al-joven-emprendedor/` | LEY DE PROMOCION E IMPULSO AL JOVEN EMPRENDEDOR PARA EL ESTADO DE COLIMA | 2 | as first published, then each reform: 4 August 2013 to 2 April 2017 |
| `ley-de-proteccion-civil/` | LEY DE PROTECCION CIVIL DEL ESTADO DE COLIMA | 12 | as first published, then each reform: 30 October 2011 to 16 November 2025 |
| `ley-de-proteccion-de-datos-personales-en-posesion-de-sujetos/` | LEY DE PROTECCION DE DATOS PERSONALES EN POSESION DE SUJETOS OBLIGADOS PARA EL ESTADO DE COLIMA | 1 | as first published: 11 November 2025 |
| `ley-de-proteccion-y-conservacion-del-patrimonio-cultural/` | LEY DE PROTECCION Y CONSERVACION DEL PATRIMONIO CULTURAL DEL ESTADO DE COLIMA Y SUS MUNICIPIOS | 2 | as first published, then each reform: 1 January 2021 to 26 March 2023 |
| `ley-de-residuos-solidos/` | LEY DE RESIDUOS SOLIDOS DEL ESTADO DE COLIMA | 7 | as first published, then each reform: 9 April 2006 to 15 September 2019 |
| `ley-de-responsabilidad-patrimonial/` | LEY DE RESPONSABILIDAD PATRIMONIAL DEL ESTADO DE COLIMA | 1 | as first published: 21 August 2022 |
| `ley-de-revocacion-de-mandato/` | LEY DE REVOCACION DE MANDATO DEL ESTADO DE COLIMA | 1 | as first published: 13 August 2022 |
| `ley-de-salud/` | LEY DE SALUD DEL ESTADO DE COLIMA | 13 | as first published, then each reform: 30 September 2018 to 12 October 2025 |
| `ley-de-seguridad-integral-escolar/` | LEY DE SEGURIDAD INTEGRAL ESCOLAR PARA EL ESTADO DE COLIMA | 4 | as first published, then each reform: 1 June 2014 to 11 October 2026 |
| `ley-de-transparencia-y-acceso-a-la-informacion-publica/` | LEY DE TRANSPARENCIA Y ACCESO A LA INFORMACION PUBLICA DEL ESTADO DE COLIMA | 1 | as first published: 10 November 2025 |
| `ley-de-turismo/` | LEY DE TURISMO DEL ESTADO DE COLIMA | 12 | as first published, then each reform: 24 September 2006 to 14 December 2025 |
| `ley-de-valuacion/` | LEY DE VALUACION PARA EL ESTADO DE COLIMA | 1 | as first published: 14 August 2011 |
| `ley-de-vivienda/` | LEY DE VIVIENDA PARA EL ESTADO DE COLIMA | 4 | as first published, then each reform: 19 August 2012 to 21 October 2018 |
| `ley-de-voluntad-anticipada/` | LEY DE VOLUNTAD ANTICIPADA PARA EL ESTADO DE COLIMA | 1 | as first published: 4 August 2013 |
| `ley-del-centro-de-conciliacion-laboral/` | LEY DEL CENTRO DE CONCILIACION LABORAL DEL ESTADO DE COLIMA | 2 | as first published, then each reform: 14 February 2021 to 31 October 2021 |
| `ley-del-instituto-colimense-de-la-infraestructura-fisica-edu/` | LEY DEL INSTITUTO COLIMENSE DE LA INFRAESTRUCTURA FISICA EDUCATIVA | 4 | as first published, then each reform: 16 August 2009 to 14 August 2016 |
| `ley-del-instituto-colimense-de-las-mujeres/` | LEY DEL INSTITUTO COLIMENSE DE LAS MUJERES | 2 | as first published, then each reform: 15 June 2003 to 30 September 2018 |
| `ley-del-instituto-de-defensoria-publica/` | LEY DEL INSTITUTO DE DEFENSORIA PUBLICA DEL ESTADO DE COLIMA | 1 | as first published: 6 June 2021 |
| `ley-del-instituto-para-el-registro-del-territorio/` | LEY DEL INSTITUTO PARA EL REGISTRO DEL TERRITORIO DEL ESTADO DE COLIMA | 5 | as first published, then each reform: 26 August 2012 to 30 December 2025 |
| `ley-del-municipio-libre/` | LEY DEL MUNICIPIO LIBRE DEL ESTADO DE COLIMA | 46 | as first published, then each reform: 30 April 2001 to 25 August 2024 |
| `ley-del-notariado/` | LEY DEL NOTARIADO DEL ESTADO DE COLIMA | 11 | as first published, then each reform: 15 February 1964 to 12 May 2024 |
| `ley-del-patrimonio/` | LEY DEL PATRIMONIO DEL ESTADO DE COLIMA Y DE SUS MUNICIPIOS | 1 | as first published: 30 September 2018 |
| `ley-del-periodico-oficial/` | LEY DEL PERIODICO OFICIAL DEL ESTADO DE COLIMA | 1 | as first published: 2 October 2015 |
| `ley-del-procedimiento-administrativo/` | LEY DEL PROCEDIMIENTO ADMINISTRATIVO DEL ESTADO DE COLIMA Y SUS MUNICIPIOS | 2 | as first published, then each reform: 12 September 2021 to 28 September 2025 |
| `ley-del-sistema-anticorrupcion/` | LEY DEL SISTEMA ANTICORRUPCION DEL ESTADO DE COLIMA | 2 | as first published, then each reform: 16 July 2017 to 19 May 2019 |
| `ley-del-sistema-de-asistencia-social/` | LEY DEL SISTEMA DE ASISTENCIA SOCIAL PARA EL ESTADO DE COLIMA | 3 | as first published, then each reform: 2 September 2012 to 1 September 2019 |
| `ley-del-sistema-de-seguridad-publica/` | LEY DEL SISTEMA DE SEGURIDAD PUBLICA PARA EL ESTADO DE COLIMA | 4 | as first published, then each reform: 15 November 2020 to 17 April 2026 |
| `ley-estatal-de-obras-publicas/` | LEY ESTATAL DE OBRAS PUBLICAS | 8 | as first published, then each reform: 16 December 2002 to 5 October 2023 |
| `ley-estatal-del-sistema-de-medios-de-impugnacion-en-materia/` | LEY ESTATAL DEL SISTEMA DE MEDIOS DE IMPUGNACION EN MATERIA ELECTORAL | 8 | as first published, then each reform: 31 August 2005 to 7 July 2026 |
| `ley-estatal-para-el-fomento-a-la-lectura-y-al-libro/` | LEY ESTATAL PARA EL FOMENTO A LA LECTURA Y AL LIBRO | 3 | as first published, then each reform: 3 September 2006 to 25 March 2018 |
| `ley-inquilinaria-para-casos-de-desastres-en-el-estado-de-col/` | LEY INQUILINARIA PARA CASOS DE DESASTRES EN EL ESTADO DE COLIMA | 1 | as first published: 11 April 2004 |
| `ley-organica-de-la-comision-de-derechos-humanos/` | LEY ORGANICA DE LA COMISION DE DERECHOS HUMANOS DEL ESTADO DE COLIMA | 2 | as first published, then each reform: 5 September 2021 to 7 June 2026 |
| `ley-organica-de-la-fiscalia-general/` | LEY ORGANICA DE LA FISCALIA GENERAL DEL ESTADO DE COLIMA | 2 | as first published, then each reform: 13 August 2023 to 15 March 2026 |
| `ley-organica-de-la-tesoreria-general-del-estado/` | LEY ORGANICA DE LA TESORERIA GENERAL DEL ESTADO | 1 | as first published: 9 June 1985 |
| `ley-organica-de-la-universidad-de-colima/` | LEY ORGANICA DE LA UNIVERSIDAD DE COLIMA | 1 | as first published: 23 November 1980 |
| `ley-organica-de-la-universidad-tecnologica-de-manzanillo-col/` | LEY ORGANICA DE LA UNIVERSIDAD TECNOLOGICA DE MANZANILLO, COLIMA | 2 | as first published, then each reform: 14 December 2014 to 3 May 2026 |
| `ley-organica-del-poder-ejecutivo-y-de-la-administracion-publ/` | LEY ORGANICA DEL PODER EJECUTIVO Y DE LA ADMINISTRACION PUBLICA DEL ESTADO DE COLIMA | 7 | as first published, then each reform: 1 November 2021 to 17 April 2026 |
| `ley-organica-del-poder-judicial/` | LEY ORGANICA DEL PODER JUDICIAL DEL ESTADO DE COLIMA | 2 | as first published, then each reform: 30 September 2025 to 19 April 2026 |
| `ley-organica-del-poder-legislativo/` | LEY ORGANICA DEL PODER LEGISLATIVO DEL ESTADO DE COLIMA | 15 | as first published, then each reform: 12 October 2021 to 14 October 2025 |
| `ley-para-el-desarrollo-forestal-sustentable/` | LEY PARA EL DESARROLLO FORESTAL SUSTENTABLE DEL ESTADO DE COLIMA | 3 | as first published, then each reform: 3 September 2006 to 8 July 2018 |
| `ley-para-el-fomento-de-energias-renovables-y-eficiencia-ener/` | LEY PARA EL FOMENTO DE ENERGIAS RENOVABLES Y EFICIENCIA ENERGETICA DEL ESTADO DE COLIMA | 1 | as first published: 1 January 2015 |
| `ley-para-el-fomento-de-una-cultura-de-donacion-procuracion-y/` | LEY PARA EL FOMENTO DE UNA CULTURA DE DONACION, PROCURACION Y TRASPLANTE DE ORGANOS, TEJIDOS Y CELULAS PARA EL ESTADO DE COLIMA | 3 | as first published, then each reform: 27 January 2013 to 1 January 2021 |
| `ley-para-el-fomento-proteccion-y-desarrollo-agricola-en-el-e/` | LEY PARA EL FOMENTO, PROTECCION Y DESARROLLO AGRICOLA EN EL ESTADO DE COLIMA | 4 | as first published, then each reform: 24 September 2006 to 8 May 2022 |
| `ley-para-el-impulso-de-la-sociedad-de-la-informacion-y-el-co/` | LEY PARA EL IMPULSO DE LA SOCIEDAD DE LA INFORMACION Y EL CONOCIMIENTO EN EL ESTADO DE COLIMA | 1 | as first published: 2 September 2012 |
| `ley-para-fomentar-la-donacion-altruista-en-materia-alimentar/` | LEY PARA FOMENTAR LA DONACION ALTRUISTA EN MATERIA ALIMENTARIA PARA EL ESTADO DE COLIMA | 2 | as first published, then each reform: 24 August 2003 to 21 October 2018 |
| `ley-para-la-administracion-de-bienes-asegurados-decomisados/` | LEY PARA LA ADMINISTRACION DE BIENES ASEGURADOS, DECOMISADOS Y ABANDONADOS DEL ESTADO DE COLIMA | 2 | as first published, then each reform: 31 December 2014 to 23 November 2016 |
| `ley-para-la-atencion-de-personas-con-trastornos-del-espectro/` | LEY PARA LA ATENCION DE PERSONAS CON TRASTORNOS DEL ESPECTRO AUTISTA PARA EL ESTADO DE COLIMA | 2 | as first published, then each reform: 4 June 2017 to 12 January 2020 |
| `ley-para-la-deteccion-y-tratamiento-oportuno-e-integral-del/` | LEY PARA LA DETECCION Y TRATAMIENTO OPORTUNO E INTEGRAL DEL CANCER EN LA INFANCIA Y LA ADOLESCENCIA DEL ESTADO DE COLIMA | 1 | as first published: 26 June 2022 |
| `ley-para-la-igualdad-entre-mujeres-y-hombres/` | LEY PARA LA IGUALDAD ENTRE MUJERES Y HOMBRES DEL ESTADO DE COLIMA | 8 | as first published, then each reform: 24 May 2009 to 27 November 2022 |
| `ley-para-la-mitigacion-y-adaptacion-ante-los-efectos-del-cam/` | LEY PARA LA MITIGACION Y ADAPTACION ANTE LOS EFECTOS DEL CAMBIO CLIMATICO PARA EL ESTADO DE COLIMA | 5 | as first published, then each reform: 1 January 2017 to 24 May 2026 |
| `ley-para-la-prestacion-del-servicio-de-agua-potable-y-drenaj/` | LEY PARA LA PRESTACION DEL SERVICIO DE AGUA POTABLE Y DRENAJE PARA EL MUNICIPIO DE MANZANILLO, COLIMA | 2 | as first published, then each reform: 10 August 1980 to 1 January 1984 |
| `ley-para-la-prevencion-social-de-la-violencia-y-la-delincuen/` | LEY PARA LA PREVENCION SOCIAL DE LA VIOLENCIA Y LA DELINCUENCIA DEL ESTADO DE COLIMA | 1 | as first published: 15 July 2012 |
| `ley-para-la-prevencion-y-atencion-a-la-violencia-familiar-an/` | LEY PARA LA PREVENCION Y ATENCION A LA VIOLENCIA FAMILIAR -- ANTES -- LEY PARA LA PREVENCION Y ATENCION DE LA VIOLENCIA FAMILIAR -- ANTES -- LEY PARA LA PREVENCION Y ATENCION A LA VIOLENCIA INTRAFAMILIAR | 11 | as first published, then each reform: 15 February 1998 to 17 September 2023 |
| `ley-para-la-prevencion-tratamiento-y-control-de-las-adiccion/` | LEY PARA LA PREVENCION, TRATAMIENTO Y CONTROL DE LAS ADICCIONES EN EL ESTADO DE COLIMA | 10 | as first published, then each reform: 19 February 2006 to 11 October 2026 |
| `ley-para-la-promocion-de-la-cultura-de-la-legalidad/` | LEY PARA LA PROMOCION DE LA CULTURA DE LA LEGALIDAD DEL ESTADO DE COLIMA | 1 | as first published: 14 August 2011 |
| `ley-para-la-promocion-y-desarrollo-agroecologico-en-el-estad/` | LEY PARA LA PROMOCION Y DESARROLLO AGROECOLOGICO EN EL ESTADO DE COLIMA | 1 | as first published: 25 June 2023 |
| `ley-para-la-proteccion-a-los-animales/` | LEY PARA LA PROTECCION A LOS ANIMALES DEL ESTADO DE COLIMA | 6 | as first published, then each reform: 1 September 2011 to 25 August 2024 |
| `ley-para-la-proteccion-a-testigos-y-sujetos-intervinientes-e/` | LEY PARA LA PROTECCION A TESTIGOS Y SUJETOS INTERVINIENTES EN EL PROCEDIMIENTO PENAL DEL ESTADO DE COLIMA | 6 | as first published, then each reform: 28 October 2014 to 1 March 2016 |
| `ley-para-la-proteccion-de-los-adultos-mayores/` | LEY PARA LA PROTECCION DE LOS ADULTOS MAYORES DEL ESTADO DE COLIMA -- ANTES LEY PARA LA PROTECCION DE LOS ADULTOS EN PLENITUD DEL ESTADO DE COLIMA -- | 22 | as first published, then each reform: 12 September 2004 to 21 June 2026 |
| `ley-para-la-proteccion-de-victimas-en-el-estado-de-colima/` | LEY PARA LA PROTECCION DE VICTIMAS EN EL ESTADO DE COLIMA | 4 | as first published, then each reform: 31 December 2014 to 8 March 2020 |
| `ley-para-la-proteccion-integral-del-ejercicio-periodistico/` | LEY PARA LA PROTECCION INTEGRAL DEL EJERCICIO PERIODISTICO PARA EL ESTADO DE COLIMA | 1 | as first published: 29 July 2012 |
| `ley-para-la-proteccion-y-bienestar-de-los-animales-de-compan/` | LEY PARA LA PROTECCION Y BIENESTAR DE LOS ANIMALES DE COMPAÑIA DEL ESTADO DE COLIMA | 1 | as first published: 9 October 2022 |
| `ley-para-la-proteccion-apoyo-y-promocion-de-la-lactancia-mat/` | LEY PARA LA PROTECCION, APOYO Y PROMOCION DE LA LACTANCIA MATERNA DEL ESTADO DE COLIMA | 1 | as first published: 11 September 2022 |
| `ley-para-prevenir-y-erradicar-la-trata-de-personas-en-el-est/` | LEY PARA PREVENIR Y ERRADICAR LA TRATA DE PERSONAS EN EL ESTADO DE COLIMA | 3 | as first published, then each reform: 30 October 2011 to 8 July 2018 |
| `ley-para-prevenir-y-sancionar-tortura/` | LEY PARA PREVENIR Y SANCIONAR TORTURA | 4 | as first published, then each reform: 14 May 1995 to 21 November 2014 |
| `ley-para-regular-la-apertura-instalacion-y-funcionamiento-de/` | LEY PARA REGULAR LA APERTURA, INSTALACION Y FUNCIONAMIENTO DE LAS CASAS DE EMPEÑO EN EL ESTADO DE COLIMA | 1 | as first published: 30 April 2018 |
| `ley-para-regular-la-convivencia-civil-en-el-estado-de-colima/` | LEY PARA REGULAR LA CONVIVENCIA CIVIL EN EL ESTADO DE COLIMA Y SUS MUNICIPIOS | 4 | as first published, then each reform: 1 January 2019 to 10 July 2022 |
| `ley-para-regular-la-participacion-del-congreso-en-asuntos-mu/` | LEY PARA REGULAR LA PARTICIPACION DEL CONGRESO EN ASUNTOS MUNICIPALES | 3 | as first published, then each reform: 21 April 2002 to 23 November 2016 |
| `ley-para-regular-la-venta-y-consumo-de-bebidas-alcoholicas/` | LEY PARA REGULAR LA VENTA Y CONSUMO DE BEBIDAS ALCOHOLICAS | 17 | as first published, then each reform: 12 January 2003 to 18 February 2024 |
| `ley-para-resolver-los-conflictos-de-limites-intermunicipales/` | LEY PARA RESOLVER LOS CONFLICTOS DE LIMITES INTERMUNICIPALES EN EL ESTADO DE COLIMA | 3 | as first published, then each reform: 22 November 2002 to 23 November 2016 |
| `ley-que-crea-el-archivo-historico-del-municipio-de-colima/` | LEY QUE CREA EL ARCHIVO HISTORICO DEL MUNICIPIO DE COLIMA | 1 | as first published: 17 January 1993 |
| `ley-que-crea-el-consejo-de-armonizacion-contable/` | LEY QUE CREA EL CONSEJO DE ARMONIZACION CONTABLE DEL ESTADO DE COLIMA | 1 | as first published: 21 August 2011 |
| `ley-que-crea-el-organismo-publico-descentralizado-denominado/` | LEY QUE CREA EL ORGANISMO PUBLICO DESCENTRALIZADO DENOMINADO COORDINACION DE LOS SERVICIOS EDUCATIVOS DEL ESTADO DE COLIMA | 6 | as first published, then each reform: 21 June 1992 to 19 April 2026 |

## Source

The legislation compilation of Mexico's Supreme Court, the Suprema Corte de Justicia de la Nación (SCJN), at <https://legislacion.scjn.gob.mx/>. For each ordenamiento it lists every publication in the state's official gazette (Periódico Oficial) that changed it (decree, erratum, ruling), with the date of publication, the decree's extract and the whole consolidated text as it stood after that publication. Each version here is one of those texts.

## Dates

- Each commit is dated at **noon, America/Mexico_City, on the day the publication took effect**: the day its own transitorios name, as SCJN's extract quotes them (most often the day after publication). When a decree names none, 3 days after publication.
- A consolidated text holds every change published before it, so it is never dated before the latest of their in-force days. Different in-force days for parts of one decree are not split.
- An act's first commit is its first publication when SCJN holds the original text; otherwise it is the oldest version SCJN holds.
- Versions that take effect after the retrieval day are on the `futuro` branch, never merged into `main`.

## Files

`<act>/art-005.md` is Artículo 5, `art-005-bis.md` Artículo 5 Bis; `encabezado.md` holds the title, the promulgation and preamble; `transitorios-original.md` the original transitory articles and `transitorios-<date>.md` those of the reform published that day. Section headings and editor's notes such as "(REFORMADO, P.O. ...)" stay in the file of the article they stand before. One paragraph per line.

## How it is checked

- Every version of every act is read back from git on the day it took effect and on the day before (`tools/check_repo.py`); both must match `corpus.json`.
- The letters and digits of every version equal those of SCJN's own text of that version (read independently of the parser), and every unit's text appears in it in order.
- Health checks: no merge commits, commit dates never go backwards, nothing dated in the future, and every commit's trailers parse.

## What "author" means

The author of a commit is the publication that changed the text (a decree, an erratum or a ruling), named by its category, gazette date and issue, with an e-mail address that cannot exist (`<key>@legislacion.scjn.gob.mx.invalid`). The committer is always Lexifina.

## Limits

This is not an official publication. The binding text is the one published in the state's official gazette (Periódico Oficial). The history starts with the oldest text SCJN holds for each ordenamiento, which for many is later than its enactment. Only the ordenamientos listed above are included.
