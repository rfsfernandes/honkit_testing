//[billing](../../../index.md)/[com.faa.billing.core.api.data](../index.md)/[BillingDataSourceDelegateTestImpl](index.md)/[queryPurchases](query-purchases.md)

# queryPurchases

[androidJvm]\
open override fun [queryPurchases](query-purchases.md)(params: [QueryPurchasesParams](../../com.faa.billing.core.api.data.purchase.query/-query-purchases-params/index.md), purchasesResponseListener: [PurchasesResponseListener](../../com.faa.billing.core.api.data.purchase.query/-purchases-response-listener/index.md))

Returns purchases details for currently owned items bought within your app.

Only non-consumed one-time purchases are returned.

#### Parameters

androidJvm

| | |
|---|---|
| params | Params specific to this query request. |
| purchasesResponseListener | The listener for the result of the query returned asynchronously through the callback with the [BillingResponseCode](../../com.faa.billing.core.api/-billing-response-code/index.md) and the list of Purchase. |
