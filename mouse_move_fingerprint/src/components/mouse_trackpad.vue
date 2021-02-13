<template>
  <div id="mouse_track_pad">Foo bar</div>
</template>

<script lang="ts">
import { Options, Vue } from "vue-class-component";

@Options({
  props: {
    msg: String,
  },
})
export default class MouseTrackPad extends Vue {
  msg!: string;
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#mouse_track_pad {
    display: flexbox;
    background-color: blueviolet;
    height: 100%;
    min-height: 100%;
	flex-direction: column;
}
</style>
