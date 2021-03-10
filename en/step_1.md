## Switch costumes to show the mood of a sprite

<div>
**Abby says hmm**: [See inside](https://scratch.mit.edu/projects/498767227/editor){:target="_blank"}
<div class="scratch-preview" style="margin-left: 15px;">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/498767227/?autostart=false" frameborder="0"></iframe>
</div>

You can change costume before and after a `say for`{:class="block3looks"}, `think for`{:class="block3looks"}, `play sounds`{:class="block3sounds"}, or `wait`{:class="block3events"} block to make you character show their feelings.

```blocks3
switch costume to [abby-a v] // normal costume
wait [1] secs
switch costume to [abby-b v] // show feelings
think [Hmm...] for [2] secs
switch costume to [abby-a v] // back to normal
```

**Tip:** Make sure you use a block that takes time, not a `start sound`{:class="block3sound"} or `say`{:class="block3looks"} or `think`{:class="block3looks"} block, otherwise you won't see the costume change.
