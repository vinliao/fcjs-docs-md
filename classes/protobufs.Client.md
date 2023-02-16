[@farcaster/js](../README.md) / [Exports](../modules.md) / [protobufs](../modules/protobufs.md) / Client

# Class: Client

[protobufs](../modules/protobufs.md).Client

A generic gRPC client. Primarily useful as a base class for all generated
clients.

## Hierarchy

- **`Client`**

  ↳ [`HubServiceClient`](../interfaces/protobufs.HubServiceClient.md)

## Table of contents

### Constructors

- [constructor](protobufs.Client.md#constructor)

### Properties

- [[CALL\_INVOCATION\_TRANSFORMER\_SYMBOL]](protobufs.Client.md#[call_invocation_transformer_symbol])
- [[CHANNEL\_SYMBOL]](protobufs.Client.md#[channel_symbol])
- [[INTERCEPTOR\_PROVIDER\_SYMBOL]](protobufs.Client.md#[interceptor_provider_symbol])
- [[INTERCEPTOR\_SYMBOL]](protobufs.Client.md#[interceptor_symbol])
- [checkMetadataAndOptions](protobufs.Client.md#checkmetadataandoptions)
- [checkOptionalUnaryResponseArguments](protobufs.Client.md#checkoptionalunaryresponsearguments)

### Methods

- [close](protobufs.Client.md#close)
- [getChannel](protobufs.Client.md#getchannel)
- [makeBidiStreamRequest](protobufs.Client.md#makebidistreamrequest)
- [makeClientStreamRequest](protobufs.Client.md#makeclientstreamrequest)
- [makeServerStreamRequest](protobufs.Client.md#makeserverstreamrequest)
- [makeUnaryRequest](protobufs.Client.md#makeunaryrequest)
- [waitForReady](protobufs.Client.md#waitforready)

## Constructors

### constructor

• **new Client**(`address`, `credentials`, `options?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `address` | `string` |
| `credentials` | `ChannelCredentials` |
| `options?` | `ClientOptions` |

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/client.d.ts:56

## Properties

### [CALL\_INVOCATION\_TRANSFORMER\_SYMBOL]

• `Private` `Optional` `Readonly` **[CALL\_INVOCATION\_TRANSFORMER\_SYMBOL]**: `any`

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/client.d.ts:55

___

### [CHANNEL\_SYMBOL]

• `Private` `Readonly` **[CHANNEL\_SYMBOL]**: `any`

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/client.d.ts:52

___

### [INTERCEPTOR\_PROVIDER\_SYMBOL]

• `Private` `Readonly` **[INTERCEPTOR\_PROVIDER\_SYMBOL]**: `any`

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/client.d.ts:54

___

### [INTERCEPTOR\_SYMBOL]

• `Private` `Readonly` **[INTERCEPTOR\_SYMBOL]**: `any`

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/client.d.ts:53

___

### checkMetadataAndOptions

• `Private` **checkMetadataAndOptions**: `any`

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/client.d.ts:69

___

### checkOptionalUnaryResponseArguments

• `Private` **checkOptionalUnaryResponseArguments**: `any`

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/client.d.ts:60

## Methods

### close

▸ **close**(): `void`

#### Returns

`void`

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/client.d.ts:57

___

### getChannel

▸ **getChannel**(): `Channel`

#### Returns

`Channel`

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/client.d.ts:58

___

### makeBidiStreamRequest

▸ **makeBidiStreamRequest**<`RequestType`, `ResponseType`\>(`method`, `serialize`, `deserialize`, `metadata`, `options?`): `ClientDuplexStream`<`RequestType`, `ResponseType`\>

#### Type parameters

| Name |
| :------ |
| `RequestType` |
| `ResponseType` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `method` | `string` |
| `serialize` | (`value`: `RequestType`) => `Buffer` |
| `deserialize` | (`value`: `Buffer`) => `ResponseType` |
| `metadata` | [`Metadata`](protobufs.Metadata.md) |
| `options?` | [`CallOptions`](../interfaces/protobufs.CallOptions.md) |

#### Returns

`ClientDuplexStream`<`RequestType`, `ResponseType`\>

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/client.d.ts:72

▸ **makeBidiStreamRequest**<`RequestType`, `ResponseType`\>(`method`, `serialize`, `deserialize`, `options?`): `ClientDuplexStream`<`RequestType`, `ResponseType`\>

#### Type parameters

| Name |
| :------ |
| `RequestType` |
| `ResponseType` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `method` | `string` |
| `serialize` | (`value`: `RequestType`) => `Buffer` |
| `deserialize` | (`value`: `Buffer`) => `ResponseType` |
| `options?` | [`CallOptions`](../interfaces/protobufs.CallOptions.md) |

#### Returns

`ClientDuplexStream`<`RequestType`, `ResponseType`\>

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/client.d.ts:73

___

### makeClientStreamRequest

▸ **makeClientStreamRequest**<`RequestType`, `ResponseType`\>(`method`, `serialize`, `deserialize`, `metadata`, `options`, `callback`): `ClientWritableStream`<`RequestType`\>

#### Type parameters

| Name |
| :------ |
| `RequestType` |
| `ResponseType` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `method` | `string` |
| `serialize` | (`value`: `RequestType`) => `Buffer` |
| `deserialize` | (`value`: `Buffer`) => `ResponseType` |
| `metadata` | [`Metadata`](protobufs.Metadata.md) |
| `options` | [`CallOptions`](../interfaces/protobufs.CallOptions.md) |
| `callback` | `UnaryCallback`<`ResponseType`\> |

#### Returns

`ClientWritableStream`<`RequestType`\>

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/client.d.ts:65

▸ **makeClientStreamRequest**<`RequestType`, `ResponseType`\>(`method`, `serialize`, `deserialize`, `metadata`, `callback`): `ClientWritableStream`<`RequestType`\>

#### Type parameters

| Name |
| :------ |
| `RequestType` |
| `ResponseType` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `method` | `string` |
| `serialize` | (`value`: `RequestType`) => `Buffer` |
| `deserialize` | (`value`: `Buffer`) => `ResponseType` |
| `metadata` | [`Metadata`](protobufs.Metadata.md) |
| `callback` | `UnaryCallback`<`ResponseType`\> |

#### Returns

`ClientWritableStream`<`RequestType`\>

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/client.d.ts:66

▸ **makeClientStreamRequest**<`RequestType`, `ResponseType`\>(`method`, `serialize`, `deserialize`, `options`, `callback`): `ClientWritableStream`<`RequestType`\>

#### Type parameters

| Name |
| :------ |
| `RequestType` |
| `ResponseType` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `method` | `string` |
| `serialize` | (`value`: `RequestType`) => `Buffer` |
| `deserialize` | (`value`: `Buffer`) => `ResponseType` |
| `options` | [`CallOptions`](../interfaces/protobufs.CallOptions.md) |
| `callback` | `UnaryCallback`<`ResponseType`\> |

#### Returns

`ClientWritableStream`<`RequestType`\>

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/client.d.ts:67

▸ **makeClientStreamRequest**<`RequestType`, `ResponseType`\>(`method`, `serialize`, `deserialize`, `callback`): `ClientWritableStream`<`RequestType`\>

#### Type parameters

| Name |
| :------ |
| `RequestType` |
| `ResponseType` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `method` | `string` |
| `serialize` | (`value`: `RequestType`) => `Buffer` |
| `deserialize` | (`value`: `Buffer`) => `ResponseType` |
| `callback` | `UnaryCallback`<`ResponseType`\> |

#### Returns

`ClientWritableStream`<`RequestType`\>

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/client.d.ts:68

___

### makeServerStreamRequest

▸ **makeServerStreamRequest**<`RequestType`, `ResponseType`\>(`method`, `serialize`, `deserialize`, `argument`, `metadata`, `options?`): [`ClientReadableStream`](../modules/protobufs.md#clientreadablestream)<`ResponseType`\>

#### Type parameters

| Name |
| :------ |
| `RequestType` |
| `ResponseType` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `method` | `string` |
| `serialize` | (`value`: `RequestType`) => `Buffer` |
| `deserialize` | (`value`: `Buffer`) => `ResponseType` |
| `argument` | `RequestType` |
| `metadata` | [`Metadata`](protobufs.Metadata.md) |
| `options?` | [`CallOptions`](../interfaces/protobufs.CallOptions.md) |

#### Returns

[`ClientReadableStream`](../modules/protobufs.md#clientreadablestream)<`ResponseType`\>

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/client.d.ts:70

▸ **makeServerStreamRequest**<`RequestType`, `ResponseType`\>(`method`, `serialize`, `deserialize`, `argument`, `options?`): [`ClientReadableStream`](../modules/protobufs.md#clientreadablestream)<`ResponseType`\>

#### Type parameters

| Name |
| :------ |
| `RequestType` |
| `ResponseType` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `method` | `string` |
| `serialize` | (`value`: `RequestType`) => `Buffer` |
| `deserialize` | (`value`: `Buffer`) => `ResponseType` |
| `argument` | `RequestType` |
| `options?` | [`CallOptions`](../interfaces/protobufs.CallOptions.md) |

#### Returns

[`ClientReadableStream`](../modules/protobufs.md#clientreadablestream)<`ResponseType`\>

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/client.d.ts:71

___

### makeUnaryRequest

▸ **makeUnaryRequest**<`RequestType`, `ResponseType`\>(`method`, `serialize`, `deserialize`, `argument`, `metadata`, `options`, `callback`): `SurfaceCall`

#### Type parameters

| Name |
| :------ |
| `RequestType` |
| `ResponseType` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `method` | `string` |
| `serialize` | (`value`: `RequestType`) => `Buffer` |
| `deserialize` | (`value`: `Buffer`) => `ResponseType` |
| `argument` | `RequestType` |
| `metadata` | [`Metadata`](protobufs.Metadata.md) |
| `options` | [`CallOptions`](../interfaces/protobufs.CallOptions.md) |
| `callback` | `UnaryCallback`<`ResponseType`\> |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/client.d.ts:61

▸ **makeUnaryRequest**<`RequestType`, `ResponseType`\>(`method`, `serialize`, `deserialize`, `argument`, `metadata`, `callback`): `SurfaceCall`

#### Type parameters

| Name |
| :------ |
| `RequestType` |
| `ResponseType` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `method` | `string` |
| `serialize` | (`value`: `RequestType`) => `Buffer` |
| `deserialize` | (`value`: `Buffer`) => `ResponseType` |
| `argument` | `RequestType` |
| `metadata` | [`Metadata`](protobufs.Metadata.md) |
| `callback` | `UnaryCallback`<`ResponseType`\> |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/client.d.ts:62

▸ **makeUnaryRequest**<`RequestType`, `ResponseType`\>(`method`, `serialize`, `deserialize`, `argument`, `options`, `callback`): `SurfaceCall`

#### Type parameters

| Name |
| :------ |
| `RequestType` |
| `ResponseType` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `method` | `string` |
| `serialize` | (`value`: `RequestType`) => `Buffer` |
| `deserialize` | (`value`: `Buffer`) => `ResponseType` |
| `argument` | `RequestType` |
| `options` | [`CallOptions`](../interfaces/protobufs.CallOptions.md) |
| `callback` | `UnaryCallback`<`ResponseType`\> |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/client.d.ts:63

▸ **makeUnaryRequest**<`RequestType`, `ResponseType`\>(`method`, `serialize`, `deserialize`, `argument`, `callback`): `SurfaceCall`

#### Type parameters

| Name |
| :------ |
| `RequestType` |
| `ResponseType` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `method` | `string` |
| `serialize` | (`value`: `RequestType`) => `Buffer` |
| `deserialize` | (`value`: `Buffer`) => `ResponseType` |
| `argument` | `RequestType` |
| `callback` | `UnaryCallback`<`ResponseType`\> |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/client.d.ts:64

___

### waitForReady

▸ **waitForReady**(`deadline`, `callback`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `deadline` | `Deadline` |
| `callback` | (`error?`: `Error`) => `void` |

#### Returns

`void`

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/client.d.ts:59
