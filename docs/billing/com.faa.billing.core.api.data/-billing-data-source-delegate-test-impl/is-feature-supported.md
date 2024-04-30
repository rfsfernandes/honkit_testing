//[billing](../../../index.md)/[com.faa.billing.core.api.data](../index.md)/[BillingDataSourceDelegateTestImpl](index.md)/[isFeatureSupported](is-feature-supported.md)

# isFeatureSupported

[androidJvm]\
open override fun [isFeatureSupported](is-feature-supported.md)(featureType: [FeatureType](../../com.faa.billing.core.api/-feature-type/index.md)): [BillingResponseCode](../../com.faa.billing.core.api/-billing-response-code/index.md)

Checks if the specified feature type is supported for the given package.

#### Return

The corresponding [BillingResponseCode](../../com.faa.billing.core.api/-billing-response-code/index.md) indicating the result of the feature support check. If the billing service call is successful and the feature is supported, [BillingResponseCode.OK](../../com.faa.billing.core.api/-billing-response-code/-o-k/index.md) is returned. If the billing service call is successful and the feature is NOT supported, [BillingResponseCode.FEATURE_NOT_SUPPORTED](../../com.faa.billing.core.api/-billing-response-code/-f-e-a-t-u-r-e_-n-o-t_-s-u-p-p-o-r-t-e-d/index.md). If the billing service is not available or a RemoteException is thrown, [BillingResponseCode.SERVICE_UNAVAILABLE](../../com.faa.billing.core.api/-billing-response-code/-s-e-r-v-i-c-e_-u-n-a-v-a-i-l-a-b-l-e/index.md) is returned. If an error occurs during the process, [BillingResponseCode.ERROR](../../com.faa.billing.core.api/-billing-response-code/-e-r-r-o-r/index.md) is returned.

#### Parameters

androidJvm

| | |
|---|---|
| featureType | [FeatureType](../../com.faa.billing.core.api/-feature-type/index.md) The feature type to be validated. |
