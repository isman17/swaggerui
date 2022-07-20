<script>
import SwaggerUI from 'swagger-ui'
import 'swagger-ui/dist/swagger-ui.css';

export default {
  mounted() {
    SwaggerUI({
        url: './src/assets/api.json',
        dom_id: '#swagger'
    })
  }
}
</script>

<template>
  <main>
    Home
    <div id="swagger"></div>
  </main>
</template>
