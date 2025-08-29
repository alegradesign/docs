<figure class="hero" style="background:#34f3dd;"></figure>

# Progress Indicator

Por lo general se conocen como barras de progreso y son muy útiles para indicar en pantalla el estado actual del sistema. Son conocidas dos formas de representación de un proceso, la primera, es a través de una barra que se llena indicando el porcentaje de carga. La segunda es la versión indeterminada donde el sistema no le indica al usuario en qué etapa del proceso se encuentra, solo muestra que está procesando la petición.

#### Native Progress Bar

<textarea code-editor="mixed" code-result-size="60">
<progress max="100" value="60"></progress>
</textarea>

#### Progress Bar

<textarea code-editor="mixed" code-result-size="60">
<div class="progress-bar">
  <span class="progress-bar-meter" style="width: 60%"></span>
</div>
</textarea>

#### Progress Circle

<textarea code-editor="mixed" code-result-size="280">
<div class="progress-circle is-small"></div>
<div class="progress-circle is-medium"></div>
<div class="progress-circle is-large"></div>
</textarea>

