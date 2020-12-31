<template>
  <div class="about">
    <br />
    <b-navbar toggleable="lg" type="black">
      <div class="container">
        <div class="row justify-content-center">
          <div class="col-lg-6">
            <div class="media text-left">
              <img src="../assets/foto.jpg" class="user-pic mr-3" />
              <div class="media-body">
                <div class="card-body">
                  <h2 class="mt-0">
                    <strong>{{firstName}} {{lastName}}</strong>
                  </h2>
                  <p
                    class="card-text"
                  >Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                  <a href class="btn btn-primary text-white">STATUS</a>
                </div>
              </div>
            </div>
          </div>
        </div>
        <layout />
      </div>
    </b-navbar>
  </div>
</template>

<script>
import Layout from "../../src/components/Layout.vue";
import "bootstrap/dist/css/bootstrap.css";
import "bootstrap/dist/css/bootstrap.min.css";

export default {
  components: { Layout },
  name: "About",
  data: function () {
    return {
      firstName: "Mohammad",
      lastName: "Nuris",
      firstName1: "Galery",
      lastName1: "Foto",
    };
  },
  component: {},
};
</script>

<style scoped>
.Layout-wrepper {
  width: 70%;
  overflow: hidden;
  margin: auto;
}
.item-layout {
  border-radius: 80px;
  float: left;
  margin-right: 30px;
  width: 150px;
  height: 150px;
  background: blueviolet;
}
.user-pic {
  border-radius: 200px;
  height: 100px;
  width: 100px;
  margin-top: 20px;
}
</style>
