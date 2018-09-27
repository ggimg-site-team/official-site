<template>
  <div>
    <!--
      REQUIRED
      The nuxt component contains the content of your current page.
      Nuxt replace automatically the nuxt component by <router-view></router-view>
    -->
    <nuxt/>
    <!--
      Example : This footer will be display on every routes.
    -->
    <my-footer/>
  </div>
</template>

<script>
import MyFooter from '~components/Footer.vue'

export default {
  head: {
    title: 'Our Schedule | GGIMG',
    meta: [
      { charset: 'utf-8' },
      { name: 'viewport', content: 'width=device-width, initial-scale=1' },
      { hid: 'description', content: "Nuxt.js project" }
    ],
    link: [
      { rel: 'icon', type: 'image/x-icon', href: 'https://yt3.ggpht.com/a-/AN66SAyPffvTfB-uXuAs0_uy2mIpz9CGB8_JiEcVJA=s288-mo-c-c0xffffffff-rj-k-no' }
    ]
  },
  components: {
    MyFooter
  }
}
</script>

<style>
.container
{
  margin: 0;
  width: 100%;
  padding: 100px 0;
  text-align: center;
}
.button, .button:visited
{
  display: inline-block;
  color: #008000;
  letter-spacing: 1px;
  background-color: #fff;
  border: 2px solid #3B8070;
  text-decoration: none;
  text-transform: uppercase;
  padding: 15px 45px;
}
.button:hover, .button:focus
{
  color: #C71585;
  background-color: #C71585;
}
.title
{
  color: #DB7093;
  font-weight: 300;
  font-size: 2em;
  margin: 0;
}
</style>