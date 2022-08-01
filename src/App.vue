<template>

<HelloWorld></HelloWorld>
<LookPanel></LookPanel>
<MyFooter></MyFooter>
<AddDirectory></AddDirectory>

</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import MyFooter from './components/MyFooter.vue'
import LookPanel from './components/LookPanel.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    MyFooter,
    LookPanel,

}
}
</script>


