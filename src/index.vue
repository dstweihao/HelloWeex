<template>
  <div class="wrapper">
    <!-- <image :src="logo" class="logo" />
    <text class="greeting">我是测试页！！!</text> -->
    <!-- <HelloWorld/> -->
    <Login/>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import Login from './activity/Login.vue'
export default {
  name: 'App',
  components: {
    // HelloWorld
    // Home
    Login
  },
  data () {
    return {
      logo: 'https://timgsa.baidu.com/timg?image&quality=80&size=b10000_10000&sec=1528208591&di=58a2c41e0bb3e2d5375a50afaf7a9509&src=http%3A%2F%2Fimg.mp.sohu.com%2Fupload%2F20170714%2Fc471de6934d946a3a28e436b7816d806_th.png'
    }
  }
}
</script>

<style scoped>
  .wrapper {
    justify-content: center;
    align-items: center;
  }
  .logo {
    width: 600px;
    height: 500px;
  }
  .greeting {
    text-align: center;
    margin-top: 70px;
    font-size: 50px;
    color: #41B883;
  }
  .message {
    margin: 30px;
    font-size: 32px;
    color: #727272;
  }
</style>
