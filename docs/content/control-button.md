<figure class="hero" style="background:#34f3dd;"></figure>

# Button

Los botones pueden ser utilizados para ejecutar diferentes tipos de acciones en formularios, cuadros de diálogo, menús de navegación o cualquier espacio en la interfaz.

<textarea code-editor="mixed" code-result-size="90">
<button class="button is-basic" type="button">Button</button>
<button class="button is-primary" type="button">Button</button>
<button class="button is-secondary" type="button">Button</button>
<button class="button is-outline" type="button">Button</button>
<button class="button is-ghost" type="button">Button</button>
</textarea>

### Uso

Para utilizar este componente se creó la clase `.button` puede utilizarse en la etiqueta `<button></button>`, sin embargo, puede ser utilizada en las etiquetas `<a></a>` e `<input/>`, esta última con su respectivo atributo de `type="button"`, `type="submit"` o `type="reset"`.

<textarea code-editor="mixed" code-result-size="90">
<a class="button" href="#">Link</a>
<button class="button" type="submit">Button</button>
<input class="button" type="button" value="Input">
<input class="button" type="submit" value="Submit">
<input class="button" type="reset" value="Reset">
</textarea>

### Botones con íconos

#### Small
<textarea code-editor="mixed" code-result-size="100">
<button class="is-small is-basic">
  <svg class="icon"><use xlink:href="dist/smile-icons.svg#accounting"></use></svg>
  <span>Button</span>
</button>
<button class="is-small is-primary">
  <svg class="icon"><use xlink:href="dist/smile-icons.svg#accounting"></use></svg>
  <span>Button</span>
</button>
<button class="is-small is-secondary">
  <svg class="icon"><use xlink:href="dist/smile-icons.svg#accounting"></use></svg>
  <span>Button</span>
</button>
<button class="is-small is-outline">
  <svg class="icon"><use xlink:href="dist/smile-icons.svg#accounting"></use></svg>
  <span>Button</span>
</button>
<button class="is-small is-ghost">
  <svg class="icon"><use xlink:href="dist/smile-icons.svg#accounting"></use></svg>
  <span>Button</span>
</button>
<button class="is-small is-primary">
  <span>Button</span>
  <svg class="icon"><use xlink:href="dist/smile-icons.svg#accounting"></use></svg>
</button>
</textarea>

#### Medium
<textarea code-editor="mixed" code-result-size="100">
<button class="is-basic">
  <svg class="icon"><use xlink:href="dist/smile-icons.svg#accounting"></use></svg>
  <span>Button</span>
</button>
<button class="is-primary">
  <svg class="icon"><use xlink:href="dist/smile-icons.svg#accounting"></use></svg>
  <span>Button</span>
</button>
<button class="is-secondary">
  <svg class="icon"><use xlink:href="dist/smile-icons.svg#accounting"></use></svg>
  <span>Button</span>
</button>
<button class="is-outline">
  <svg class="icon"><use xlink:href="dist/smile-icons.svg#accounting"></use></svg>
  <span>Button</span>
</button>
<button class="is-ghost">
  <svg class="icon"><use xlink:href="dist/smile-icons.svg#accounting"></use></svg>
  <span>Button</span>
</button>
</textarea>

#### Large
<textarea code-editor="mixed" code-result-size="120">
<button class="is-large is-basic">
  <svg class="icon"><use xlink:href="dist/smile-icons.svg#accounting"></use></svg>
  <span>Button</span>
</button>
<button class="is-large is-primary">
  <svg class="icon"><use xlink:href="dist/smile-icons.svg#accounting"></use></svg>
  <span>Button</span>
</button>
<button class="is-large is-secondary">
  <svg class="icon"><use xlink:href="dist/smile-icons.svg#accounting"></use></svg>
  <span>Button</span>
</button>
<button class="is-large is-outline">
  <svg class="icon"><use xlink:href="dist/smile-icons.svg#accounting"></use></svg>
  <span>Button</span>
</button>
<button class="is-large is-ghost">
  <svg class="icon"><use xlink:href="dist/smile-icons.svg#accounting"></use></svg>
  <span>Button</span>
</button>
</textarea>

#### Icon only

<textarea code-editor="mixed" code-result-size="90">
<button class="is-primary is-pill">
  <svg class="icon"><use xlink:href="dist/smile-icons.svg#accounting"></use></svg>
</button>
<button class="is-secondary">
  <svg class="icon"><use xlink:href="dist/smile-icons.svg#accounting"></use></svg>
</button>
<button class="is-basic">
  <svg class="icon"><use xlink:href="dist/smile-icons.svg#accounting"></use></svg>
</button>
<button class="is-outline">
  <svg class="icon"><use xlink:href="dist/smile-icons.svg#accounting"></use></svg>
</button>
<button class="is-ghost">
  <svg class="icon"><use xlink:href="dist/smile-icons.svg#accounting"></use></svg>
</button>
</textarea>


### Tamaños

<textarea code-editor="mixed" code-result-size="140">
<button class="button is-large" type="submit">Button</button>
<button class="button is-medium" type="submit">Button</button>
<button class="button is-small" type="submit">Button</button>
<button class="button is-full-width" type="submit">Button</button>
</textarea>

### Formas

<textarea code-editor="mixed" code-result-size="140">
<button class="button is-square" type="submit">Button</button>
<button class="button is-pill" type="submit">Button</button>
<button class="button is-rounded" type="submit">Button</button>
<button class="button is-rounded-left" type="submit">Button</button>
<button class="button is-rounded-right " type="submit">Button</button>
</textarea>


