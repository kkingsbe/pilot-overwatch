<script>
  export let src
</script>

<div class="background" style="background-image: url({src})"></div>

<style>
.background {
  height: 100%;
  width: 100%;
  background-size: cover;
  background-repeat: no-repeat;
  background-position: 50% 50%;
  filter: blur(5px) brightness(80%);
}
</style>