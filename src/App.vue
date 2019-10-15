<template>
  <div>
    <div id="slogan my-5">
      <div class="text-center">
        <h1>NameGator</h1>
        <br />
        <h6>Gerador de nomes utililzando Vue.js, GraphQL e Node</h6>
      </div>
    </div>

    <div id="main">
      <DomainList></DomainList>
    </div>
  </div>
</template>

<script>
import "bootstrap/dist/css/bootstrap.css";
import "font-awesome/css/font-awesome.css";
import DomainList from "./components/DomainList";

export default {
  name: "app",
  components: {
    DomainList
  }
};
</script>

<style>
#main {
  background-color: #f1f1f1;
  padding: 30px;
}
</style>