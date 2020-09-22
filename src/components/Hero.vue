<template>
  <div class="hero mt-4">
    <div class="row">
      <div class="col align-self-center">
        <h1 class="mb-4">
          Delicious Food Menu,
          <strong>
            <br />In Your Gadget
          </strong>
        </h1>
        <p
          class="mb-4"
        >Pesan hidanganmu dengan mudah melalui aplikasi, makanan pun akan segera datang kemeja mu.</p>
        <router-link to="/foods" class="btn btn-success" href="#" role="button">
          Pilih Menu
          <b-icon icon="arrow-right" class="ml-2"></b-icon>
        </router-link>
      </div>
      <div class="col d-none d-sm-block">
        <img width="500" src="../assets/img/kulinerkuy.svg" alt />
      </div>
    </div>
  </div>
</template>


<script>
export default {};
</script>

<style>
</style>