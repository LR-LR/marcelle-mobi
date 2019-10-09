<template>
  <div>
    <img
      :src="require('~/assets/images/supergrandfathersuccess.svg')"
      class="img-fluid col-4 offset-4"
    />
    <div
      class="text-white text-center btn-success rounded-pill p-3 mx-5 btn-lg btn-primary active"
    >JE SUIS BIEN ARRIVE(E) A DESTINATION</div>
    <!--btn -->
  </div>
</template>
<script>
export default {
  data() {
    return {
      message: "LA PAGE DES BOUTONS D'ARRIVEE ET D'URGENCE"
    }
  }
}
</script>
<style scoped>
.click {
  cursor: pointer;
}

.active {
  background-color: #00c52e !important;
  border-color: #00c52e !important;
}
</style>


<!-- @click="sendEmergencyMsg()"




<h1>{{message}}</h1>
  </div>
</template>
<script>
export default {
  data() {
    return {
      message: 'JE SUIS BIEN ARRIVE'
    }
  }
}
</script>
<style scoped>
h1 {
  color: red;
}
</style>
-->
