<template>
  
  <main>

    <janus-viewer>
      <FireBoxRoom>
        <Room use_local_asset="room1">
          <Object id="cube" pos="0 1 5" />
          <Text col="1 0 0" pos="0 2 4">My First Room</Text>
        </Room>
      </FireBoxRoom>
    </janus-viewer>

  </main>

</template>

<style>

</style>

<script setup>

import { ref } from 'vue';

let greeting = ref('');

</script>