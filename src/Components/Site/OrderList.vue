<template>
    <div>
        <app-order v-for="order in orders" :order="order"></app-order>
    </div>
</template>

<script>
    import Order from './Order.vue'
    export default {
        data() {
          return {
            orders: [{ orderNumber:'Order 1', amount: 50 }, { orderNumber:'Order 2', amount: 500 }, { orderNumber:'Order 3', amount: 550 }]
          }
        },
        components: {
          appOrder: Order
        }
    }
</script>