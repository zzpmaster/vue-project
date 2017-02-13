<template>
  <div class="list">
    <md-table v-once>
      <md-table-body>
        <md-table-row v-for="item in items" :key="index">
          <md-table-cell>
            {{ item.name }}
            <span class="list-subtitle">{{ item.subTitle }}</span>
          </md-table-cell>
          <md-table-cell>Factsheet(pdf): Eng | 中文</md-table-cell>
        </md-table-row>
      </md-table-body>
    </md-table>
  </div>
</template>

<script>
export default {
  name: 'list',
  data () {
    return {
      items: [
        {name: 'Fidelity Funds - America Fund', subTitle: '(9 of 9 share classes mathed)'},
        {name: 'Fidelity Funds - America Diversified Fund', subTitle: '(1 of 1 share classes mathed)'},
        {name: 'Fidelity Funds - America Growth Fund', subTitle: '(1 of 1 share classes mathed)'},
        {name: 'Fidelity Funds - ASEAN Fund', subTitle: '(3 of 3 share classes mathed)'},
        {name: 'Fidelity Funds - Asia Focus Fund', subTitle: '(3 of 3 share classes mathed)'}
      ]
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .list {
    width: 85%;
  }
  .list-subtitle {
    color: #666;
  }
</style>
