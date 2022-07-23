<template>
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
</template>

<style scoped>
.display--page {
  margin-top: 30px;
}
</style>
