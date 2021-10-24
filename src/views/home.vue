<template>
  <div class="home">
    <h1>Hello Rodrigo</h1>
  </div>
</template>

<script>
export default {
  data() {
    return {
      data: "",
    };
  },
  mounted() {
    console.log(this.$store.getters.data);
  },
  methods: {
    action() {
      console.log("hello world");
    }
  },
  components: {}
};
</script>

<style scoped>
h1 {
  color: whitesmoke;
  justify-self: center;
  align-self: center;
}

.home {
  display: grid;
  height: 100vh;
  width: 100vw;
  background-color: #252627;
}
</style>


/*-------------- IPHONE 5 ----------------*/
@media only screen and (min-device-width: 320px) and (max-device-width: 568px) and (orientation: portrait)


@media only screen and (min-device-width: 768px) and (max-device-width: 1024px)

/*-------------- HALF SCREEN ----------------*/
@media only screen and (min-device-width: 500px) and (max-width: 1000px) 


/*-------------- FULL SCREEN ----------------*/
@media only screen and (min-width: 1001px)