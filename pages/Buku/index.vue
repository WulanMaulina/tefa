<template>
  <div class="container-fluid">
    <div class="row">
      <div class="col-lg-12">
        <h2 class="text-center my-4">BUKU</h2>
        <div class="my-3">
          <input type="text" class="form-control rounded-5" placeholder="Mau baca apa hari ini?">
        </div>
      </div>
      <div class="my-3 text-muted">menampilkan 3 dari 3</div>
      <div class="row">
        <div class="col-lg-2">
          <div class="card-mb-3">
            <div class="card-body">
              <img src="~/asset/img/days.jpg" class="days" alt="days" />
            </div>
          </div>
        </div>
        <div class="col-lg-2">
          <div class="card-mb-3">
            <div class="card-body">
              <img src="~/asset/img/mariposa.jpg" class="mariposa" alt="mariposa" />
            </div>
          </div>
        </div>
        <div class="col-lg-2">
          <div class="card-mb-3">
            <div class="card-body">
              <img src="~/asset/img/12.jpg" class="12" alt="12" />
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.container-fluid {
  background-image: url("../asset/img/yy.webp");
  height: 100;
  background-position: center;
  background-repeat: repeat;
  background-size: cover;

}
.card-body {
  width: 100%;
  height: em;
  padding: 0;
}
.cover {
  width: 100%;
  height: 100%;
  object-fit: cover;
  object-position: 0 30;
}
</style>
