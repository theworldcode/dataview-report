<template>
  <div class="home">
   roeport
   <top-view></top-view>
   <sales-view></sales-view>
   <bottom-view></bottom-view>
   <map-view></map-view>
  </div>
</template>

<script>
    import TopView from '@/components/TopView/TopView'
    import SalesView from '@/components/SalesView/SalesView'
    import BottomView from '@/components/BottomView/BottomView'
    import MapView from '@/components/MapView/MapView'



    export default {
        name: 'Home',
        components: {
            TopView,
            SalesView,
            BottomView,
            MapView
        }

    }
</script>
<style>
    .home {
        width: 100%;
        height: 100%;
        padding: 20px;
        background: #eee;
        box-sizing: border-box;
    }
</style>