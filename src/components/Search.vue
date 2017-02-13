<template>
  <div class="search">
      <md-card md-with-hover class="search">
        <md-card-content>
            <div class="search-title">
                <div>Pension scheme fund</div>
                <md-button class="custom-md-button">Select all</md-button>
            </div>
            <div class="search-button">
                <md-button class="md-primary">CPFIS included fund</md-button>
                <md-button class="md-primary">SRS eligible fund</md-button>
            </div>
        </md-card-content>
    </md-card>
  </div>
</template>

<script>
export default {
  name: 'search',
  data () {
    return {
    }
  }
}
</script>

<style scoped>
    .search {
        margin-left: 10px;
        margin-right: 10px;
    }
    .search-title {
        display: flex;
        align-items: center;
        justify-content: space-between;
    }
    .custom-md-button {
        text-transform: none;
    }
    .search-button {
        text-align: left;
    }
</style>
