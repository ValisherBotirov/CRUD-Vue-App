<template>
  <div class="crud--page">
    <form class="row g-3">
      <div class="col-md-6">
        <label for="inputEmail4" class="form-label">Name</label>
        <input
          type="text"
          class="form-control"
          id="inputEmail4"
          placeholder="Valisher"
        />
      </div>
      <div class="col-md-6">
        <label for="inputPassword4" class="form-label">Surname</label>
        <input
          type="text"
          class="form-control"
          id="inputPassword4"
          placeholder="Botirov"
        />
      </div>
      <div class="col-12">
        <label for="inputAddress" class="form-label">Email</label>
        <input
          type="email"
          class="form-control"
          id="inputAddress"
          placeholder="valisherbotirov1218@gamil.com"
        />
      </div>
      <div class="col-12">
        <label for="inputAddress2" class="form-label">Job</label>
        <input
          type="text"
          class="form-control"
          id="inputAddress2"
          placeholder="Businesman"
        />
      </div>
      <div class="col-12">
        <button type="submit" class="btn btn-primary">Add Info</button>
      </div>
    </form>
  </div>
</template>

<style scoped>
.crud--page {
  margin-top: 30px;
}
</style>
