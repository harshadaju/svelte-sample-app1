<script>
  let w = 1000,
    h;
</script>

<style>
  div {
    background-color: red;
  }
</style>

<div style="width:{w}px;height:{h}px">
  hello from container {w} x {h}
  <input type="number" bind:value={w} />
  <input type="number" bind:value={h} />
</div>
