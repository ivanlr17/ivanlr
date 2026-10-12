# Pactos entre particulares: decisiones del proyecto

Última actualización: octubre de 2026.

Este documento recoge lo decidido hasta ahora en las conversaciones con Claude. Los puntos marcados como **pendiente** hay que validarlos con un abogado del país correspondiente. No es asesoramiento jurídico.

## 1. La idea

Una app para formalizar pactos entre particulares, con:
- firma electrónica avanzada;
- cobro automático a plazos;
- valoración mutua de quien paga y de quien presta el servicio;
- un módulo legal y fiscal propio de cada país;
- un expediente de reclamación preparado por si no se paga.

Cubre deudas, préstamos y servicios ocasionales. La app no presta dinero. La financiación llegará en fases posteriores, siempre a través de socios autorizados.

## 2. Producto

### Para todos los usuarios

- **Verificación de identidad obligatoria.** Foto del documento y selfie con prueba de que la persona está presente. Solo mayores de edad. En EE. UU. se pide además el SSN; en Singapur se usa Singpass.
- **Firma avanzada para todos**, no solo en premium. Debe cumplir el artículo 26 del reglamento eIDAS:
  - estar vinculada solo al firmante;
  - permitir identificarlo;
  - estar bajo su control exclusivo;
  - delatar cualquier cambio posterior del documento.
- **Módulo legal y fiscal de cada país**, incluido para todos porque es lo que distingue a la app. Por ejemplo, el modelo 600 en España, o el pagaré y el tipo de interés mínimo del IRS en EE. UU.
- **Cobro automático a plazos** a través de un proveedor de pagos con licencia. La app nunca guarda el dinero.
- **Valoración mutua:**
  - Quien paga se valora solo con el registro automático de pagos.
  - Quien presta el servicio se valora con la confirmación del cliente. Si el cliente no abre una disputa en X días, el servicio se da por cumplido.
  - Las dos valoraciones se pueden recurrir, y el recurso lo revisa una persona.
- **Disputas.** Si el cliente abre una disputa a tiempo, la cuota retenida no cuenta como impago hasta que se resuelva.
- **Importe mínimo para pagar a plazos** (orientativo: 150 €). Por debajo, se paga de una vez y el dinero queda retenido hasta que se confirme el servicio.
- **Pagos hechos fuera de la app.** Cuentan si quien cobra los confirma o si hay justificante.

### Premium y fases posteriores

- **Garantía de cobro.** La aporta una aseguradora socia y la app cobra una comisión. El precio depende de la puntuación de quien paga, del importe y del plazo.
- **Cobro anticipado.** Solo en una fase posterior, para usuarios verificados con pactos previos y buenas valoraciones. La decisión final es del socio financiero, y el filtro de la app se puede recurrir.
- **Asesoría jurídica** para los trámites que no requieren abogado (monitorio, monitorio europeo, proceso europeo de escasa cuantía). La da una red de abogados colegiados en cada país. La app ofrece gratis la información general; el consejo sobre un caso concreto lo da el abogado.
- **Otros servicios:** expediente de reclamación (burofax y monitorio), fiador, comprobación de solvencia con permiso del usuario, certificado de buen pagador, cambio del calendario de pagos y panel para quien presta servicios a menudo.

### Ingresos

- Los pactos y los recordatorios son gratis.
- Un pequeño porcentaje de cada cuota cobrada automáticamente.
- Una suscripción para quien presta servicios a menudo.
- Pago por uso de la garantía, el expediente, el certificado y la asesoría.
- El principal coste por usuario es la verificación de identidad y la firma.

## 3. Impagos y reputación

### Reglas generales

- **Impagos de 50 € o más (UE y España).** Pueden mostrarse como "impago" si se cumple el artículo 20 de la ley española de protección de datos (LOPDGDD):
  - la deuda es cierta, está vencida y se puede exigir ya;
  - el deudor no la ha discutido;
  - se le avisó antes;
  - se borra al pagar y, como máximo, a los 5 años;
  - solo la ve quien está negociando con esa persona un pacto con pago aplazado.
- **Impagos de menos de 50 €.** No se pueden mostrar como impago (disposición adicional sexta de esa ley). En su lugar:
  - se limitan funciones: sin plazos y con pago por adelantado o señal;
  - aparece un aviso fijo que solo ven el deudor y su acreedor;
  - existe una insignia positiva de "buen pagador": quien tiene pactos completados pero no la tiene destaca frente a un usuario nuevo;
  - la opción preferida es la **reseña escrita del acreedor** (condiciones en la tabla siguiente).
- La deuda siempre se puede reclamar, porque el monitorio no tiene importe mínimo.
- **Cómo se calcula la puntuación.** Con una fórmula pública, no con inteligencia artificial: la ley europea de IA trata la puntuación de crédito como de alto riesgo desde el 2 de diciembre de 2027. Sus efectos se limitan a la app y a los pagos; nunca será una puntuación "social".
- Antes del lanzamiento hay que hacer una evaluación de impacto de protección de datos.

### Por país (decisión: el modelo de EE. UU., Reino Unido y Singapur es el preferido)

| | UE y España | EE. UU. | Reino Unido | Singapur |
|---|---|---|---|---|
| Marca visible para impagos pequeños | No (mínimo de 50 €) | No dentro de la app, porque la convertiría en agencia de informes de crédito. Se comunica a las agencias de crédito | Posible con garantías. Puede requerir autorización de la FCA | Posible tras una evaluación previa. **Pendiente:** ley de oficinas de crédito |
| Reseña del acreedor | Posible, con condiciones estrictas (abajo) | Sí. La Sección 230 protege a la plataforma por lo que escriben los usuarios | Sí, con más margen | Sí, evitando acoso y publicación de datos personales. Desde el 29 de junio de 2026 existe una Comisión de Seguridad en Línea |
| Historial de crédito positivo | No existe en los ficheros privados | Sí, comunicándolo a las agencias en formato Metro 2 | Sí. **Pendiente:** requisitos | Solo lo aportan bancos y entidades financieras |

**Condiciones para la reseña en la UE:**
- Es una valoración de si "cumplió lo acordado", no un botón de "denunciar impago".
- Solo puede escribirla quien tuvo un pacto real con esa persona, y solo después del vencimiento, un aviso y un margen de días.
- El texto se ciñe a hechos, sin insultos ni datos personales.
- La persona valorada tiene derecho a responder, y su respuesta se ve junto a la reseña.
- Cuando se paga la deuda, la reseña se marca como "resuelto" o desaparece.
- Hay un canal de denuncia y la retirada es rápida (Ley de Servicios Digitales europea).
- Las dos partes pueden valorarse mutuamente.
- **Pendiente:** confirmar con un abogado especialista en protección de datos. En Estonia se sancionó publicar deudas en un grupo de Facebook.

## 4. Fiscalidad

- **Quién hace qué.** La plataforma informa a Hacienda (modelo 238, directiva DAC7). Cada usuario declara su propia renta.
- **Qué hay que informar según la DAC7:**
  - servicios personales, de cualquier importe;
  - venta de bienes, salvo que no llegue a 30 operaciones ni supere 2.000 € al año;
  - los préstamos y deudas entre particulares no se informan;
  - un tablón que solo publica anuncios, sin intervenir en el pago, queda fuera.
- **Obligaciones de la plataforma:**
  - recoger nombre, dirección, NIF y fecha de nacimiento;
  - informar a Hacienda antes del 31 de enero;
  - comunicarle al usuario lo que se ha informado;
  - cerrarle la cuenta o retenerle los pagos si no da sus datos tras dos recordatorios y 60 días;
  - conservar los registros entre 5 y 10 años.
- **El usuario en España:**
  - no tiene que declarar si todos sus ingresos suman 1.000 € al año o menos; si superan esa cifra, declara;
  - debe darse de alta como autónomo si la actividad es habitual (sentencia del Tribunal Supremo 941/2025): unos 206 € al mes, o 80 € al mes el primer año.
- **Lo que hace la app:** no está diseñada para ocultar ingresos y ofrece a cada usuario un resumen anual para su declaración.
- **Comida casera.** La categoría solo se activa donde es legal: estados de EE. UU. con leyes de libertad alimentaria, Singapur y Reino Unido (con registro).

## 5. Dónde constituir la empresa y lanzar

### Regla anotada

- La empresa será del país donde empiece la actividad, **siempre que se dirija desde allí**. Si se dirige desde España, tributa en España (artículo 8 de la ley del impuesto de sociedades y consulta vinculante V1964-20).
- Si se empieza en España: SL española, con certificación de empresa emergente y préstamo de ENISA, y el sandbox del Banco de España.
- Descartados de momento: Estonia, Irlanda, Andorra y Bulgaria.
- China queda descartada (préstamo entre particulares cerrado allí, informes de crédito con licencia, datos que no pueden salir del país, incompatible con la estrategia europea).

### Alternativa A: UE, empezando por España

1. SL española y certificación de empresa emergente.
2. Cumplir la DAC7, el artículo 20 de la LOPDGDD y las normas de impagos pequeños de la sección 3.
3. Nicho de partida: pactos entre personas de distintos países de la UE (estudiantes Erasmus, gente que vive fuera, trabajadores que cruzan la frontera).
4. Estrategia institucional con el monitorio europeo (sección 6).
5. Cartera de identidad digital europea en cuanto esté disponible (finales de 2026).

### Alternativa B: EE. UU.

1. Filial estadounidense de la empresa matriz. **Pendiente:** asesor fiscal internacional, porque si se dirige solo desde España puede ser residente en los dos países.
2. Pagos: conexión bancaria tipo Plaid y un proveedor de pagos con licencia.
3. Comunicar pagos e impagos a las agencias de crédito (Equifax, Experian, TransUnion) en formato Metro 2:
   - necesita un código de cliente de cada agencia;
   - envío mensual;
   - las reclamaciones se resuelven en 30 días.

   **Pendiente:** si aceptan cuentas en las que quien presta es un particular.
4. Préstamos al 0 % por defecto y respetando los topes de interés de cada estado. Pagaré firmado y tipo mínimo del IRS en préstamos familiares de más de 10.000 $.
5. Consentimiento expreso para enviar SMS automáticos (ley TCPA).
6. Las reseñas de los usuarios quedan protegidas por la Sección 230. No compartir la puntuación con terceros, para no ser agencia de crédito.
7. Diferencia frente a Zirtue y Pigeon: comunicar pagos a las agencias de crédito, incluir servicios, valoración mutua y módulo legal por estado.

### Alternativa C: Reino Unido

1. Sociedad limitada (Ltd) registrada en línea en Companies House. Desde el 18 de noviembre de 2025, todo administrador nuevo debe verificar su identidad, y puede hacerlo desde fuera con pasaporte biométrico. La empresa necesita un domicilio en Reino Unido. Si se dirige desde España, tributa en España: tú o un cofundador debéis dirigirla desde allí.
2. Servicios sin licencia. La plataforma informa a Hacienda (HMRC) con las normas de la OCDE. Los usuarios tienen 1.000 £ al año libres de impuestos y sin obligación de declarar.
3. Préstamos entre particulares: requieren autorización de la FCA (artículo 36H) o un socio que la tenga. Se dejan para una fase posterior.
4. Puntuación y reseñas: decisiones automáticas permitidas con garantías desde el 5 de febrero de 2026. Si la app se acerca a dar referencias de crédito, usar el sandbox de la FCA.
5. Vía institucional: el código de buenas prácticas del comité de procedimiento en línea (OPRC) para plataformas de resolución de conflictos antes del juicio. Reclamaciones por internet con Money Claim Online, hasta 100.000 £.
6. Financiación: los inversores se deducen el 50 % en el impuesto sobre la renta a través del programa SEIS.

### Singapur: laboratorio institucional y expansión

- **Visión:** la app de confianza para la vida diaria en Singapur, casi una red social estándar, con perfiles verificados por Singpass. Pueden usarla ciudadanos, residentes y extranjeros con número de identificación (FIN). El público natural son los recién llegados.
- **Infraestructura pública que usaría:**
  - Singpass y Myinfo para la identidad;
  - Firma con Singpass;
  - declaración prerrellenada de Hacienda (IRAS), con la app como intermediaria;
  - tribunal de reclamaciones menores por internet;
  - sandbox del MAS;
  - SGFinDex más adelante.
- **Préstamos entre particulares: aplazados hasta una expansión.** **Pendiente:** confirmar que pagar un servicio a plazos no se considera préstamo según la ley de prestamistas.
- **Normas para plataformas:**
  - la Comisión de Seguridad en Línea funciona desde el 29 de junio de 2026 y, en casos de acoso, la plataforma tiene 24 horas para responder;
  - con mucho alcance, la app podría quedar sujeta a los códigos de seguridad de la autoridad digital (IMDA);
  - si la app controla el trabajo, podría aplicarse la ley de trabajadores de plataformas.
- **Primeros pasos:**
  1. GovTech: condiciones para integrar Singpass, Myinfo y su firma.
  2. MAS: sandbox para la puntuación.
  3. IRAS: incorporarse como intermediaria de la declaración prerrellenada.
  4. Tribunales: expedientes preparados para su sistema en línea.

## 6. Estrategia institucional europea (monitorio europeo)

- **Fase 0 (meses 0 a 3):**
  - módulo que genera los formularios del monitorio europeo y del proceso de escasa cuantía;
  - mapa de procedimientos por país con el Portal e-Justicia;
  - informe de dos páginas para presentar a las instituciones;
  - primeros abogados colaboradores.
- **Fase 1 (meses 3 a 9):**
  - consulta a la Red Judicial Europea en materia civil y mercantil;
  - contacto con la Dirección General de Justicia de la Comisión (DG JUST) y participación en sus consultas públicas;
  - piloto con la Erasmus Student Network y oficinas internacionales de universidades;
  - registro en el Portal de Financiación de la UE y búsqueda de consorcio para la convocatoria JUST-2027-JACC-EJUSTICE.
- **Fase 2 (meses 9 a 24):**
  - integración de la cartera de identidad digital europea;
  - compatibilidad con el punto de acceso electrónico europeo (Reglamento 2023/2844 y reglamentos de ejecución 2026/101 y 2026/102);
  - en España, recordatorios certificados que sirvan como intento previo de acuerdo (MASC) antes de demandar.
- **Fase 3 (a partir del mes 24):** datos del piloto para la Comisión y expansión a los países con más estudiantes y trabajadores que se mueven por la UE.

## 7. Preguntas pendientes para abogados

- **España:**
  - ¿La reseña del acreedor por impagos de menos de 50 € es compatible con la LOPDGDD?
  - ¿Qué figura hace falta para ofrecer el seguro de una aseguradora?
  - ¿La herramienta de pactos cuenta como plataforma a efectos de la DAC7?
- **UE:** ¿cómo se hace la evaluación de impacto de la puntuación y qué supone la sentencia SCHUFA sobre decisiones automatizadas?
- **EE. UU.:**
  - ¿Aceptan las agencias de crédito préstamos entre particulares?
  - ¿Qué leyes estatales de cobro de deudas aplican?
  - ¿Cómo se estructura la filial?
- **Reino Unido:** ¿mostrar marcas de impago es dar "referencias de crédito" a efectos de la FCA? ¿Cuál es el alcance del artículo 36H?
- **Singapur:**
  - ¿Se aplica la ley de oficinas de crédito a la puntuación?
  - ¿Se aplica la ley de prestamistas a los pagos a plazos de servicios?
  - ¿En qué condiciones se integra Singpass?
