<template>
  <div class="hello">
    <ion-label>Label</ion-label>
    <button ion-button @click="handleClick">Default</button>
    <button ion-button color="secondary">Secondary</button>
    <ion-label>Label22</ion-label>
    <ion-item>
      <ion-label floating>Username</ion-label>
      <ion-input type="text"></ion-input>
    </ion-item>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String
  },
  methods: {
    handleClick() {
      console.log("clicked");
    }
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
</style>
