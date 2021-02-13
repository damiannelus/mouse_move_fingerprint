<template>
  <div id="mouse_track_pad">
        Foo bar
    </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>


#mouse_track_pad {
    display: flexbox;
    background-color: blueviolet;
    height: 100%;
    min-height: 100%;
	flex-direction: column;
}
</style>
