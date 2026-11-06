# Castilla-La Mancha: law history in git

Part of [lexifina/global-law](https://github.com/lexifina/global-law), one git history for every country's law: this is the law of Castilla-La Mancha, Spain, which global-law reads at `spain/castile-la-mancha/acts/`.

The law of the autonomous community of Castilla-La Mancha (Comunidad Autónoma de Castilla-La Mancha, Spain) as a git history: one file per article, one commit per norm that changed it, dated the day the change took effect, with the amending norm as the commit's author. `git blame` names the norm behind every paragraph; `git log` lists every change to an article; checking out a date gives the text in force that day.

It follows the shared design of [lexifina/global-law](https://github.com/lexifina/global-law), which places it at `es-cm/`. Spain's national law is in [lexifina/spain-law](https://github.com/lexifina/spain-law).

The text is in Spanish, exactly as the BOE's consolidated text prints it. Texts in co-official languages are not included.

Basado en datos de la Agencia Estatal Boletín Oficial del Estado (<https://www.boe.es>). Every text here is a consolidated text for information only (texto consolidado de carácter meramente informativo), not an official publication.

## What this repository holds

161 norms with 566 versions so far: the Estatuto de Autonomía first, then the laws, decree-laws and legislative decrees in force that the BOE consolidates, oldest first, added in parts of about 50. 15 of them are repealed norms the BOE consolidates: their whole history is kept, and their last commit removes the text on the day the repeal took effect, credited to the repealing norm. Regulations are not included (the BOE consolidates no autonomic decrees or orders).

| Folder | Norm | Versions | History | BOE last updated |
| --- | --- | ---: | --- | --- |
| `estatuto-de-autonomia/` | Ley Orgánica 9/1982, de 10 de agosto, de Estatuto de Autonomía de Castilla-La Mancha. | 7 | as first published, then each change: 17 August 1982 to 23 May 2014 | 2026-10-29 |
| `ley-1983-001/` | Ley 1/1983, de 30 de junio, sobre al Escudo de la Región de Castilla-La Mancha. | 1 | as first published: 13 July 1983 | 2025-12-16 |
| `ley-1983-003/` | Ley 3/1983, de 7 de diciembre, de la Sede de las Instituciones Regionales de la Junta de Comunidades de Castilla-La Mancha. | 1 | as first published: 9 January 1984 | 2025-12-16 |
| `ley-1984-003/` | Ley 3/1984, de 25 de abril, sobre Régimen Jurídico del Gobierno y de la Administración de la Junta de Comunidades de Castilla-La Mancha. | 3 | as first published, then each change: 8 May 1984 to 20 September 1997 | 2026-04-17 |
| `ley-1984-005/` | Ley 5/1984, de 19 de diciembre, de las Comunidades Originarias de Castilla-La Mancha. | 1 | as first published: 20 January 1985 | 2025-12-16 |
| `ley-1985-002/` | Ley 2/1985, de 8 de mayo, sobre iniciativa legislativa popular y de los Ayuntamientos de Castilla-La Mancha. | 1 | as first published: 22 May 1985 | 2025-12-16 |
| `ley-1985-004/` | Ley 4/1985, de 26 de junio, sobre designación de Senadores representantes de Castilla-La Mancha. | 5 | as first published, then each change: 12 August 1985 to 9 August 2023 | 2025-12-16 |
| `ley-1986-005/` | Ley 5/1986, de 23 de diciembre, electoral de Castilla-La Mancha. | 14 | as first published, then each change: 6 January 1987 to 22 March 2024 | 2025-12-17 |
| `ley-1987-001/` | Ley 1/1987, de 7 de abril, sobre el Consejo Asesor de Radio y Televisión Española en Castilla-La Mancha. | 2 | oldest version available, then each change: 18 May 1987 to 4 June 1998 | 2025-12-17 |
| `ley-1988-003/` | Ley 3/1988, de 13 de diciembre, de Ordenación de la Función Pública de Castilla-La Mancha. | 13 | as first published, then each change: 28 December 1988 to 22 September 2011 | 2025-12-17 |
| `ley-1989-003/` | Ley 3/1989, de 18 de mayo, de Capitalidad de los Partidos Judiciales de Castilla-La Mancha. | 1 | as first published: 31 May 1989 | 2025-12-17 |
| `ley-1990-008/` | Ley 8/1990, de 28 de diciembre, de Aguas Minerales y Termales de Castilla-La Mancha. | 1 | as first published: 22 January 1991 | 2025-12-17 |
| `ley-1990-009/` | Ley 9/1990, de 28 de diciembre, de Carreteras y Caminos de Castilla-La Mancha. | 4 | as first published, then each change: 22 January 1991 to 10 June 2010 | 2026-03-30 |
| `ley-1991-002/` | Ley 2/1991, de 14 de marzo, de Coordinación de Diputaciones. | 1 | as first published: 1 January 1992 | 2025-12-17 |
| `ley-1991-003/` | Ley 3/1991, de 4 de marzo, de Entidades Locales de Castilla-La Mancha. | 9 | as first published, then each change: 16 April 1991 to 2 December 2012 | 2026-09-14 |
| `ley-1992-001/` | Ley 1/1992, de 7 de mayo, de Pesca Fluvial. | 7 | as first published, then each change: 24 September 1992 to 15 April 2018 | 2025-12-17 |
| `ley-1994-001/` | Ley 1/1994, de 24 de mayo, de accesibilidad y eliminación de barreras en Castilla-La Mancha. | 3 | as first published, then each change: 14 July 1994 to 27 January 2019 | 2025-12-18 |
| `ley-1995-004/` | Ley 4/1995, de 16 de marzo, de Voluntariado en Castilla-La Mancha. | 2 | as first published, then each change: 22 April 1995 to 17 November 2014 | 2025-12-18 |
| `ley-1997-002/` | Ley 2/1997, de 30 de mayo, de Actividades Feriales de Castilla-La Mancha. | 2 | as first published, then each change: 17 July 1997 to 24 December 2009 | 2025-12-18 |
| `ley-1997-004/` | Ley 4/1997, de 10 de julio, de Cajas de Ahorro de Castilla-La Mancha. | 5 | as first published, then each change: 19 July 1997 to 22 May 2010 | 2025-12-18 |
| `ley-1997-011/` | Ley 11/1997, de 17 de diciembre, de creación de la empresa pública «Gestión de Infraestructuras de Castilla-La Mancha». | 5 | as first published, then each change: 1 January 1998 to 31 May 2016 | 2025-12-18 |
| `ley-1999-006/` | Ley 6/1999, de 15 de abril, de Protección de la Calidad del Suministro Eléctrico. | 5 | as first published, then each change: 20 May 1999 to 24 September 2023 | 2025-12-18 |
| `ley-1999-008/` | Ley 8/1999, de 26 de mayo, de Ordenación del Turismo de Castilla-La Mancha. | 4 | as first published, then each change: 2 July 1999 to 28 December 2019 | 2025-12-18 |
| `ley-1999-009/` | Ley 9/1999, de 26 de mayo, de Conservación de la Naturaleza. | 6 | as first published, then each change: 2 July 1999 to 15 April 2018 | 2026-03-30 |
| `ley-1999-010/` | Ley 10/1999, de 26 de mayo, de Creación de Colegios Profesionales de Castilla-La Mancha. | 3 | as first published, then each change: 2 July 1999 to 6 August 2020 | 2025-12-18 |
| `ley-2000-003/` | Ley 3/2000, de 26 de mayo, de Creación del Ente Público de Radio-Televisión de Castilla-La Mancha. | 6 | as first published, then each change: 2 June 2000 to 1 June 2021 | 2025-12-18 |
| `ley-2000-005/` | Ley 5/2000, de 19 de octubre, de creación del Colegio Oficial de Protésicos Dentales de Castilla-La Mancha. | 1 | as first published: 3 December 2000 | 2025-12-18 |
| `ley-2000-006/` | Ley 6/2000, de 19 de octubre, de creación del Colegio Oficial de Podólogos de Castilla-La Mancha. | 1 | as first published: 3 December 2000 | 2025-12-18 |
| `ley-2000-007/` | Ley 7/2000, de 23 de noviembre, de Ordenación del Aprovechamiento de Pastos, Hierbas y Rastrojeras. | 2 | as first published, then each change: 25 December 2000 to 1 August 2020 | 2025-12-18 |
| `ley-2000-008/` | Ley 8/2000, de 30 de noviembre, de Ordenación Sanitaria de Castilla-La Mancha. | 5 | as first published, then each change: 19 January 2001 to 1 June 2021 | 2026-04-16 |
| `ley-2001-003/` | Ley 3/2001, de 26 de abril, de Creación del Colegio Profesional de Fisioterapeutas de Castilla-La Mancha. | 1 | as first published: 16 May 2001 | 2025-12-18 |
| `ley-2001-004/` | Ley 4/2001, de 10 de mayo, de Parques Arqueológicos de Castilla-La Mancha. | 2 | as first published, then each change: 7 June 2001 to 1 July 2021 | 2025-12-18 |
| `ley-2001-008/` | Ley 8/2001, de 28 de junio, para la Ordenación de las Instalaciones de Radiocomunicación en Castilla-La Mancha. | 4 | as first published, then each change: 30 July 2001 to 11 February 2012 | 2025-12-18 |
| `ley-2001-009/` | Ley 9/2001, de 27 de septiembre, de Creación del Colegio Profesional de Logopedas de Castilla-La Mancha. | 1 | as first published: 10 October 2001 | 2025-12-18 |
| `ley-2001-012/` | Ley 12/2001, de 29 de noviembre, de Acceso de las Personas con Discapacidad a la Función Pública de la Administración de la Junta de Comunidades de Castilla-La Mancha. | 2 | as first published, then each change: 3 January 2002 to 22 September 2011 | 2025-12-18 |
| `ley-2002-002/` | Ley 2/2002, de 7 de febrero, por la que se establecen y regulan las diversas modalidades de viviendas de protección pública en Castilla-La Mancha. | 3 | as first published, then each change: 23 February 2002 to 1 February 2023 | 2026-10-29 |
| `ley-2002-008/` | Ley 8/2002, de 23 de mayo, de Coordinación de Policías Locales de Castilla-La Mancha. | 3 | as first published, then each change: 2 July 2002 to 23 March 2023 | 2025-12-18 |
| `ley-2002-009/` | Ley 9/2002, de 6 de junio, de Creación del Consejo de Relaciones Laborales de Castilla-La Mancha. | 4 | as first published, then each change: 24 July 2002 to 31 May 2016 | 2025-12-18 |
| `ley-2002-010/` | Ley 10/2002, de 21 de junio, de Estadística de Castilla-La Mancha. | 3 | as first published, then each change: 18 July 2002 to 21 December 2010 | 2026-03-30 |
| `ley-2002-014/` | Ley 14/2002, de 11 de julio, de Ordenación y Fomento de la Artesanía. | 1 | as first published: 13 August 2002 | 2026-03-30 |
| `ley-2002-015/` | Ley 15/2002, de 11 de julio, sobre Drogodependencias y otros Trastornos Adictivos. | 1 | as first published: 24 August 2002 | 2025-12-18 |
| `ley-2002-019/` | Ley 19/2002, de 24 de octubre, de Archivos Públicos de Castilla-La Mancha. | 3 | as first published, then each change: 16 November 2002 to 16 April 2025 | 2025-12-18 |
| `decreto-legislativo-2002-001/` | Decreto Legislativo 1/2002, de 19 de noviembre de 2002, por el que se aprueba el Texto Refundido de la Ley de Hacienda de Castilla-La Mancha. | 30 | oldest version available, then each change: 30 November 2002 to 1 January 2026 | 2026-03-26 |
| `ley-2002-022/` | Ley 22/2002, de 21 de noviembre, de Creación del Instituto de la Mujer de Castilla-La Mancha. | 5 | as first published, then each change: 24 December 2002 to 28 December 2019 | 2025-12-18 |
| `ley-2003-003/` | Ley 3/2003, de 13 de febrero, de Cooperación Internacional para el Desarrollo. | 3 | as first published, then each change: 20 March 2003 to 1 March 2012 | 2025-12-18 |
| `ley-2003-009/` | Ley 9/2003, de 20 de marzo, de Vías Pecuarias de Castilla-La Mancha. | 8 | as first published, then each change: 28 April 2003 to 6 August 2025 | 2025-12-18 |
| `ley-2003-011/` | Ley 11/2003, de 25 de septiembre, del Gobierno y del Consejo Consultivo de Castilla-La Mancha. | 3 | as first published, then each change: 7 October 2003 to 4 July 2020 | 2025-12-18 |
| `ley-2004-004/` | Ley 4/2004, de 18 de mayo, de la Explotación Agraria y del Desarrollo Rural en Castilla-La Mancha. | 2 | as first published, then each change: 25 June 2004 to 7 May 2023 | 2025-12-18 |
| `ley-2004-006/` | Ley 6/2004, de 21 de diciembre, para la aplicación al municipio de Albacete del régimen de organización de los municipios de gran población. | 1 | as first published: 31 December 2004 | 2025-12-18 |
| `ley-2004-007/` | Ley 7/2004, de 21 de diciembre, para la aplicación al municipio de Ciudad Real del régimen de organización de los municipios de gran población. | 1 | as first published: 31 December 2004 | 2025-12-18 |
| `ley-2004-008/` | Ley 8/2004, de 21 de diciembre, para la aplicación al municipio de Guadalajara del régimen de organización de los municipios de gran población. | 1 | as first published: 31 December 2004 | 2025-12-18 |
| `ley-2004-009/` | Ley 9/2004, de 21 de diciembre, para la aplicación al municipio de Talavera de la Reina del régimen de organización de los municipios de gran población. | 1 | as first published: 31 December 2004 | 2025-12-18 |
| `ley-2004-010/` | Ley 10/2004, de 21 de diciembre, para la aplicación al municipio de Cuenca del régimen de organización de los municipios de gran población. | 1 | as first published: 31 December 2004 | 2025-12-18 |
| `ley-2004-011/` | Ley 11/2004, de 21 de diciembre, para la aplicación al municipio de Toledo del régimen de organización de los municipios de gran población. | 1 | as first published: 31 December 2004 | 2025-12-18 |
| `ley-2005-001/` | Ley 1/2005, de 7 de abril, de los Consejos de la Juventud de Castilla-La Mancha. | 2 | as first published, then each change: 8 May 2005 to 1 January 2014 | 2025-12-18 |
| `ley-2005-005/` | Ley 5/2005, de 27 de junio, de Ordenación del Servicio Farmacéutico de Castilla-La Mancha. | 3 | as first published, then each change: 1 August 2005 to 1 June 2021 | 2026-04-16 |
| `ley-2005-006/` | Ley 6/2005, de 7 de julio, sobre la Declaración de Voluntades Anticipadas en materia de la propia salud. | 1 | as first published: 15 August 2005 | 2025-12-18 |
| `ley-2005-009/` | Ley 9/2005, de 6 de octubre, de creación del Colegio Profesional de Higienistas Dentales de Castilla-La Mancha. | 1 | as first published: 10 November 2005 | 2025-12-18 |
| `ley-2005-014/` | Ley 14/2005, de 29 de diciembre, de ordenación del transporte de personas por carretera en Castilla-La Mancha. | 5 | oldest version available, then each change: 1 January 2006 to 1 February 2023 | 2026-03-30 |
| `ley-2005-016/` | Ley 16/2005, de 29 de diciembre, del Impuesto sobre determinadas actividades que inciden en el medio ambiente y del tipo autonómico del Impuesto sobre las Ventas Minoristas de determinados Hidrocarburos. | 5 | as first published, then each change: 1 January 2006 to 10 April 2013 | 2025-12-18 |
| `ley-2007-001/` | Ley 1/2007, de 15 de febrero, de fomento de las Energías Renovables e Incentivación del Ahorro y Eficiencia Energética en Castilla-La Mancha. | 2 | as first published, then each change: 14 March 2007 to 1 June 2021 | 2025-12-19 |
| `ley-2007-003/` | Ley 3/2007, de 8 de marzo, de Participación Social en la Educación en la Comunidad Autónoma de Castilla-La Mancha. | 4 | as first published, then each change: 9 April 2007 to 16 April 2025 | 2025-12-19 |
| `ley-2007-007/` | Ley 7/2007, de 15 de marzo, de Calidad Agroalimentaria de Castilla-La Mancha. | 2 | as first published, then each change: 5 May 2007 to 24 December 2009 | 2025-12-19 |
| `ley-2007-010/` | Ley 10/2007, de 29 de marzo, de Medios Audiovisuales de Castilla-La Mancha. | 4 | as first published, then each change: 20 April 2007 to 22 March 2024 | 2025-12-19 |
| `ley-2007-011/` | Ley 11/2007, de 29 de marzo, de creación del Organismo Autónomo Espacios Naturales de Castilla-La Mancha. | 1 | as first published: 9 May 2007 | 2025-12-19 |
| `ley-2008-001/` | Ley 1/2008, de 17 de abril, de creación de la Empresa Pública de Gestión de Suelo de Castilla-La Mancha. | 2 | as first published, then each change: 29 April 2008 to 22 September 2011 | 2025-12-19 |
| `ley-2008-003/` | Ley 3/2008, de 12 de junio, de Montes y Gestión Forestal Sostenible de Castilla-La Mancha. | 6 | as first published, then each change: 13 July 2008 to 6 August 2025 | 2025-12-19 |
| `ley-2008-004/` | Ley 4/2008, de 12 de junio, de creación del Colegio Oficial de Dietistas-Nutricionistas de Castilla-La Mancha. | 1 | as first published: 13 July 2008 | 2025-12-19 |
| `ley-2008-007/` | Ley 7/2008, de 13 de noviembre, de Regulación de Tasas en materia de Industria, Energía y Minas de Castilla-La Mancha. | 6 | as first published, then each change: 27 December 2008 to 28 December 2019 | 2025-12-19 |
| `ley-2009-003/` | Ley 3/2009, de 24 de septiembre, de Creación del Colegio Oficial de Profesionales en Ingeniería Química de Castilla-La Mancha. | 1 | as first published: 3 October 2009 | 2025-12-19 |
| `ley-2010-001/` | Ley 1/2010, de 11 de marzo, de regulación de la tasa para la concesión de la etiqueta ecológica en Castilla-La Mancha. | 2 | as first published, then each change: 7 April 2010 to 2 December 2012 | 2025-12-19 |
| `ley-2010-002/` | Ley 2/2010, de 13 de mayo, de comercio de Castilla-La Mancha. | 3 | as first published, then each change: 22 May 2010 to 23 December 2014 | 2025-12-19 |
| `ley-2010-005/` | Ley 5/2010, de 24 de junio, sobre derechos y deberes en materia de salud de Castilla-La Mancha. | 2 | as first published, then each change: 9 January 2011 to 28 December 2019 | 2025-12-19 |
| `ley-2010-006/` | Ley 6/2010, de 24 de junio, de creación de las categorías de personal estatutario de inspección y evaluación de servicios sanitarios y prestaciones. | 3 | as first published, then each change: 10 July 2010 to 28 December 2019 | 2025-12-19 |
| `ley-2010-007/` | Ley 7/2010, de 20 de julio, de Educación de Castilla-La Mancha. | 5 | as first published, then each change: 17 August 2010 to 16 April 2025 | 2025-12-19 |
| `ley-2010-010/` | Ley 10/2010, de 21 de octubre, de promoción de la seguridad y salud en el trabajo en Castilla-La Mancha. | 2 | as first published, then each change: 22 November 2010 to 16 April 2025 | 2025-12-19 |
| `ley-2010-011/` | Ley 11/2010, de 4 de noviembre, de Cooperativas de Castilla-La Mancha. | 2 | as first published, then each change: 16 January 2011 to 31 December 2017 | 2025-12-19 |
| `ley-2010-012/` | Ley 12/2010, de 18 de noviembre, de igualdad entre mujeres y hombres de Castilla-La Mancha. | 7 | as first published, then each change: 26 November 2010 to 1 July 2021 | 2025-12-19 |
| `ley-2010-014/` | Ley 14/2010, de 16 de diciembre, de servicios sociales de Castilla-La Mancha. | 11 | as first published, then each change: 30 June 2011 to 6 August 2025 | 2026-03-30 |
| `ley-2011-002/` | Ley 2/2011, de 10 de febrero, de creación del Colegio Oficial de Terapeutas Ocupacionales de Castilla-La Mancha. | 1 | as first published: 13 March 2011 | 2025-12-19 |
| `ley-2011-003/` | Ley 3/2011, de 24 de febrero, de la Lectura y de las Bibliotecas de Castilla-La Mancha. | 2 | as first published, then each change: 28 March 2011 to 1 March 2012 | 2025-12-19 |
| `ley-2011-004/` | Ley 4/2011, de 10 de marzo, del Empleo Público de Castilla-La Mancha. | 18 | as first published, then each change: 22 September 2011 to 22 March 2024 | 2026-04-16 |
| `ley-2011-007/` | Ley 7/2011, de 21 de marzo, de Espectáculos Públicos, Actividades Recreativas y Establecimientos Públicos de Castilla-La Mancha. | 3 | as first published, then each change: 20 April 2011 to 28 December 2019 | 2026-10-08 |
| `ley-2011-008/` | Ley 8/2011, de 21 de marzo, del Consejo del Agua de Castilla-La Mancha. | 2 | as first published, then each change: 1 April 2011 to 20 March 2022 | 2025-12-19 |
| `ley-2011-009/` | Ley 9/2011, de 21 de marzo, por la que se crean el canon eólico y el Fondo para el Desarrollo Tecnológico de las Energías Renovables y el Uso Racional de la Energía en Castilla-La Mancha. | 1 | as first published: 1 April 2011 | 2025-12-19 |
| `ley-2011-012/` | Ley 12/2011, de 3 de noviembre, de supresión del Defensor del Pueblo de Castilla-La Mancha | 1 | as first published: 29 December 2011 | 2025-12-19 |
| `ley-2011-015/` | Ley 15/2011, de 15 de diciembre, de Emprendedores, Autónomos y Pymes. | 1 | as first published: 15 January 2012 | 2025-12-19 |
| `ley-2012-001/` | Ley 1/2012, de 21 de febrero, de Medidas Complementarias para la Aplicación del Plan de Garantías de Servicios Sociales. | 13 | as first published, then each change: 1 March 2012 to 1 February 2023 | 2026-04-16 |
| `ley-2012-003/` | Ley 3/2012, de 10 de mayo, de autoridad del profesorado. | 1 | as first published: 10 June 2012 | 2025-12-19 |
| `ley-2012-006/` | Ley 6/2012, de 2 de agosto, de acompañamiento de la Ley 1/2012, de 21 de febrero, de Medidas Complementarias para la Aplicación del Plan de Garantía de los Servicios Sociales Básicos de Castilla-La Mancha. | 4 | as first published, then each change: 7 August 2012 to 1 January 2018 | 2025-12-19 |
| `ley-2012-009/` | Ley 9/2012, de 29 de noviembre, de Tasas y Precios Públicos de Castilla-La Mancha y otras medidas tributarias. | 14 | as first published, then each change: 2 December 2012 to 22 March 2024 | 2026-03-30 |
| `ley-2012-011/` | Ley 11/2012, de 21 de diciembre, de Estabilidad Presupuestaria y Sostenibilidad Financiera de la Junta de Comunidades de Castilla-La Mancha. | 4 | as first published, then each change: 1 January 2013 to 1 January 2020 | 2025-12-19 |
| `ley-2013-001/` | Ley 1/2013, de 21 de marzo, de medidas para la dinamización y flexibilización de la actividad comercial y urbanística en Castilla-La Mancha. | 2 | as first published, then each change: 28 March 2013 to 26 March 2023 | 2025-12-19 |
| `ley-2013-004/` | Ley 4/2013, de 16 de mayo, de Patrimonio Cultural de Castilla-La Mancha. | 5 | as first published, then each change: 13 June 2013 to 6 August 2025 | 2025-12-19 |
| `ley-2013-005/` | Ley 5/2013, de 17 de octubre, de ordenación del servicio jurídico de la Administración de la Junta de Comunidades de Castilla-La Mancha. | 6 | as first published, then each change: 14 November 2013 to 16 April 2025 | 2025-12-19 |
| `ley-2013-008/` | Ley 8/2013, de 21 de noviembre, de Medidas Tributarias de Castilla-La Mancha. | 11 | as first published, then each change: 30 November 2013 to 1 February 2023 | 2026-03-30 |
| `ley-2014-001/` | Ley 1/2014, de 24 de abril, de supresión de la Sindicatura de Cuentas. | 1 | as first published: 10 June 2014 | 2025-12-19 |
| `ley-2014-002/` | Ley 2/2014, de 8 de mayo, de Museos de Castilla-La Mancha. | 1 | as first published: 17 June 2014 | 2025-12-19 |
| `ley-2014-003/` | Ley 3/2014, de 21 de julio, de garantía de la atención sanitaria y del ejercicio de la libre elección en las prestaciones del Servicio de Salud de Castilla-La Mancha. | 1 | as first published: 1 October 2014 | 2025-12-19 |
| `ley-2014-007/` | Ley 7/2014, de 13 de noviembre, de Garantía de los Derechos de las Personas con Discapacidad en Castilla-La Mancha. | 3 | as first published, then each change: 2 January 2015 to 16 March 2023 | 2025-12-19 |
| `ley-2015-001/` | Ley 1/2015, de 12 de febrero, del Servicio Regional de Mediación Social y Familiar de Castilla-La Mancha. | 1 | as first published: 15 March 2015 | 2025-12-19 |
| `ley-2015-003/` | Ley 3/2015, de 5 de marzo, de Caza de Castilla-La Mancha. | 5 | as first published, then each change: 1 April 2015 to 6 August 2025 | 2026-03-30 |
| `ley-2015-004/` | Ley 4/2015, de 26 de marzo, por la que se crea el Instituto Regional de Investigación y Desarrollo Agroalimentario y Forestal de Castilla-La Mancha. | 4 | as first published, then each change: 8 June 2015 to 31 August 2022 | 2025-12-19 |
| `ley-2015-005/` | Ley 5/2015, de 26 de marzo, de la Actividad Física y el Deporte de Castilla-La Mancha. | 1 | as first published: 28 April 2015 | 2025-12-19 |
| `ley-2015-008/` | Ley 8/2015, de 2 de diciembre, de medidas para la garantía y continuidad en Castilla-La Mancha de los servicios públicos como consecuencia de la entrada en vigor de la Ley 27/2013, de 27 de diciembre, de racionalización y sostenibilidad de la Administración Local. | 1 | as first published: 17 December 2015 | 2025-12-19 |
| `ley-2016-004/` | Ley 4/2016, de 15 de diciembre, de Transparencia y Buen Gobierno de Castilla-La Mancha. | 3 | as first published, then each change: 30 January 2017 to 30 August 2024 | 2026-03-30 |
| `ley-2017-001/` | Ley 1/2017, de 9 de marzo, por la que se establecen medidas adicionales de protección de la salud pública y del medio ambiente para la exploración, investigación o explotación de hidrocarburos utilizando la técnica de la fractura hidráulica. | 4 | as first published, then each change: 12 April 2017 to 26 March 2023 | 2025-12-19 |
| `ley-2017-003/` | Ley 3/2017, de 1 de septiembre, en materia de gestión y organización de la Administración y otras medidas administrativas. | 2 | as first published, then each change: 26 September 2017 to 26 March 2023 | 2025-12-19 |
| `ley-2017-004/` | Ley 4/2017, de 30 de noviembre, de Microempresas Cooperativas y Cooperativas Rurales de Castilla-La Mancha y por la que se modifica la Ley 11/2010, de 4 de noviembre, de Cooperativas de Castilla-La Mancha. | 1 | as first published: 31 December 2017 | 2025-12-20 |
| `ley-2017-005/` | Ley 5/2017, de 30 de noviembre, de Estímulo Económico de Zonas Prioritarias en Castilla-La Mancha. | 1 | as first published: 31 December 2017 | 2025-12-20 |
| `ley-2017-006/` | Ley 6/2017, de 14 de diciembre, de Cámaras Oficiales de Comercio, Industria y Servicios de Castilla-La Mancha. | 1 | as first published: 22 December 2017 | 2026-03-30 |
| `ley-2018-003/` | Ley 3/2018, de 24 de mayo, de protección y apoyo garantizado para personas con discapacidad en Castilla-La Mancha. | 1 | as first published: 6 July 2018 | 2025-12-20 |
| `ley-2018-004/` | Ley 4/2018, de 8 de octubre, para una Sociedad Libre de Violencia de Género en Castilla-La Mancha. | 7 | as first published, then each change: 15 November 2018 to 21 June 2024 | 2026-05-26 |
| `ley-2018-005/` | Ley 5/2018, de 21 de diciembre, de acceso al entorno de las personas con discapacidad acompañadas de perros de asistencia. | 2 | as first published, then each change: 16 January 2019 to 8 February 2022 | 2025-12-20 |
| `ley-2019-002/` | Ley 2/2019, de 15 de marzo, de Academias de Castilla-La Mancha. | 2 | as first published, then each change: 15 April 2019 to 19 February 2025 | 2025-12-20 |
| `ley-2019-003/` | Ley 3/2019, de 22 de marzo, del Estatuto de las Personas Consumidoras en Castilla-La Mancha. | 1 | as first published: 1 May 2019 | 2026-05-12 |
| `ley-2019-006/` | Ley 6/2019, de 25 de noviembre, del Estatuto de las Mujeres Rurales de Castilla-La Mancha. | 2 | as first published, then each change: 18 December 2019 to 1 June 2021 | 2025-12-20 |
| `ley-2019-007/` | Ley 7/2019, de 29 de noviembre, de Economía Circular de Castilla-La Mancha. | 3 | as first published, then each change: 1 January 2020 to 6 August 2025 | 2025-12-20 |
| `ley-2019-008/` | Ley 8/2019, de 13 de diciembre, de Participación de Castilla-La Mancha. | 1 | as first published: 26 June 2020 | 2025-12-20 |
| `ley-2019-009/` | Ley 9/2019, de 13 de diciembre, de Mecenazgo Cultural de Castilla-La Mancha. | 3 | as first published, then each change: 15 January 2020 to 16 April 2025 | 2025-12-20 |
| `ley-2019-010/` | Ley 10/2019, de 20 de diciembre, de Presupuestos Generales de la Junta de Comunidades de Castilla-La Mancha para 2020. | 4 | as first published, then each change: 1 January 2020 to 25 March 2022 | 2026-02-06 |
| `ley-2020-001/` | Ley 1/2020, de 3 de febrero, del Tercer Sector Social de Castilla-La Mancha. | 1 | as first published: 7 March 2020 | 2025-12-20 |
| `ley-2020-002/` | Ley 2/2020, de 7 de febrero, de Evaluación Ambiental de Castilla-La Mancha. | 5 | as first published, then each change: 4 March 2020 to 6 August 2025 | 2026-07-23 |
| `ley-2020-004/` | Ley 4/2020, de 10 de julio, de Fomento y Coordinación del Sistema de Investigación, Desarrollo e Innovación de Castilla-La Mancha. | 2 | as first published, then each change: 9 August 2020 to 8 February 2022 | 2025-12-20 |
| `ley-2020-005/` | Ley 5/2020, de 24 de julio, de Medidas Urgentes para la Declaración de Proyectos Prioritarios en Castilla-La Mancha. | 6 | as first published, then each change: 1 August 2020 to 22 March 2024 | 2025-12-20 |
| `ley-2020-007/` | Ley 7/2020, de 31 de agosto, de Bienestar, Protección y Defensa de los Animales de Castilla-La Mancha. | 1 | as first published: 7 March 2021 | 2026-02-23 |
| `ley-2020-008/` | Ley 8/2020, de 16 de octubre, por la que se crea la reserva estratégica de productos sanitarios en Castilla-La Mancha. | 3 | as first published, then each change: 15 November 2020 to 22 March 2024 | 2025-12-20 |
| `ley-2020-009/` | Ley 9/2020, de 6 de noviembre, de Patrimonio de la Junta de Comunidades de Castilla-La Mancha. | 1 | as first published: 19 February 2021 | 2025-12-20 |
| `ley-2021-002/` | Ley 2/2021, de 7 de mayo, de Medidas Económicas, Sociales y Tributarias frente a la Despoblación y para el Desarrollo del Medio Rural en Castilla-La Mancha. | 5 | as first published, then each change: 1 June 2021 to 22 March 2024 | 2026-03-30 |
| `ley-2021-003/` | Ley 3/2021, de 28 de mayo, por la que se crea el Colegio Oficial de Licenciados y Graduados en Ciencias Ambientales de Castilla-La Mancha. | 1 | as first published: 29 June 2021 | 2025-12-20 |
| `ley-2021-004/` | Ley 4/2021, de 25 de junio, de Medidas Urgentes de Agilización y Simplificación de Procedimientos para la Gestión y Ejecución de los Fondos Europeos de Recuperación. | 6 | as first published, then each change: 1 July 2021 to 22 March 2024 | 2025-12-20 |
| `ley-2021-005/` | Ley 5/2021, de 23 de julio, del Régimen Administrativo y Fiscal del Juego en Castilla-La Mancha. | 4 | as first published, then each change: 30 January 2022 to 16 April 2025 | 2025-12-20 |
| `ley-2021-006/` | Ley 6/2021, de 5 de noviembre, de extinción de cámaras agrarias provinciales de Castilla-La Mancha y por la que se establece el régimen jurídico para realizar transmisiones de patrimonio procedentes del Instituto de Reforma y Desarrollo Agrario. | 2 | as first published, then each change: 2 December 2021 to 12 August 2022 | 2025-12-20 |
| `ley-2021-007/` | Ley 7/2021, de 3 de diciembre, de la Cámara de Cuentas de Castilla-La Mancha. | 1 | as first published: 2 January 2022 | 2025-12-20 |
| `ley-2022-001/` | Ley 1/2022, de 14 de enero, de Medidas Tributarias y Administrativas de Castilla-La Mancha. | 2 | as first published, then each change: 8 February 2022 to 26 March 2023 | 2025-12-20 |
| `ley-2022-002/` | Ley 2/2022, de 18 de febrero, de Aguas de la Comunidad Autónoma de Castilla-La Mancha. | 6 | as first published, then each change: 20 March 2022 to 14 September 2024 | 2026-03-30 |
| `ley-2022-005/` | Ley 5/2022, de 6 de mayo, de Diversidad Sexual y Derechos LGTBI en Castilla-La Mancha. | 1 | as first published: 1 June 2022 | 2025-12-20 |
| `ley-2022-006/` | Ley 6/2022, de 29 de julio, de la Viña y del Vino de Castilla-La Mancha. | 1 | as first published: 31 August 2022 | 2025-12-20 |
| `ley-2022-007/` | Ley 7/2022, de 29 de julio, de Medidas para la Agilización Administrativa de los Proyectos de Energías Renovables en Castilla-La Mancha. | 1 | as first published: 12 August 2022 | 2025-12-20 |
| `ley-2023-002/` | Ley 2/2023, de 10 de febrero, de Atención Temprana en Castilla-La Mancha. | 1 | as first published: 16 March 2023 | 2025-12-20 |
| `decreto-legislativo-2023-001/` | Decreto Legislativo 1/2023, de 28 de febrero, por el que se aprueba el texto refundido de la Ley de Ordenación del Territorio y de la Actividad Urbanística. | 4 | oldest version available, then each change: 26 March 2023 to 6 August 2025 | 2026-10-29 |
| `ley-2023-007/` | Ley 7/2023, de 10 de marzo, de Atención y Protección a la Infancia y la Adolescencia de Castilla-La Mancha. | 2 | oldest version available, then each change: 14 April 2023 to 16 April 2025 | 2025-12-20 |
| `ley-2023-009/` | Ley 9/2023, de 3 de abril, de Agricultura Familiar y de Acceso a la Tierra en Castilla-La Mancha. | 2 | as first published, then each change: 7 May 2023 to 22 March 2024 | 2025-12-20 |
| `ley-2024-004/` | Ley 4/2024, de 19 de julio, de Integridad Pública de Castilla-La Mancha. | 2 | as first published, then each change: 30 August 2024 to 16 April 2025 | 2025-12-20 |
| `ley-2025-003/` | Ley 3/2025, de 6 de junio, de determinación de la representatividad de las organizaciones profesionales agrarias en Castilla-La Mancha. | 1 | as first published: 2 July 2025 | 2025-12-20 |
| `ley-2025-004/` | Ley 4/2025, de 11 de julio, de Simplificación, Agilización y Digitalización Administrativa. | 1 | as first published: 6 August 2025 | 2026-03-30 |
| `ley-1985-006/` | Ley 6/1985, de 13 de noviembre, del Patrimonio de la Comunidad Antónoma de Castilla-La Mancha. | 11 | as first published, then each change: 23 December 1985 to 19 February 2021; **repealed** 19 February 2021 by Ley 9/2020, de 6 de noviembre (BOE-A-2021-2849) | 2025-12-16 |
| `ley-1990-007/` | Ley 7/1990, de 28 de diciembre, de protección de los animales domésticos. | 2 | as first published, then each change: 2 March 1991 to 7 March 2021; **repealed** 7 March 2021 by Ley 7/2020, de 31 de agosto (BOE-A-2020-13916) | 2025-12-17 |
| `ley-1996-001/` | Ley 1/1996, de 27 de junio, de Cámaras Agrarias de Castilla-La Mancha. | 3 | as first published, then each change: 29 June 1996 to 2 December 2021; **repealed** 2 December 2021 by Ley 6/2021, de 5 de noviembre (BOE-A-2022-2541) | 2025-12-18 |
| `ley-2001-005/` | Ley 5/2001, de 17 de mayo, de Prevención de Malos Tratos y de Protección a las Mujeres Maltratadas. | 4 | as first published, then each change: 23 May 2001 to 15 November 2018; **repealed** 15 November 2018 by Ley 4/2018, de 8 de octubre (BOE-A-2018-17065) | 2025-12-18 |
| `ley-2002-012/` | Ley 12/2002, de 27 de junio, Reguladora del Ciclo Integral del Agua. | 7 | as first published, then each change: 9 July 2002 to 20 March 2022; **repealed** 20 March 2022 by Ley 2/2022, de 18 de febrero (BOE-A-2022-4920) | 2025-12-18 |
| `ley-2003-007/` | Ley 7/2003, de 13 de marzo, del Consejo Social de la Universidad de Castilla-La Mancha. | 2 | as first published, then each change: 17 April 2003 to 19 February 2025; **repealed** 19 February 2025 by Ley 1/2025, de 17 de enero (BOE-A-2025-11205) | 2025-12-18 |
| `ley-2005-011/` | Ley 11/2005, de 15 de diciembre, del Estatuto del Consumidor. | 2 | as first published, then each change: 20 January 2006 to 1 May 2019; **repealed** 1 May 2019 by Ley 3/2019, de 22 de marzo (BOE-A-2019-6772) | 2025-12-18 |
| `ley-2007-004/` | Ley 4/2007, de 8 de marzo, de Evaluación Ambiental en Castilla-La Mancha. | 4 | as first published, then each change: 9 April 2007 to 4 March 2020; **repealed** 4 March 2020 by Ley 2/2020, de 7 de febrero (BOE-A-2020-4474) | 2025-12-19 |
| `ley-2009-004/` | Ley 4/2009, de 15 de octubre, de Cámaras Oficiales de Comercio e Industria de Castilla-La Mancha. | 2 | as first published, then each change: 30 October 2009 to 22 December 2017; **repealed** 22 December 2017 by Ley 6/2017, de 14 de diciembre (BOE-A-2018-988) | 2025-12-19 |
| `ley-2009-006/` | Ley 6/2009, de 17 de diciembre, por la que se crea la Agencia del Agua de Castilla-La Mancha. | 2 | as first published, then each change: 20 January 2010 to 20 March 2022; **repealed** 20 March 2022 by Ley 2/2022, de 18 de febrero (BOE-A-2022-4920) | 2025-12-19 |
| `decreto-legislativo-2010-001/` | Decreto Legislativo 1/2010, de 18 de mayo, por el que se aprueba el texto refundido de la Ley de Ordenación del Territorio y de la Actividad Urbanística. | 12 | oldest version available, then each change: 10 June 2010 to 26 March 2023; **repealed** 26 March 2023 by Decreto Legislativo 1/2023, de 28 de febrero (DOCM-q-2023-90063) | 2026-06-09 |
| `ley-2013-002/` | Ley 2/2013, de 25 de abril, del juego y las apuestas de Castilla-La Mancha. | 6 | as first published, then each change: 9 November 2013 to 30 January 2022; **repealed** 30 January 2022 by Ley 5/2021, de 23 de julio (BOE-A-2021-18039) | 2025-12-19 |
| `ley-2013-007/` | Ley 7/2013, de 21 de noviembre, de adecuación de procedimientos administrativos y reguladora del régimen general de la declaración responsable y comunicación previa. | 5 | as first published, then each change: 19 December 2013 to 6 August 2025; **repealed** 6 August 2025 by Ley 4/2025, de 11 de julio (BOE-A-2025-18966) | 2025-12-19 |
| `ley-2014-005/` | Ley 5/2014, de 9 de octubre, de Protección Social y Jurídica de la Infancia y la Adolescencia de Castilla-La Mancha. | 3 | as first published, then each change: 17 November 2014 to 14 April 2023; **repealed** 14 April 2023 by Ley 7/2023, de 10 de marzo (BOE-A-2023-8710) | 2025-12-19 |
| `ley-1993-002/` | Ley 2/1993, de 15 de julio, de Caza de Castilla-La Mancha. | 5 | as first published, then each change: 4 November 1993 to 2 April 2015; **repealed** 2 April 2015 by Ley 3/2015, de 5 de marzo (BOE-A-2015-6877) | 2025-12-17 |

## Source

The consolidated legislation of the Agencia Estatal Boletín Oficial del Estado (BOE), through its open-data API, <https://www.boe.es/datosabiertos/api/legislacion-consolidada>. For each consolidated norm it gives every block of the text (article, disposition, annex, heading) with every version of that block, the day each version took effect (fecha_vigencia) and the norm that made it (id_norma). Each version here is the whole text as it stood on one of those days. The last column above is the BOE's own last-update date for the consolidated text.

## Dates

- Each commit is dated at **noon, Europe/Madrid, on the day the change took effect**: the fecha_vigencia the BOE gives the new block versions.
- A day on which the BOE records a new block version that changes no words is not a version here.
- Block versions with no in-force date (the BOE's 99999999, a date not yet fixed) are left out.
- An act's first commit is its first publication when the BOE's earliest text is the act as enacted; otherwise it is the oldest version the BOE holds.
- Versions that take effect after the retrieval day are on the `futuro` branch, never merged into `main`.

## Files

`<act>/art-005.md` is Artículo 5, `art-005-bis.md` Artículo 5 bis; `da-01.md` the Disposición adicional primera, `dt-` transitional, `dd-` repealing and `df-` final dispositions (`-unica` for "única"); `preambulo.md` the preamble, `firma.md` the signature, `anexo-*.md` the annexes. The book, title, chapter and section headings sit at the top of the file of the article that follows them. One paragraph per line; a table one line per row, cells separated by ` | `.

## How it is checked

- Every version of every act is read back from git on the day it took effect and on the day before (`tools/check_repo.py`); both must match `corpus.json`.
- The letters and digits of every version equal those of the BOE's own text of that day, rebuilt from the source XML by a separate reader, and every file's text appears in it.
- Health checks: no merge commits, commit dates never go backwards, nothing dated in the future, and every commit's trailers parse.

## What "author" means

The author of a commit is the norm that changed the text (a law, a decree-law, a ruling of the Constitutional Court), named by its title and BOE identifier, with an e-mail address that cannot exist (`<boe id>@boe.es.invalid`). The committer is always Lexifina.

## Limits

This is not an official publication. Only the texts published in the official journals are authentic. The history starts with the oldest text the BOE consolidates for each norm. Only the norms listed above are included; norms the BOE does not consolidate are not.
