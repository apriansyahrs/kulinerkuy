<template>
  <div class="card shadow card-product" style="width: 18rem;">
    <img class="card-img-top" :src=" 'assets/img/' + product.gambar" alt="Card image cap" />
    <div class="card-body">
      <h5 class="card-title"> {{ product.nama }}</h5>
      <p
        class="card-text"
      >Harga : Rp. {{ product.harga }}</p>
      <a href="#" class="btn btn-success"><b-icon icon="cart" class="ml-2"></b-icon> Pesan</a>
    </div>
  </div>
</template>

<script>
export default {
  name: "cardProduct",
  props: ["product"],
};
</script>