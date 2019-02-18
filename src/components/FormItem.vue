<!-- src/components/FormItem.vue -->
<template>
  <form class="form-horizontal">
    <fieldset>
      <!-- Form Name -->
      <legend>Photos</legend>

      <!-- Text input-->
      <div class="form-group">
        <label class="col-md-4 control-label" for="title">Title</label>
        <div class="col-md-4">
        <input id="title" name="title" type="text" placeholder="title" class="form-control input-md" required="">

        </div>
      </div>

      <!-- Text input-->
      <div class="form-group">
        <label class="col-md-4 control-label" for="thumbnailUrl">Thumbnail URL</label>
        <div class="col-md-4">
        <input id="thumbnailUrl" name="thumbnailUrl" type="text" placeholder="thumbnail url" class="form-control input-md" required="" >

        </div>
      </div>

      <!-- Text input-->
      <div class="form-group">
        <label class="col-md-4 control-label" for="url">URL</label>
        <div class="col-md-4">
        <input id="url" name="url" type="text" placeholder="url" class="form-control input-md">

        </div>
      </div>

      <!-- Button (Double) -->
      <div class="form-group">
        <label class="col-md-4 control-label" for="save"></label>
        <div class="col-md-8">
          <button id="save" name="save" class="btn btn-success">Save</button>
          <button id="cancel" name="cancel" class="btn btn-danger">Cancel</button>
        </div>
      </div>
    </fieldset>
  </form>
</template>