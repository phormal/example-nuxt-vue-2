<template>
  <div class="container">
    <h1>Phormal</h1>

    <PhormalContent/>
  </div>
</template>

<script>
import PhormalContent from '~/components/PhormalContent';

export default {
  name: 'Index',

  components: {
    PhormalContent,
  }
};
</script>

<style>
body {
  background-color: rgb(245, 245, 245);
}

:root {
  font-family: Inter, Avenir, Helvetica, Arial, sans-serif;
  font-size: 16px;
  line-height: 24px;
  font-weight: 400;
  color-scheme: light dark;

  font-synthesis: none;
  text-rendering: optimizeLegibility;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  -webkit-text-size-adjust: 100%;
}

.container {
  margin: 50px auto 0;
  max-width: 700px;
  background-color: #fff;
  padding: 20px;
  border-radius: 10px;
  box-shadow: 0 0 6px rgba(0, 0, 0, 0.1);
}

h1 {
  font-size: 2.5rem;
  font-weight: 700;
  line-height: 1.2;
  margin: 0 0 1rem;
  font-style: italic;
}

</style>
