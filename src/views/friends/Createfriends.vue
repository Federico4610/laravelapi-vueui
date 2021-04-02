<template>
  <div class="card shadow mt-4">
    <div class="card-body">
      <h5 class="card-title">ADD FRIEND</h5>
      <form class="row g-3">
        <div class="col-md-6">
          <label for="inputEmail4" class="form-label">Nama</label>
          <input type="text" class="form-control" id="inputEmail4" />
        </div>
        <div class="col-md-6">
          <label for="inputPassword4" class="form-label">No. Telp</label>
          <input type="number" class="form-control" id="inputPassword4" />
        </div>
        <div class="col-12">
          <label for="inputAddress" class="form-label">Alamat</label>
          <textarea
            class="form-control"
            id="inputAddress"
            placeholder="Masukkan Alamat"
          />
        </div>
        <div class="col-12">
          <button type="submit" class="btn btn-primary">ADD</button>
        </div>
      </form>
    </div>
  </div>
</template>
