//[billing](../../../index.md)/[com.faa.billing.core.api.data](../index.md)/[BillingDataSourceDelegateTestImpl](index.md)

# BillingDataSourceDelegateTestImpl

[androidJvm]\
class [BillingDataSourceDelegateTestImpl](index.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html)) : BillingDataSourceDelegate

Created by Nuno Palma on 22/02/2024.

## Constructors

| | |
|---|---|
| [BillingDataSourceDelegateTestImpl](-billing-data-source-delegate-test-impl.md) | [androidJvm]<br>constructor(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html)) |

## Functions

| Name | Summary |
|---|---|
| [acknowledgePurchase](acknowledge-purchase.md) | [androidJvm]<br>open override fun [acknowledgePurchase](acknowledge-purchase.md)(params: [AcknowledgePurchaseParams](../../com.faa.billing.core.api/-acknowledge-purchase-params/index.md), listener: [AcknowledgePurchaseResponseListener](../../com.faa.billing.core.api/-acknowledge-purchase-response-listener/index.md))<br>Acknowledges in-app purchases. |
| [consumePurchase](consume-purchase.md) | [androidJvm]<br>open override fun [consumePurchase](consume-purchase.md)(params: [ConsumePurchaseParams](../../com.faa.billing.core.api/-consume-purchase-params/index.md), consumePurchaseResponseListener: [ConsumePurchaseResponseListener](../../com.faa.billing.core.api/-consume-purchase-response-listener/index.md))<br>Consumes a given in-app product. Consuming can only be done on an item that's owned, and as a result of consumption, the user will no longer own it. |
| [isFeatureSupported](is-feature-supported.md) | [androidJvm]<br>open override fun [isFeatureSupported](is-feature-supported.md)(featureType: [FeatureType](../../com.faa.billing.core.api/-feature-type/index.md)): [BillingResponseCode](../../com.faa.billing.core.api/-billing-response-code/index.md)<br>Checks if the specified feature type is supported for the given package. |
| [launchBillingFlow](launch-billing-flow.md) | [androidJvm]<br>open override fun [launchBillingFlow](launch-billing-flow.md)(params: [BillingFlowParams](../../com.faa.billing.core.api/-billing-flow-params/index.md)): [BillingResponseCode](../../com.faa.billing.core.api/-billing-response-code/index.md)<br>Initiates the billing flow for an in-app purchase. It will show FAA's or the current OEM's purchase screen. The result will be delivered via the PurchasesUpdatedListener interface implementation set by BillingClientSettings.Builder.setPurchasesUpdatedListener |
| [queryProductDetails](query-product-details.md) | [androidJvm]<br>open override fun [queryProductDetails](query-product-details.md)(params: [QueryProductDetailsParams](../../com.faa.billing.core.api/-query-product-details-params/index.md), listener: [ProductDetailsResponseListener](../../com.faa.billing.core.api/-product-details-response-listener/index.md))<br>Performs a network query the details of products available for sale in your app. |
| [queryPurchases](query-purchases.md) | [androidJvm]<br>open override fun [queryPurchases](query-purchases.md)(params: [QueryPurchasesParams](../../com.faa.billing.core.api.data.purchase.query/-query-purchases-params/index.md), purchasesResponseListener: [PurchasesResponseListener](../../com.faa.billing.core.api.data.purchase.query/-purchases-response-listener/index.md))<br>Returns purchases details for currently owned items bought within your app. |
