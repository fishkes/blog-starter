<template>
  <div class="row page py-4">
    <div class="col">
      <form novalidate="novalidate" class="needs-validation">
        <div class="form-group">
          <label>Title</label>
          <input type="text" placeholder="Post title" class="form-control">
          <div class="text-danger">title is required.</div>
        </div>
        <div class="form-group">
          <label>Body</label>
          <textarea placeholder="Post body" rows="3" class="form-control"></textarea>
          <div class="text-danger">body is required.</div>
        </div>
        <div class="d-flex">
          <button type="submit" class="btn btn-primary mr-2">Save</button>
        </div>
      </form>
    </div>
  </div>
</template>