<template>
  <div>
    <h2>Devices</h2>

    <b-list-group>
      <b-list-group-item href="#" class="flex-column align-items-start">
        <div class="d-flex w-100 justify-content-between">
          <h5 class="mb-1">Sittingroom</h5>
          <b-button-group size="lg">
            <b-button>Edit</b-button>
            <b-button variant="danger">Delete</b-button>
          </b-button-group>
        </div>
        <p class="mb-1">
          Device Id
        </p>
      </b-list-group-item>
    </b-list-group>

  </div>
</template>

<style scoped>
h2{
  margin: 0.6em 0
}
</style>
