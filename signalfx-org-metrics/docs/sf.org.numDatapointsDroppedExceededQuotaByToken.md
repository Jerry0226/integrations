---
title: sf.org.numDatapointsDroppedExceededQuotaByToken
brief: Number of new datapoints not processed by SignalFx; exceeded subscription limit
metric_type: counter
---
### sf.org.numDatapointsDroppedExceededQuotaByToken

One value per token; number of new datapoints you sent to SignalFx but that SignalFx didn't accept, because your organization exceeded its subscription limit.

For more information on how SignalFx processes incoming data when subscription limits are exceeded, see [this FAQ](https://docs.signalfx.com/en/latest/_sidebars-and-includes/dpm-faq.html).

Dimension(s): `orgId, tokenId`

Data Resolution: 1 second

Note that the sum of all the values may be less than the value of `sf.org.numDatapointsDroppedExceededQuota`. For an explanation, see [About ByToken metrics](../readme.md#about-bytoken-metrics).

