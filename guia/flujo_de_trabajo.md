# Flujo de trabajo 

Las comunicaciones generales se realizarán por Slack.
Las comunicaciones se hacen oficiales cuando aparzcan publicadas en el repositorio `BayesDeLasProvinciasUnidasDelSur/estadistica_repensada`.

## Funciones

- **Traducción**: persona responsable de la traducción de uno de los capítulos.
- **Revisión 1**: persona responsable de la verificación de uno de los capítulos.
- **Revisión 2**: persona responsable de la verificación de uno de los capítulos.

## Requisitos

### Tiempos de trabajo

Las personas responsables de traducción y verificación de capítulos deben cumplir requisitos mínimos de trabajo y tiempos máximos de entrega.

- **Traductores**: Se espera que traduzcan como mínimo 1.5 páginas por semana, mínimo.
- **Revisores**: Se espera que revisen 3 páginas por semana, mínimo.

Se recomienda traducir/revsiar varias páginas las primeras semanas para tener un colchón.
La tolerancia por incumplimiento es de una semana, máximo.
En caso de retrazo superior, su función podrá ser impugnada y asignada a otra persona. 

### Herramientas de trabajo

Las personas responsables deben trabajar con git o tener asistencia personalizada que garantice el buen desempeño de su grupo de trabajo.


- **Repositorio principal**: `git@github.com:BayesDeLasProvinciasUnidasDelSur/estadistica_repensada.git`
- **Fork de traducción**: `git@github.com:usuario/estadistica_repensada.git`

La forma de organización para la traducción y verificación del capítulo (sea individual, colaborativa u otra) es decisión de la responsable.

### Fork y archivos

- **Traductores**: Deben tener un fork del repositorio principal en su cuenta propia de github o de algun servidor git público (e.g. `git@github.com:miusuario/estadistica_repensada.git`), y deberán trabajar solamente sobre el archivo `.tex` correspondiente al capítulo, disponible en la carpeta `libro/`.
- **Revisores**: Luego de que se haya publicado una sección en el repositorio principal, deben abrir un issue en el fork de traducción, donde indicarán las propuestas de cambio, señalando la frase actual y la frase propuesta.

### Upstream

- **Traductores**: Los fork deben mantenerse actualizados con el repositorio principal. Para ello es necesario agregar un remoto al fork:

    `git remote add upstream git@github.com:BayesDeLasProvinciasUnidasDelSur/estadistica_repensada.git`

    De esta forma es posible traer los cambios que ocurran en el repositorio principal al fork individual.

        `git pull upstream main --rebase`

    En caso de que ambos repositorios hubieran hecho cambios, el flag `rebase` coloca los commits publicados en el upstream primero en la historia, re-aplicando las modificaciones locales sobre esa nueva historia.
Si hubiera una conflicto, automáticamente se suspende el rebase hasta que usted seleccione una de las versión, la agregue, e indique continuar con el rebase.

### Pull request

*Hacer un pull request por sección*

- **Traductores**: Una vez terminada la propuesta de traducción de una sección, se debe traer los cambios del upstream, se debe verificar que es posible generar el pdf localmente, sin errores ni warnings, y solo después se hace debe hacer el _pull request_ indicando el branch `main` del repositorio `BayesDeLasProvinciasUnidasDelSur/estadistica_repensada`.

- **Revisores 1**: Una vez terminada la revisión de una sección, luego de alcanzar un acuerdo entre las personas revisoras, debe abrir un pull request en el repositorio principal.

