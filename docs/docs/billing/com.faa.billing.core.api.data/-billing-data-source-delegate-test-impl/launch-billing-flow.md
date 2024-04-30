//[billing](../../../index.md)/[com.faa.billing.core.api.data](../index.md)/[BillingDataSourceDelegateTestImpl](index.md)/[launchBillingFlow](launch-billing-flow.md)

# launchBillingFlow

[androidJvm]\
open override fun [launchBillingFlow](launch-billing-flow.md)(params: [BillingFlowParams](../../com.faa.billing.core.api/-billing-flow-params/index.md)): [BillingResponseCode](../../com.faa.billing.core.api/-billing-response-code/index.md)

Initiates the billing flow for an in-app purchase. It will show FAA's or the current OEM's purchase screen. The result will be delivered via the PurchasesUpdatedListener interface implementation set by BillingClientSettings.Builder.setPurchasesUpdatedListener

#### Return

[BillingResponseCode](../../com.faa.billing.core.api/-billing-response-code/index.md) The result of the launch billing flow operation. [BillingResponseCode.ITEM_ALREADY_OWNED](../../com.faa.billing.core.api/-billing-response-code/-i-t-e-m_-a-l-r-e-a-d-y_-o-w-n-e-d/index.md) if the user already owns the item being purchased, [BillingResponseCode.ITEM_UNAVAILABLE](../../com.faa.billing.core.api/-billing-response-code/-i-t-e-m_-u-n-a-v-a-i-l-a-b-l-e/index.md) if the item is not available to be purchased.

#### Parameters

androidJvm

| | |
|---|---|
| params | [BillingFlowParams](../../com.faa.billing.core.api/-billing-flow-params/index.md) Params specific to the launch billing flow request. |
