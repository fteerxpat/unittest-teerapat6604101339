<template>
  <div class="htmlClass">
    <h1>{{ surename }}</h1>
    <h2>{{ lastname }}</h2>
    <h3>{{ nickname }}</h3>
    <h4>{{ studentnumber }}</h4>
  </div>
</template>


<script>
export default {
  name: 'HtmlComponent',
  data() {
    return {
      surename: 'ธีรภัทร',
      lastname: 'พอจิต',
      nickname: 'ฟลุ๊ค',
      studentnumber: '6604101339'

    }
  },
}
</script>

<style scoped></style>
