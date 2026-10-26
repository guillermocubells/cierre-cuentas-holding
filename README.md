# Cierre de cuentas anuales de una holding (España)

Un solo fichero HTML. Lo abres, rellenas un formulario y te genera los documentos del
cierre más una hoja de ruta de 81 pasos que va desde «he formulado las cuentas» hasta «ya
está todo presentado y archivado».

No necesita instalar nada, no sube tus datos a ningún sitio y no tiene servidor: es un
fichero que se abre en el navegador y hace todo en tu ordenador.

```
Descarga el repo  ->  abre app.html  ->  rellena el formulario  ->  exporta a PDF
```

## Para quién es

Fundador o fundadora con una **sociedad holding española (SL)** que participa en otra u
otras sociedades, y que tiene que cerrar el ejercicio: formular las cuentas, aprobarlas,
legalizar los libros, depositar en el Registro Mercantil y presentar el Impuesto sobre
Sociedades.

Si tu estructura es otra (SA, cooperativa, sucursal, sociedad extranjera) te servirá la
hoja de ruta, pero los documentos no.

## Qué te da

| Lo que genera | Para qué |
|---|---|
| **Cuentas anuales** | Balance, cuenta de pérdidas y ganancias y memoria |
| **Certificado de formulación** | Lo firma el administrador el día que formula |
| **Acta** | Decisiones del socio único, o acta de junta general |
| **Certificado de acuerdos** | El que acompaña al depósito en el Registro Mercantil |
| **Los 4 libros contables** | Diario, Inventarios y Cuentas Anuales, Actas, Registro de Socios |
| **Hoja de ruta** | 81 pasos en 6 fases, con el estado guardado en tu navegador |
| **Guía del Modelo 200** | El recorrido por el formulario de la AEAT, pantalla por pantalla |
| **Guía del depósito** | El recorrido por el programa D2 y por Legalia 2 |

Los plazos **se calculan con tu fecha de cierre**, no están escritos a mano. Si tu
ejercicio social no acaba el 31 de diciembre, cambias un campo y se recalcula todo.

## Antes de usarlo, tres cosas

**1. Esto no es asesoramiento.** Es una plantilla de cierre de ejercicio, limpiada y
generalizada a partir de un caso concreto. Nadie ha revisado tu caso. Lo que firmes y
deposites te vincula a ti.

**2. Lee [AVISO.md](AVISO.md).** No es el típico descargo de responsabilidad. Son las
correcciones concretas que salieron al verificar contra el BOE lo que el sistema
afirmaba, y hay unas cuantas que cambian lo que ibas a presentar. La más cara: una
holding de nueva creación **probablemente no tiene derecho al tipo del 15%** que medio
internet da por hecho.

**3. Los errores caros no son los campos vacíos.** Esos se ven. Son las frases escritas
en afirmativo que dan por cierto algo que lo era para otra sociedad. Por eso la sección
«Lo que vas a declarar» del formulario tiene casillas sin marcar: **si no marcas una, el
párrafo no se escribe**. Es a propósito. Un hueco se nota; una afirmación falsa, no.

## Los campos del formulario

De dónde sale cada dato. La mayoría están en la **escritura de constitución**: si no la
tienes a mano, pídesela a tu notaría antes de empezar.

### Datos de la holding
| Campo | Qué es | De dónde sale |
|---|---|---|
| Denominación social | Nombre completo, con la forma social | Escritura |
| CIF | | Tarjeta de identificación fiscal |
| Domicilio social | El inscrito, no donde trabajas | Escritura |
| Capital social | En euros | Escritura |
| Núm. participaciones | Total en que se divide el capital | Escritura |
| Valor nominal | Por participación | Escritura |
| Fecha de constitución | | Escritura |
| Ciudad / Provincia | La provincia es la de **tu Registro Mercantil** | Escritura |
| CNAE | **6421** para holdings. Ver aviso abajo | Modelo 036 |

### Ejercicio que cierras
| Campo | Qué es |
|---|---|
| Fecha de cierre | **De aquí salen todos los plazos.** Cámbiala si tu ejercicio no es el año natural |
| Ejercicio | Cómo se titulan los documentos («2025») |
| Cierre en letra | Como aparece dentro del texto («31 de diciembre de 2025») |
| ¿Primer ejercicio? | Desmárcalo a partir del segundo: si no, declaras que no hay comparativas y es falso |

### Administrador y socios
| Campo | Qué es |
|---|---|
| Administrador / DNI / Cargo | Quien firma |
| Domicilio del administrador | Puede ser distinto del domicilio social |
| Unipersonal o pluripersonal | Si es unipersonal **no hay junta**: el socio único decide y lo consigna en acta |

### Participada
| Campo | Qué es |
|---|---|
| Denominación y CIF de la filial | |
| % de participación | |
| Valor de las participaciones | El coste por el que las tienes contabilizadas |
| Núm. de participaciones de la filial | Las que posees |
| ¿Grupo o asociada? | **Si la controlas es grupo.** Cambia la cuenta contable y los epígrafes de la memoria |

### Lo que vas a declarar
| Campo | Qué es |
|---|---|
| Resultado del ejercicio | En negativo si hay pérdidas. **Ojo:** si contabilizaste la factura de notaría y registro, no es cero |
| Otros pasivos a cierre | Deudas pendientes |
| Tipo del Impuesto sobre Sociedades | **No pongas 15 sin comprobarlo.** Lo que escribas aquí es lo que sale en la memoria y en la guía del Modelo 200; si pones 15 te sale un aviso. Ver [AVISO.md](AVISO.md) |
| ¿Exento de auditar? | Se certifica ante el Registro. Sin marcar, el párrafo no se emite |
| ¿Sin ECPN ni EFE? | Idem |
| ¿Aportación no dineraria? | Déjalo sin marcar si aportaste dinero |

### Datos registrales
| Campo | De dónde sale |
|---|---|
| Notario y núm. de protocolo | Escritura |
| Tomo / Folio / Hoja | Escritura o nota simple |
| IRUS | Escritura o nota simple. Lo pide el programa D2 |

## Lo que NO hace

Dicho antes de que lo descubras a mitad:

- **No calcula tu contabilidad.** Tú metes las cifras; él las coloca en los documentos.
- **No comprueba si estás obligado a auditar ni a consolidar.** No te pregunta activo,
  cifra de negocios ni empleados. Esas dos decisiones son tuyas y de tu asesor.
- **No tiene columna de ejercicio anterior.** Si no es tu primer ejercicio, tendrás que
  añadir tú las cifras comparativas.
- **Solo contempla una participada.** Si tienes dos o más, la memoria se queda corta.
- **El modo pluripersonal está a medias.** El acta y el certificado se adaptan. La
  memoria, el Libro de Actas y el Libro Registro de Socios **no**: siguen redactados para
  socio único y te lo dicen en un aviso, pero el texto lo tienes que reescribir tú. El
  Libro de Actas es el que se legaliza, así que ese no lo dejes pasar.
- **No rellena tu cuenta de pérdidas y ganancias.** Solo conoce el resultado, porque lo
  escribes tú. El desglose de ingresos y gastos sale como `[COMPLETA]` a propósito: un
  hueco se ve, un cero no.
- **No calcula tu base imponible ni tu cuota.** El resultado contable no es la base
  imponible: entre medias están los ajustes fiscales, y esos no los sabe nadie por ti.
- **No conoce los festivos.** Los plazos saltan sábados y domingos, nada más.
- **Necesita conexión para exportar a PDF.** La librería se carga desde internet. Sin
  conexión la pantalla se ve bien pero los botones de descarga no funcionan.

## Requisitos prácticos

- **Certificado digital** vigente, de la sociedad o del administrador.
- **Alta previa** como usuario abonado en registradores.org, con el certificado asociado
  a un NIF. Sin eso no puedes presentar ni libros ni cuentas.
- **Autofirma** instalada.
- **Windows** para LEGALIA 2 y para el D2: las dos son aplicaciones de escritorio y no
  hay alternativa web que genere el fichero. Si trabajas en Mac, resuélvelo con semanas
  de margen, no el día antes.

## Licencia

[CC0 1.0](LICENSE). Dominio público. Úsalo, cámbialo, véndelo si quieres, no hace falta
que cites a nadie. Si te ahorra un fin de semana, ya ha cumplido.

## Si encuentras un error

Abre un issue. Especialmente si es un dato que ha caducado: las cifras y los
procedimientos de aquí están verificados a **octubre de 2026** y envejecen.
