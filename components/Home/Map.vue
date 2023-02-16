<template>
  <html>

    <h3>My Google Maps Demo</h3>
    <!--The div element for the map -->
    <div id="map"></div>

</html>
</template>

<script>

export default {
    head() {
      return {
        script: [
          {
            src:
              'https://polyfill.io/v3/polyfill.min.js?features=default',
          },
          {
            src:
              'https://maps.googleapis.com/maps/api/js?key=AIzaSyB41DRUbKWJHPxaFjMAwdrzWzbVKartNGg&callback=initMap&v=weekly'
          },
          {
            src:
              '@/assets/js/map.js'
          }
        ],
      }
    }

}
</script>

<style>
/* Set the size of the div element that contains the map */
#map {
  height: 400px; /* The height is 400 pixels */
  width: 100%; /* The width is the width of the web page */
}
</style>