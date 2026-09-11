# Creative

Drop campaign artwork in this folder, then reference it from the `CAMPAIGNS`
config at the top of the `<script>` block in `index.html`:

```js
{ name:'Product Campaign', platform:'Meta', status:'live', ...
  creative:['creative/brown-sugar-01.jpg','creative/brown-sugar-02.jpg'] }
```

Portrait 4:5 crops look best (they fill the slot without distortion).
Three slots show per campaign card.
