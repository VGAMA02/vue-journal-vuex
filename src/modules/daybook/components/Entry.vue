<template>
  <div class="entry-container mb-3 pointer p-2"
  @click="$router.push({name:'entry',params: {id:10} })">
        <div class="entry-tittle d-flex">
            <span class="text-success fs-5 fw-bold">20</span>
            <span class="mx-1 fs-5">Agosto</span>
            <span class="mx-1 fs-5 fw-light">2023,Lunes</span>
        </div>
       
        <div class="entry-description">
            Et officia cupidatat eiusmod eiusmod esse ad ullamco. Ad eiusmod ex velit aute. Incididunt reprehenderit elit ad excepteur laborum ipsum. Officia amet ea consequat non aute esse laborum Lorem culpa. Aliquip elit laborum laborum consectetur. Dolore nulla veniam irure sint eu enim non officia fugiat commodo aliquip. Pariatur velit aliqua esse ullamco deserunt consequat pariatur ex tempor culpa sit tempor dolore.
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

    &:hover{
        background-color: lighten($color: grey, $amount: 45);
        transition: 0.2s all ease-in;
    }

    .entry-description{
        font-size: 11px;
    }
}
</style>