<figure class="hero" style="background:#34f3dd;"></figure>

# Radio Button

Los botones de radio se utilizan en formularios para seleccionar una opción específica. Su comportamiento es excluyente, por lo que sólo es posible la selección de una opción de las disponibles. En el momento de seleccionar la alternativa deseada la anterior se desactiva para activar la nueva.


#### Básico

<textarea code-editor="mixed" code-result-size="80">
<div class="is-medium">
  <!-- Radio 1 -->
  <label class="radio-button" for="radio1">
    <input type="radio" name="my_radios" id="radio1" checked>
    <span>Radio 1</span>
  </label>
</div>
</textarea>


#### Tamaño

<textarea code-editor="mixed" code-result-size="80">
<!-- Radio 1 -->
<label class="radio-button is-small" for="radio1">
  <input type="radio" name="my_radios" id="radio1" checked>
  <span>Radio 1</span>
</label>
<!-- Radio 2 -->
<label class="radio-button is-medium" for="radio2">
  <input type="radio" name="my_radios" id="radio2" >
  <span>Radio 2</span>
</label>
<!-- Radio 3 -->
<label class="radio-button is-large" for="radio3">
  <input type="radio" name="my_radios" id="radio3" >
  <span>Radio 3</span>
</label>
</textarea>


### Full width

<textarea code-editor="mixed" code-result-size="140">
<!-- Radio 1 -->
<label class="radio-button is-medium is-full-width" for="radio1">
  <input type="radio" name="my_radios" id="radio1" checked>
  <span>Radio 1</span>
</label>
<!-- Radio 2 -->
<label class="radio-button is-medium is-full-width" for="radio2">
  <input type="radio" name="my_radios" id="radio2" >
  <span>Radio 2</span>
</label>
<!-- Radio 3 -->
<label class="radio-button is-medium is-full-width" for="radio3">
  <input type="radio" name="my_radios" id="radio3" >
  <span>Radio 3</span>
</label>
</textarea>
