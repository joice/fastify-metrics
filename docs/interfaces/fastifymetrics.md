[fastify-metrics](../README.md) › [FastifyMetrics](fastifymetrics.md)

# Interface: FastifyMetrics

## Hierarchy

* **FastifyMetrics**

## Indexable

* \[ **key**: *string*\]: unknown

Additional objects to store your metrics, registries, etc.

## Index

### Properties

* [client](fastifymetrics.md#client)

### Methods

* [clearRegister](fastifymetrics.md#clearregister)

## Properties

###  client

• **client**: *typeof promClient*

*Defined in [src/plugin.ts:27](https://github.com/SkeLLLa/fastify-metrics/blob/d193ecd/src/plugin.ts#L27)*

Prom-client

## Methods

###  clearRegister

▸ **clearRegister**(): *void*

*Defined in [src/plugin.ts:31](https://github.com/SkeLLLa/fastify-metrics/blob/d193ecd/src/plugin.ts#L31)*

Expose register clear function if register was provided

**Returns:** *void*
