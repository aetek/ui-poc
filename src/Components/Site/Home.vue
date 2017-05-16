<template>
    <div class="container">
        <div class="row">
            <div class="col-lg-6">
                <app-order-list></app-order-list>
            </div>
            <div class="col-lg-6"></div>
        </div>
    </div>
</template>
<script>
    import Header from '../Shared/Header.vue'
    import OrderList from '../Site/OrderList.vue'
    export default {
      components: {
        appHeader: Header,
        appOrderList: OrderList
      }
    }
</script>
<style>

</style>