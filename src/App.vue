<template>
<div class="is-widescreen">
  <div class="columns">
    <div>
      <sidebar />  
    </div>

    <div class="column is-four-fifths">
      
      <section class="section">
        <intro />
      </section>

      <section class="section">
        <personal-work-root />
      </section>
    
    </div>  
  </div>  
</div>


</template>

<script>
import intro from './components/intro/intro';
import sidebar from './components/sidebar/sidebar';
import personalWorkRoot from './components/personalWork/personalWorkRoot';

export default {
  name: 'app',
  components: {
    'intro' : intro,
    'sidebar' : sidebar,
    'personal-work-root' : personalWorkRoot
  }
}
</script>

<style>
@import '../node_modules/bulma/css/bulma.css';

html, body{
  /*CSS resets to override default browser behaviour*/
  margin: 0;
  padding: 0;
  overflow: auto;
  
  background-color: #B0D6DF;
}

.noselect {
  /*Avoid selection of images*/
  -webkit-touch-callout: none; /* iOS Safari */
    -webkit-user-select: none; /* Safari */
     -khtml-user-select: none; /* Konqueror HTML */
       -moz-user-select: none; /* Old versions of Firefox */
        -ms-user-select: none; /* Internet Explorer/Edge */
            user-select: none; /* Non-prefixed version, currently
                                  supported by Chrome, Edge, Opera and Firefox */
}
</style>
