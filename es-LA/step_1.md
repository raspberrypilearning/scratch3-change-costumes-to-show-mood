**Abby piensa "Umm"**: [Ver interior](https://scratch.mit.edu/projects/498767227/editor){:target="_blank"}
<div class="scratch-preview" style="margin-left: 15px;">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/498767227/?autostart=false" frameborder="0"></iframe>
</div>

Puedes usar bloques `cambiar disfraz a`{:class="block3looks"} antes y después de un bloque `decir durante`{:class="block3looks"}, `pensar durante`{:class="block3looks"}, `tocar sonido`{:class="block3sound"}, o `esperar`{:class="block3control"} para hacer que tu personaje muestre sus sentimientos.

```blocks3
switch costume to [abby-a v] // disfraz inicial
wait [1] seconds
switch costume to [abby-b v] // mostrar sentimientos
think [Hmm...] for [2] seconds
switch costume to [abby-a v] // volver al disfraz inicial
```

**Consejo:** Asegúrate de usar un bloque que tenga un valor de tiempo, no un bloque `iniciar sonido`{:class="block3sound"}, `decir`{:class="block3looks"}, o `pensar`{:class="block3looks"}, de lo contrario, no verás el cambio de disfraz.

