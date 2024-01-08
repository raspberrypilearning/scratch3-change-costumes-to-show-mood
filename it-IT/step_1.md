
<div class="scratch-preview" style="margin-left: 15px;">
  <iframe allowtransparency="true" width="485" height="402" src="" frameborder="0"></iframe>
</div>

Puoi usare il blocco `passa al costume`{:class="block3looks"} prima e dopo che uno sprite utilizzi i blocchi `dire per`{:class="block3looks"}, `pensa per`{:class="block3looks"}, `riproduci suono`{:class="block3sound"}, o `attendi`{:class="block3control"} per far esprimere sentimenti ai tuoi personaggi.

```blocks3
switch costume to [abby-a v] // starting costume
wait [1] seconds
switch costume to [abby-b v] // show feelings
think [Hmm...] for [2] seconds
switch costume to [abby-a v] // back to starting costume
```

**Suggerimento:** Assicurati di utilizzare un blocco che abbia una durata temporale, non un blocco `avvia riproduzione suono`{:class="block3sound"}, `dire`{:class="block3looks"} o `pensa`{: class="block3looks"}, altrimenti non vedrai il cambio di costume.



