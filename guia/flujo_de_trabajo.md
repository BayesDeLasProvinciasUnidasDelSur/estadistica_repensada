# Flujo de trabajo 

### Slack

Las comunicaciones se realizarán por Slack.

* Asignaciones e impugnaciones de responsables de traducción.
* Aviso de nuevos capítulo disponible para ser revisado.
* Asignaciones e impugnaciones de personas (más de una) para que hagan la revisión del capítulo.

Las comunicaciones se hacen oficiales cuando aparzcan publicadas en el repositorio `BayesDeLasProvinciasUnidasDelSur/estadistica_repensada`.

### Responsables

Las personas responsables de traducción y verificación de capítulos deben cumplir requisitos mínimos de trabajo y tiempos máximos de entrega.
En caso de incumplimiento, puede impugnarse y transmitirse a otras personas las funciones de responsabilidad.

- **git**: Las personas responsables deben saber trabajar con git o tener asistencia personalizada que garantice el buen desempeño de su grupo de trabajo.
- **Tiempos de traducción**: definir
- **Tiempos de verificación**: definir
- **Edición**: link a traduccion y criterios de edición general.

### Fork y archivos

Las personas responsable deben hacer un fork en su cuenta github (`git@github.com:miusuario/estadistica_repensada.git`), y trabajar sobre el archivo `.tex` correspondiente al capítulo, disponible en la carpeta `libro/`. La forma de organización para la traducción y verificación del capítulo (sea individual, colaborativa u otra) es decisión de la responsable.

### Upstream

Los fork deben mantenerse actualizados con el repositorio `BayesDeLasProvinciasUnidasDelSur/estadistica_repensada`. Para ello es necesario agregar un remoto al fork:

`git remote add upstream git@github.com:BayesDeLasProvinciasUnidasDelSur/estadistica_repensada.git`

De esta forma es posible traer los cambios que ocurran en el repositorio principal al fork individual.

`git pull upstream main --rebase`

El flag `rebase` reordena la historia en caso de que ambos repositorios hubieran hecho cambios, poniendo primero en la historia los cambios que traemos y aplicando las modificaciones locales sobre la nueva historia. Si hubiera una conflicto, automáticamente se suspende el rebase hasta que se seleccione una de las versión, se agregue, y se continúe el rebase.

### Pull request

Una vez terminada la propuesta de traducción, se debe verificar que es posible generar el pdf localmente, sin errores ni warnings. Una vez comprobado eso, se hace el _pull request_ indicando el branch `main` del repositorio `BayesDeLasProvinciasUnidasDelSur/estadistica_repensada`.

### Revision

* Los comentarios sobre la traducción se harán sobre un issue específico para revisión del capítulo. Habrá un issue por capítulo.

* A medida que vayan terminando de hacer sus comentarios, las personas encargadas avisan por el Slack que su revisión está lista.
* Una vez revisado el archivo, la persona a cargo de la traducción hace _commit_ a los cambios que considere pertinentes para que se actualice el _pull request_ y avisa por el Slack que ya está lista la última versión.
* [@pachamaltese](https://github.com/pachamaltese) hace el _merge_.
* [@rivaquiroga](https://github.com/rivaquiroga) actualiza el documento con el seguimiento.
