<template>
  <div>
  	<title>Sieged- Eagle Softworks</title>
	<br/>
    <h2>Sieged Game View</h2>
    <!-- WebGL loader -->

    <!-- might need to use CORSBuster / SOPBuster -->
    <div>
      <!-- https://github.com/wmhilton/cors-buster -->
      <iframe id="game-viewer" src="https://cors-buster-tbgktfqyku.now.sh/raw.githubusercontent.com/eaglesoftworks/sieged/master/WebGLBuild/index.html" >
      </iframe>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from "vue";

export default Vue.extend({

});
</script>

<style lang="scss">
.game-viewer {
  display: block
}
</style>
