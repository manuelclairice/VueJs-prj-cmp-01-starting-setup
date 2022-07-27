<template>
  <ul></ul>
</template>

<script>
export default {
   data() {
    return {
        storedResources: [
            { 
              id: 'official-guide', 
              title: 'Official Guide', 
              description: 'The official Vue.js documentation',
              link: 'https://vuejs.org/v2/guide/index.html'
            },
            { 
              id: 'google', 
              title: 'Google', 
              description: 'Learn to Google...',
              link: 'https://google.org'
            }
        ]
    };
   } 
}
</script>