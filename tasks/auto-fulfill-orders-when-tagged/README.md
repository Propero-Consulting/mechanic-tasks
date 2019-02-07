# Auto-fulfill orders when tagged

* [Task script](./script.liquid)

This task monitors order tags, and when a certain tag is added to an order, it auto-fulfills all unfulfilled items in the order. Optionally, you can choose to notify customers when their order is fulfilled by this task.

## Default options

```json
{
  "order_tag__required": null,
  "notify_customer_on_fulfillment__boolean": false
}
```

## Subscriptions

```liquid
shopify/orders/updated
```

## Documentation

This task auto-fulfills from the store's default location. (If you need to change this, contact support!)