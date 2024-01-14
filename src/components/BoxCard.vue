<template>
    <div class="card">
        <p>
            Hie! I am Aaditya.
        </p>
    </div>
</template>

<script>
export default {
  name: 'BoxCard',
  props: {
    msg: String
  }
}
</script>

<style scoped>
    .card{
        background-color: lightblue;
        height: 280px;
        width: 280px;
        border-radius: 20px;
    }
</style>