<template>
  <div class="container">
    <table class="table table-hover">
      <thead class="thread-light">
        <tr>
          <th scope="col">Title</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <th scope="row">1</th>
          <td>Name</td>
        </tr>
        <tr>
          <td colspan="2">descriptiondescriptiondescription</td>
        </tr>
      </tbody>
      <tbody>
        <tr>
          <th scope="row">2</th>
          <td>Namae</td>
        </tr>
        <tr>
          <td colspan="2">shousaishousaishousai</td>
        </tr>
      </tbody>
      <tbody>
        <tr>
          <th scope="row">3</th>
          <td>Mingzi</td>
        </tr>
        <tr>
          <td colspan="2">shenmeshenmeshenmeshenme</td>
        </tr>
      </tbody>
    </table>
    <div class="row justify-content-center">
      <div class="col-sm-6">
        <form>
          <div class="form-group row">
            <label for="name" class="col-sm-3 col-form-label">Name</label>
            <input type="text" class="col-sm-9 form-control" id="name">
          </div>
          <div class="form-group row">
            <label for="content" class="col-sm-3 col-form-label">Content</label>
            <input type="text" class="col-sm-9 form-control" id="content">
          </div>
          <button type="submit" class="btn btn-primary">Submit</button>
        </form>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  
}
</script>
