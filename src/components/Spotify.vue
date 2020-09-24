<template>
  <div class="iframeContainer">
    <iframe
      src="songUrl"
      width="300"
      height="380"
      frameborder="0"
      allowtransparency="true"
      allow="encrypted-media"
    ></iframe>
  </div>
</template>

<script>
export default {
  props: {
    songId: {
      type: String
    }
  },
  data() {
    return {
      songUrl: "https://open.spotify.com/embed/track/3IV4swNduIRunHREK80owz"
    }
  }
}
</script>
