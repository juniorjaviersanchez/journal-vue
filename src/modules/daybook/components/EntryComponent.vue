<template>
  <div class="entry-container mb-3 pointer p-2"
    @click="$router.push({name: 'entry', params: {id:10}})">
    <div class="entry-title d-flex">
        <spa class="text-success fs-5 fw-bold">15</spa>
        <span class="mx-1 fs-5">Julio</span>
        <span class="mx-2 fw-light">2021, Jueves</span>
    </div>
    <div class="entry-description">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Maxime ad ratione beatae odio natus quisquam at rerum officiis impedit non aliquam aut, aspernatur qui corrupti, soluta repellat? Sed, asperiores maxime.
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
    .entry-container{
        border-bottom: 1px solid #2c3e50;
        transition: 0.2s all ease-in;

        &:hover {
            background-color: lighten($color: grey, $amount: 45);
        }
    }
</style>