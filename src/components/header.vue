<template>
  <div class="vheader">
    <div class="float_div"></div>
    <div class="inner_vheader">
      <ul class="inner_vheader_ul">
        <li>
          <img src="../assets/logo.png" alt />
        </li>
        <li></li>
        <li></li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: 'vheader',
  data () {
    return {}
  }
}
</script>

<style scoped>
.vheader {
  height: 100px;
  background-color: rgb(85, 81, 81);
}
.float_div{
  float: left;
  height: 50%;
  margin-bottom: -40px;
}
.inner_vheader {
  clear: both;
  position: relative;
  height: 80%;
  width: 80%;
  margin: auto;
}
.inner_vheader_ul {
  height: 100%;
  list-style: none;
}
.inner_vheader_ul li {
  height: 100%;
  float: left;
}
li > img {
  height: 100%;
}
</style>
