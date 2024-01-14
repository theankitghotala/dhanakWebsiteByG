<template>
    <div class="card">
        <p>
            Hie! I am Aaditya. Cheking if the changes occur or not when pushed to git repo.
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