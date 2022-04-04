<template>
  <div 
    class="entry-conteiner mb-3 pointer p-2"
    @click="$router.push({name:'entry', params:{id: 1}})"
  >
    <!-- TITULO -->
    <div class="entry-title d-flex">
        <span class="text-success fs-5 fw-bold">15</span>
        <span class="mx-1 fs-5">Julio</span>
        <span class="mx-2 fw-light">2021, Jueves</span>
    </div>

    <div class="entry-description">
        In officia quis nisi ea magna pariatur voluptate sint velit amet eu. Ipsum velit sint dolore duis consequat fugiat excepteur ipsum. Ut adipisicing amet deserunt laboris sit duis qui sit ut duis. Amet qui proident non irure veniam enim.
    </div>
  </div> 
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
.entry-conteiner{
    border-bottom: 1px solid #2c3e50;
    transition: 0.2s all ease-in;

    &:hover{
        background-color: lighten($color: gray, $amount: 45);
        transition: 0.2s all ease-in;
    }

    .entry-description{
        font-size: 12px;
    }
}
</style>