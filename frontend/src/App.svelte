<script>
  function max() {
    window.runtime.WindowMaximise();
  }
  function unmax() {
    window.runtime.WindowUnmaximise();
  }
</script>

<header style="--wails-draggable:drag" />
<div id="input" style="--wails-draggable:no-drag">
  <button on:click={max}>Max</button>
  <button on:click={unmax}>UnMax</button>
</div>
<div id="result" />

<style>
  header {
    height: 40px;
    background: #555;
  }
</style>
