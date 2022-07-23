<template>
  <div class="main">
    <h1 class="text-center">CRUD Aplication</h1>

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

    <div class="display--page">
      <table class="table">
        <thead>
          <tr>
            <th scope="col">#</th>
            <th scope="col">Fullname</th>
            <th scope="col">Job</th>
            <th scope="col">Email</th>
            <th scope="col"></th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <th scope="row">1</th>
            <td>Mark</td>
            <td>Otto</td>
            <td>@mdo</td>
            <td>
              <button class="btn btn-primary mx-2">Edit</button>
              <button class="btn btn-danger">Delete</button>
            </td>
          </tr>
        </tbody>
      </table>
    </div>
  </div>
</template>

<script>
import CrudPage from "./components/CrudPage.vue";
import DisplayPage from "./components/DisplayPage.vue";

export default {
  components: {
    CrudPage,
    DisplayPage,
  },
};
</script>

<style scoped>
.main {
  width: 70%;
  margin: 0 auto;
}
.crud--page {
  margin-top: 30px;
}
.display--page {
  margin-top: 30px;
}
</style>
