//[billing](../../../index.md)/[com.faa.billing.core.api.data](../index.md)/[BillingDataSourceDelegateTestImpl](index.md)/[consumePurchase](consume-purchase.md)

# consumePurchase

[androidJvm]\
open override fun [consumePurchase](consume-purchase.md)(params: [ConsumePurchaseParams](../../com.faa.billing.core.api/-consume-purchase-params/index.md), consumePurchaseResponseListener: [ConsumePurchaseResponseListener](../../com.faa.billing.core.api/-consume-purchase-response-listener/index.md))

Consumes a given in-app product. Consuming can only be done on an item that's owned, and as a result of consumption, the user will no longer own it.

Consumption is done asynchronously and the listener receives the callback specified upon completion.

Warning! All purchases require acknowledgement. Failure to acknowledge a purchase will result in that purchase being refunded. For one-time products ensure you are using this method which acts as an implicit acknowledgement or you can explicitly acknowledge the purchase via [acknowledgePurchase](acknowledge-purchase.md). For subscriptions use [acknowledgePurchase](acknowledge-purchase.md).

#### Parameters

androidJvm

| | |
|---|---|
| params | Params specific to consuming a purchase. |
| consumePurchaseResponseListener | The listener for the result of the consume operation returned asynchronously through the callback with the purchase token and BillingResponseCode. |
