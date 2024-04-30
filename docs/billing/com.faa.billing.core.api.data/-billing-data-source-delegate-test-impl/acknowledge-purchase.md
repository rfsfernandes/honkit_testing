//[billing](../../../index.md)/[com.faa.billing.core.api.data](../index.md)/[BillingDataSourceDelegateTestImpl](index.md)/[acknowledgePurchase](acknowledge-purchase.md)

# acknowledgePurchase

[androidJvm]\
open override fun [acknowledgePurchase](acknowledge-purchase.md)(params: [AcknowledgePurchaseParams](../../com.faa.billing.core.api/-acknowledge-purchase-params/index.md), listener: [AcknowledgePurchaseResponseListener](../../com.faa.billing.core.api/-acknowledge-purchase-response-listener/index.md))

Acknowledges in-app purchases.

Developers are required to acknowledge that they have granted entitlement for all in-app purchases for their application.

Warning! All purchases require acknowledgement. Failure to acknowledge a purchase will result in that purchase being refunded. For one-time products ensure you are explicitly acknowledging the purchase via this method. [acknowledgePurchase(AcknowledgePurchaseParams, AcknowledgePurchaseResponseListener)](acknowledge-purchase.md)

#### Parameters

androidJvm

| | |
|---|---|
| params | Params specific to this acknowledge purchase request. |
| listener | The listener for the result of the acknowledge operation returned asynchronously through the callback with the [BillingResponseCode](../../com.faa.billing.core.api/-billing-response-code/index.md). |
