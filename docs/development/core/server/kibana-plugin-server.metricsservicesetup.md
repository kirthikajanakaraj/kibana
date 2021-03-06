<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [kibana-plugin-server](./kibana-plugin-server.md) &gt; [MetricsServiceSetup](./kibana-plugin-server.metricsservicesetup.md)

## MetricsServiceSetup interface

APIs to retrieves metrics gathered and exposed by the core platform.

<b>Signature:</b>

```typescript
export interface MetricsServiceSetup 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [getOpsMetrics$](./kibana-plugin-server.metricsservicesetup.getopsmetrics_.md) | <code>() =&gt; Observable&lt;OpsMetrics&gt;</code> | Retrieve an observable emitting the [OpsMetrics](./kibana-plugin-server.opsmetrics.md) gathered. The observable will emit an initial value during core's <code>start</code> phase, and a new value every fixed interval of time, based on the <code>opts.interval</code> configuration property. |

