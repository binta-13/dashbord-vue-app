<template>
  <div class="grid grid-cols-2 gap-4">
    <div class="bg-blue-400 w-0">
      <Sidebar/>
    </div>
    <div class="-ml-96">
      <HeadBar/>
      <TableCustomer/>
    </div>
  </div>
  
  
</template>

<script>
import Sidebar from './components/SideBar.vue'
import HeadBar from './components/HeadBar.vue'
import TableCustomer from './components/TableCustomer.vue';
export default {
  name: 'App',
  components: {
    Sidebar,
    HeadBar,
    TableCustomer,
}
}
</script>

