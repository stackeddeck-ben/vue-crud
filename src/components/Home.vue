<!-- src/components/Home.vue -->
<template>
  <div>
    <h1>Home</h1>
    <button type="button" class="btn btn-default btn-lg" @click="goAdd">
      <span class="glyphicon glyphicon-plus" aria-hidden="true" ></span> Add
    </button>
    <br />
    <br />
    <div class="col-sm-6 col-md-4">
      <div class="thumbnail">
        <img src="http://placehold.it/600/92c952" alt="accusamus beatae ad facilis cum similique qui sunt">
        <div class="caption">
          <h3>accusamus beatae ad facilis cum similique qui sunt</h3>
        </div>
      </div>
    </div>
    <div class="col-sm-6 col-md-4">
      <div class="thumbnail">
        <img src="http://placehold.it/600/92c952" alt="accusamus beatae ad facilis cum similique qui sunt">
        <div class="caption">
          <h3>accusamus beatae ad facilis cum similique qui sunt</h3>
        </div>
      </div>
    </div>
    <div class="col-sm-6 col-md-4">
      <div class="thumbnail">
        <img src="http://placehold.it/600/92c952" alt="accusamus beatae ad facilis cum similique qui sunt">
        <div class="caption">
          <h3>accusamus beatae ad facilis cum similique qui sunt</h3>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Home',
  methods: {
    goAdd: function () {
      this.$router.push('/add')
    }
  }
}
</script>