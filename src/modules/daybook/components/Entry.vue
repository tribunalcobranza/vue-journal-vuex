<template>
  <div
    class="entry-container mb-3 pointer p-2"
    @click="$router.push({ name: 'entry', params: { id: 10}})"
  >

        <!-- Titulo -->
        <div class="entry-title d-flex">
            <span class="text-success fs-5 fw-bold">15</span>
            <span class="mx-1 fs-5">Julio</span>
            <span class="mx-2 fw-ligth">2021, jueves</span>
        </div>        

        <div class="entry-description">
            Sit nulla aliquip excepteur est anim nisi ex eiusmod Lorem nostrud. Magna proident duis sunt velit aliqua occaecat irure. Nostrud sint nisi culpa nulla mollit. Irure ut ea commodo velit sunt proident ipsum ex deserunt consectetur cupidatat aute qui veniam. Sint ipsum eu mollit occaecat eiusmod et Lorem voluptate exercitation nisi ullamco voluptate incididunt deserunt. Et ad commodo incididunt enim nisi tempor.
        </div>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
.entry-container {
    border-bottom: 1px solid #2c3e50;
    transition: 0.2s all ease-in;
    &:hover {
        background-color: lighten($color: grey, $amount: 45);
        transition: 0.2s all ease-in;
    }
    .entry-description {
        font-size: 12px;
    }
}
</style>