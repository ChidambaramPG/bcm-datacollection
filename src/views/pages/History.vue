<template>
  <div id="">
    <top-bar />
    <div class="container">
         <cards-list/>
    </div>
  </div>
</template>

<script>
import TopBar from "../shared/TopBar.vue";
import store from '../../store/index.js';
import CardsList from '../components/history/CardsList.vue';

export default {
  name: "Cards",
  components: {
    TopBar,
    CardsList
  },
  computed:{
    cardsSection(){
      return store.state.cardsSecton;
    }
  }
};
</script>
<style scoped>
.brochures-table {
  margin-top: 20px;
}
</style>
