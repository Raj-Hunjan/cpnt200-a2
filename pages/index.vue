<template>
  <div>
    <Nav/>
    <Header/>
    <Footer/>
  </div>
</template>

<script>
  export default {
  head() {
    return {
      script: [{ src: 'https://identity.netlify.com/v1/netlify-identity-widget.js' }],
    };
  },
};
</script>
