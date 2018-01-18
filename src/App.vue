<template>
  <div id="app">
    <appDisplay></appDisplay>
    <Keypad></Keypad>
  </div>
</template>

<script>

import Display from './components/Display';
import Keypad from './components/Keypad';

export default {
  data() {
    return {
      name: 'App',
    };
  },
  components: {
    appDisplay: Display,
    Keypad,
  },
};
</script>

<style>

@import './assets/pure-min.css';

#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

.button-xlarge {
            font-size: 125%;
            padding: 40px;
            margin-top: 10px;
        }
.button-warning {
         background: rgb(223, 117, 20); /* this is an orange */
       }
</style>
