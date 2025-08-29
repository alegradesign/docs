<figure class="hero" style="background:#34f3dd;"></figure>

# Accordion

<textarea code-editor="mixed" code-result-size="450">
<nav class="bg-brand1">
  <ul class="accordion">
    <li class="accordion-section">
      <input id="" name="main-nav" type="radio">
      <label for="">
        <svg class="icon"><use xlink:href="dist/smile-icons.svg#home"></use></svg>
        <a href="#">Inicio</a>
      </label>
    </li>
    <li class="accordion-section has-submenu is-active">
      <input id="incomes" name="main-nav" type="radio" checked/>
      <label for="incomes" class="">
        <svg class="icon"><use xlink:href="dist/smile-icons.svg#input"></use></svg>
        <span>Ingresos</span>
      </label>
      <ul class="accordion-submenu">
        <li><a href="#">Facturas de venta</a><a href="#" title="Nuevo" class="accordion-quick-action">+</a></li>
        <li class="is-active"><a href="#">Facturas recurrentes</a></li>
        <li><a href="#">Pagos recibidos</a></li>
        <li><a href="#">Notas crédito</a></li>
      </ul>
    </li>
    <li class="accordion-section has-submenu">
      <input id="expenses" name="main-nav" type="radio"/>
      <label for="expenses" class="">
        <svg class="icon"><use xlink:href="dist/smile-icons.svg#output"></use></svg>
        <span>Gastos</span>
      </label>
      <ul class="accordion-submenu">
        <li><a href="#">Facturas de venta</a><a href="#" title="Nuevo" class="accordion-quick-action">+</a></li>
        <li><a href="#">Facturas recurrentes</a></li>
        <li><a href="#">Pagos recibidos</a></li>
        <li><a href="#">Notas crédito</a></li>
      </ul>
    </li>
    <li class="accordion-section has-submenu">
      <input id="stock" name="main-nav" type="radio"/>
      <label for="stock" class="">
        <svg class="icon"><use xlink:href="dist/smile-icons.svg#stock"></use></svg>
        <span>Inventario</span>
      </label>
      <ul class="accordion-submenu">
        <li><a href="#">Facturas de venta</a><a href="#" title="Nuevo" class="accordion-quick-action">+</a></li>
        <li><a href="#">Facturas recurrentes</a></li>
        <li><a href="#">Pagos recibidos</a></li>
        <li><a href="#">Notas crédito</a></li>
      </ul>
    </li>
  </ul>
</nav>
<script>
  // Close open section onclick
  const accordionSectionRadio = document.getElementsByName('main-nav')
  let setCheck
  for (let i = 0; i < accordionSectionRadio.length; i++) {
    accordionSectionRadio[i].onclick = function () {
      if (setCheck != this) {
        setCheck = this;
      } else {
        this.checked = false
        setCheck = null
      }
    }
  }
</script>
</textarea>