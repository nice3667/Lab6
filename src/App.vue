<script setup>
import LikeSad from "./components/LikeSad.vue";
</script>
<template>
  <div class="container w-100">
    <div class="row justify-content-center">
      <div v-for="n in 6" :key="n" class="col-3 m-3 p-2">
        <div class="card" style="width: 18rem">
          <img
            src="https://th.bing.com/th/id/OIP.gaPHi7Q16KZ2lvcvhcU1qAHaEo?pid=ImgDet&rs=1"
            class="card-img-top"
            alt="..."
          />
          <div class="card-body">
            <h5 class="card-title">Card title</h5>
            <p class="card-text">
              Some quick example text to build on the card title and make up the bulk of
              the card's content.
            </p>
           <LikeSad></LikeSad>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>