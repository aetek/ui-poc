<template>
    <div>
        <div class="panel panel-primary">
            <div class="panel-heading">
                <h3 class="panel-title">{{ order.orderNumber }}</h3>
            </div>
            <div class="panel-body">
                {{ order.amount }}
            </div>
        </div>
    </div>
</template>

<script>
  export default {
    props: ['order']
  }
</script>