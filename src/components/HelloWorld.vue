<template>
  <div class="hello">
    <Tabs @changePage="tabChange" indexTab="friend">
      <TabPanel
        label="好友榜"
        hash="friend"
        fontsize="36"
        tabheight="90"
        color="red">
        <div class="first">1</div>
      </TabPanel>
      <TabPanel
        label="全省榜"
        hash="convince"
        fontsize="36"
        tabheight="90"
        color="red">
        <div class="second">2</div>
      </TabPanel>
      <TabPanel
        label="全国榜"
        hash="country"
        fontsize="36"
        tabheight="90"
        color="red">
        <div class="three">3</div>
      </TabPanel>
    </Tabs>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {

    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}
</style>
