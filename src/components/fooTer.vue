<template>
    <footer>
        <p>Connect with us | Follow us | Dhanak &copy; 2024</p>
  </footer>
</template>

<script>
    export default {
  name: 'fooTer',
  props: {
    msg: String
  }
}
</script>

<style scoped>
    footer {
    background-color: rgba(255, 255, 255, 0.9);
    color: #333;
    text-align: center;
    padding: 20px;
    width: 100%;
    margin-top: 40px;
  }
</style>