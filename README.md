# Junction 2022 materials

## Better cities. Delivered.

* [Challenge description](https://www.junction2022.com/challenges-new/wolt)
* [Wolt Drive API docs](https://daas-track.development.dev.woltapi.com/docs/public-api/index.html)


### Quick start

Note! You need **merchant id** and **api token** which you can get from the Wolt booth. See you there!

Creating a delivery order:
```
curl -X POST -H "Content-Type: application/json" -H "Authorization: Bearer <YOUR API TOKEN>" -d @example_delivery_order_request.json https://daas-public-api.development.dev.woltapi.com/merchants/<YOUR MERCHANT ID>/delivery-order
```

If you just want to know the delivery fee:
```
curl -X POST -H "Content-Type: application/json" -H "Authorization: Bearer <YOUR API TOKEN>" -d @example_delivery_fee_request.json https://daas-public-api.development.dev.woltapi.com/merchants/<YOUR MERCHANT ID>/delivery-fee
```


Here's a screen recording where delivery order is made via Postman:

![demo](demo.gif)