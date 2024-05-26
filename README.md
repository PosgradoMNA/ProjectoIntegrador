# Proyecto Integrador
## Optimización de Portafolio de Inversión

### Tutor: Dr. Luis Eduardo Falcón Morales

### Equipo 15:
- Jose Fabricio Barahona Amaya 
- Andrés Eduardo Figueroa García 
- Isaac Francisco Viramontes Castillo 

#### Descripción:
Este proyecto pretende implementar una alternativa por medio del uso de los sistemas apoyados por la inteligencia artificial, para asistir en la toma de decisiones financieras orientadas a valorar acciones empresas, su utilidad y practicidad para áreas financieras y personas particulares que compran y venden acciones en mercados de valores para obtener beneficios sobre sus inversiones. 

#### Antecedentes:
- Empresa: TeamUp Costa Rica, está en búsqueda de implementar productos innovadores basados en inteligencia artificial, están interesados en poner el mercado los servicios de asesoría en inversiones financieras con instrumentos disponibles dentro y fuera del país en donde opera. Debido a que este proyecto no utiliza datos privados de la compañía, no se requerirá algún tipo de acuerdo de confidencialidad. La empresa se define como una empresa consultora con una red de profesionales con experiencia, conocimientos y la mejor actitud de servicio en servicios de asesoría estratégica, definición de propuestas ganadoras (concursos), arquitectura empresarial, asesoría en procesos de innovación y transformación digital. 
- Sector Industrial al que Pertenece: Información en Medios Masivos - Edición de periódicos, revistas, libros, directorios, software y otros materiales 
- Lugar de Aplicación: Belén, Heredia, Costa Rica. 

#### Entendimiento del Negocio:
##### Objetivos
*General*

Analizar la importancia y utilidad de invertir en mercados de capitales y la introducción de modelos de inteligencia artificial en la asistencia para la inversión en mercados financieros con el fin que los inversionistas puedan tomar decisiones oportunas y efectivas por medio de la elaboración un portafolio de inversión exitoso donde se maximizan las ganancias y se diversifica el riesgo y su aplicación en economías que carecen de mercados capitales como es caso de la economía hondureña. 

*Específicos*
- Implementar un modelo para configurar un portafolio de inversión apoyado en teoría de portafolio elaborada por Harry M. Markowitz y evaluar su desempeño y utilización. 
- Comparar los diferentes modelos de diseño de portafolio. 
- Implementar ejecuciones prácticas asistidas por inteligencia artificial en un escenario al alcance. 
- Evaluar los resultados de la implementación experimental asistida por computadora de los diferentes modelos. 

##### Preguntas de Negocio
- ¿Qué tan confiables son los resultados de las simulaciones y aplicación de inteligencia artificial a los mercados bursátiles y como se comprueba su efectividad? 

- ¿Cómo puede asistir la minería de texto o procesamiento de lenguaje natural en el comportamiento de los mercados financieros y en la toma de decisiones de inversión?

  
##### Formulación del Problema 
El problema está en implementar una solución por medio de la cual se pueda conformar un portafolio de inversión óptimo, el cual en la medida de lo posible pueda predecir comportamientos que se pueden acercar a la realidad en los mercados de capitales y dar soluciones en tiempos útiles emulando el comportamiento de un experto financiero y con la capacidad procesar la información histórica, proveniente de datos estructurados (precios de mercados) y no estructurados (noticias). El modelo te inteligencia artificial se implementará de forma en la que se pueda formular un portafolio en base a la asistencia del computador, en donde se pueda recomendar a los inversionistas un portafolio que les permita obtener mejores beneficios al menor riesgo. También es se contextualizará la investigación a la utilidad en la práctica para inversionistas de Latinoamérica, una región en la que varios países carecen de mercados de capitales locales y opciones de inversión rentables. 

##### Contexto 
Los mercados de capitales son una opción de financiamiento para las empresas que desean financiarse vendiendo parte del capital de la empresa por medio de un instrumento llamado acción o por medio de la emisión de deuda. Por otro lado, el comprador o inversionista se vuelve parcialmente propietario de una parte de la compañía en vez de volverse un acreedor y representa una oportunidad de inversión como alternativa al mercado de dinero en el cual suele invertir en bonos que para el emisor son deuda. (Vázquez, 2012, pp. 55-79)

Para que una empresa pueda acceder a vender acciones o emitir deuda en un mercado organizado, esta debe cumplir con una serie de normas y certificaciones que el mercado exige con el fin de trasladar confiabilidad y atracción por para los inversionistas. Las empresas salen al mercado fijando un precio para cada acción el cual ha sido fijado mediante una serie de estudios y métodos de valuación que no siempre pueden ser el precio justo, en algunos casos el precio de la acción luego de la oferta pública inicial aumenta o disminuye drásticamente. 

Cuando una corporación emite acciones o deuda por primera vez o agrega acciones al mercado (emite un nuevo paquete de acciones), estas se negocian en el mercado primario y son negociados al precio fijo que el emisor estimó “el más justo”. Una vez colocadas todas las acciones emitidas en el mercado los propietarios de las acciones pueden revenderlas, lo que se lleva a cabo en un mercado secundario. 

Los precios de las acciones en mercados secundarios ya no son fijados en base a estudios de valoración si no que son establecidos mediante la oferta y la demanda de la misma, así como la decisión de la empresa de emitir o retirar acciones del mercado mediante la compra de acciones a los accionistas. Hay empresas que son oportunistas y hacen un seguimiento cercano del precio de mercado de sus acciones para emitir nuevas acciones y captar los recursos directamente y quitar esa cuota en parte el mercado secundario. Estas decisiones pueden saturar el mercado y hacer que las acciones bajen de precio. 

El método de valoración en mercados secundarios por tanto en las bolsas de valores más importantes del planeta está dado por la negociación entre el que vende y el que compra, o también llamado método de subasta de doble punta. Este método de valuación de acciones es el implementado en las bolsas de valores más grandes del mundo incluyendo la bolsa NYSE (New York Stock Exchange) en la cual cotizan la mayoría de las empresas en Estados Unidos de América.  

El riesgo juega un papel importante en el mercado de acciones ya que los dividendos de las acciones van acordes del éxito o el fracaso de la empresa. Por tanto, existe el peligro de perder en su totalidad una inversión realizada con alto riesgo, la cual pudo haber sido atractiva ya que a mayor riesgo mayor ganancias. 

Un portafolio financiero es entonces la colección de activos con las cuales cuenta una persona o empresa de los cuales obtiene una utilidad financiera que podría provenir de varias fuentes: intereses en el caso de bonos, depósitos en mercados de dinero, dividendos pagados por acciones en mercados de capitales, la venta de acciones o transacciones en mercados de derivados. 

Harry M. Markowitz planteó su teoría del portafolio, en la que, mediante datos históricos, aplicación de covarianzas estadísticas, evaluación de expectativas (ya que el precio de una acción va según lo que esta retornará en el futuro) y valoración del riesgo, optimiza un portafolio de inversión maximizando las ganancias y diversificando el riesgo. 

La teoría del portafolio de Markowitz es utilizada por los inversionistas para ayudar a la toma de decisiones de inversión. Sin embargo, el saber las tendencias de los precios de las acciones, sería para los inversionistas una información valiosa para sus finanzas, ya que podrían tomar decisiones adecuadas en el momento indicado. El resultado de la aplicación de la teoría de Markowitz es determinístico ya que se basa en datos históricos y aplicación de estadística. 

Los seres humanos generalmente toman decisiones no determinísticas y sorprendentes. Por ejemplo, un ser humano es capaz de identificar a una identidad de otro ser humano con solo mirar a los ojos, ver algún rasgo físico, un patrón de caminado, escuchar una voz o inclusive con solo ver una sombra. Esto es algo que definitivamente le da una ventaja grandísima al ser humano por sobre los sistemas computacionales y modelo matemático alguno. Las decisiones de compra de acciones en algunos casos se vuelven subjetivas.  

En los últimos años las ciencias de la computación han sido responsables de representar comportamientos sociales complejos mediante simulaciones y aplicaciones que implementan inteligencia artificial. Los mercados financieros están en la mira de los científicos ya que representan un comportamiento fundamental en el sistema capitalista. 
