# steps

```vue
<template>
    <Steps :active="3">
      <StepsItem title="提交订单" :desc="order.createTime" />
      <StepsItem title="付款成功" :desc="order.payTime" />
      <StepsItem title="商品发货" :desc="order.consignTime" />
      <StepsItem title="确认收货" :desc="order.evaluationTime" />
      <StepsItem title="订单完成" :desc="order.endTime" />
    </Steps>
</template>
```

active:当前进度项

title：标题

desc:下方副标题