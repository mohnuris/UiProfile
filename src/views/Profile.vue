<template>
  <div>
    <div class="profile">
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
                    <a href="../views/Users.vue" class="btn btn-primary text-white">STATUS</a>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <layout />
          <!-- start -->

          <!-- end -->
          <br />
          <br />
          <!-- <div class="margin-top">
        <div class="card">
          <div class="card-header">Foto</div>
          <div class="card-body">
            <h5 class="text-left">Special title treatment</h5>
            <div class="row justify-content-center">
              <div class="col-mb-3"></div>
            </div>

            <div
              class="text-left"
            >With supporting text below as a natural lead-in to additional content.</div>
          </div>
        </div>
          </div>-->
          <!-- <div class="row"> -->
          <div class="container-fluid">
            <div class="layout-wrepper">
              <h2>
                {{firstName1}}
                <strong>{{lastName1}}</strong>
              </h2>
              <br />
              <div class="row mb-3">
                <!-- <div class="col-md-3 mt-3"> -->
                <div class="item-layout">
                  <img src alt />
                </div>
                <div class="item-layout">
                  <img src alt />
                </div>
                <div class="item-layout">
                  <img src alt />
                </div>
                <div class="item-layout">
                  <img src alt />
                </div>
                <div class="item-layout">
                  <img src alt />
                </div>
              </div>
            </div>
          </div>
        </div>
      </b-navbar>
    </div>
  </div>
</template>

<script >
import "bootstrap/dist/css/bootstrap.css";
import "bootstrap/dist/css/bootstrap.min.css";
import Layout from "../src/components/Layout.vue";
export default {
  components: { Layout },
  name: "profile",
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
  /* border-radius: 80px; */
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