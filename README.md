# Documentación Legal de IOTUS

Aquí es donde se guarda la versión en Markdown de todos los documentos legales de IOTUS, incluyendo estatutos, códigos de conducta, y cualquier otro documento oficial de la organización.

Mantener estos documentos en un repositorio de Git permite llevar un historial completo de cambios, garantizar su integridad mediante firmas criptográficas y facilitar la revisión colectiva de cualquier modificación.

## Estructura del directorio

Los documentos están organizados en tres carpetas principales:

```
/
├── EstatutosNormativa/        # Estatutos, normativa de funcionamiento interno y código de conducta
├── Plantillas/                # Plantillas reutilizables para la redacción de documentos oficiales
└── AcuerdosFirmados/          # PDFs con firma digital de los acuerdos aprobados
```

> **Nota:** al renombrar cualquier archivo, usar siempre `git mv nombre-antiguo.md nombre-nuevo.md` en lugar de renombrarlo directamente desde el explorador de archivos, para que Git conserve el historial del fichero.

Los archivos en Markdown siguen el formato de nombre `vX.Y_AAAA-MM-DD_nombre-del-documento.md`, donde:
- `vX.Y` es el número de versión.
- `AAAA-MM-DD` es la fecha de aprobación del documento.
- `nombre-del-documento` es un identificador descriptivo en minúsculas con guiones.

## Firma y verificación

Los documentos oficiales se firman con **certificado digital** reconocido, lo que garantiza la autenticidad del documento, la identidad del firmante y la validez legal de la firma.

Los PDFs firmados se almacenan en la carpeta `AcuerdosFirmados/`. Los documentos en Markdown de `EstatutosNormativa/` representan la versión editable y con historial de cambios; su versión firmada y con validez oficial siempre es el PDF correspondiente en `AcuerdosFirmados/`.

### Verificar la firma de un documento

La firma digital incrustada en cada PDF puede verificarse abriendo el archivo con cualquier lector de PDF compatible (como Adobe Acrobat Reader) y consultando el panel de firmas. El certificado del firmante debe estar emitido por una autoridad de certificación reconocida (por ejemplo, la FNMT en España).

## Contribuciones

Este repositorio es mantenido principalmente por los **miembros internos de IOTUS**. Cualquier modificación de un documento existente o incorporación de uno nuevo debe realizarse mediante una *pull request* y ser revisada y aprobada por al menos un miembro autorizado. El documento oficial resultante deberá firmarse digitalmente y añadirse a `AcuerdosFirmados/`.

De forma **excepcional**, se podrán aceptar contribuciones externas mediante *pull request* si están debidamente justificadas. Estas contribuciones estarán sujetas al mismo proceso de revisión y aprobación que las internas.

## Licencia

Los documentos contenidos en este repositorio son propiedad de IOTUS. Salvo que se indique lo contrario en un documento concreto, no se permite su reproducción o modificación fuera del marco de esta organización.