[@farcaster/js](../README.md) / [Exports](../modules.md) / [protobufs](../modules/protobufs.md) / Metadata

# Class: Metadata

[protobufs](../modules/protobufs.md).Metadata

A class for storing metadata. Keys are normalized to lowercase ASCII.

## Table of contents

### Constructors

- [constructor](protobufs.Metadata.md#constructor)

### Properties

- [\_getCoreRepresentation](protobufs.Metadata.md#_getcorerepresentation)
- [internalRepr](protobufs.Metadata.md#internalrepr)
- [options](protobufs.Metadata.md#options)

### Methods

- [add](protobufs.Metadata.md#add)
- [clone](protobufs.Metadata.md#clone)
- [get](protobufs.Metadata.md#get)
- [getMap](protobufs.Metadata.md#getmap)
- [getOptions](protobufs.Metadata.md#getoptions)
- [merge](protobufs.Metadata.md#merge)
- [remove](protobufs.Metadata.md#remove)
- [set](protobufs.Metadata.md#set)
- [setOptions](protobufs.Metadata.md#setoptions)
- [toHttp2Headers](protobufs.Metadata.md#tohttp2headers)
- [toJSON](protobufs.Metadata.md#tojson)
- [fromHttp2Headers](protobufs.Metadata.md#fromhttp2headers)

## Constructors

### constructor

• **new Metadata**(`options?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `options?` | `MetadataOptions` |

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/metadata.d.ts:19

## Properties

### \_getCoreRepresentation

• `Private` **\_getCoreRepresentation**: `any`

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/metadata.d.ts:74

___

### internalRepr

• `Protected` **internalRepr**: `MetadataObject`

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/metadata.d.ts:17

___

### options

• `Private` **options**: `any`

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/metadata.d.ts:18

## Methods

### add

▸ **add**(`key`, `value`): `void`

Adds the given value for the given key by appending to a list of previous
values associated with that key. Normalizes the key.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `key` | `string` | The key for which a new value should be appended. |
| `value` | `MetadataValue` | The value to add. Must be a buffer if and only if the normalized key ends with '-bin'. |

#### Returns

`void`

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/metadata.d.ts:35

___

### clone

▸ **clone**(): [`Metadata`](protobufs.Metadata.md)

Clones the metadata object.

#### Returns

[`Metadata`](protobufs.Metadata.md)

The newly cloned object.

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/metadata.d.ts:59

___

### get

▸ **get**(`key`): `MetadataValue`[]

Gets a list of all values associated with the key. Normalizes the key.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `key` | `string` | The key whose value should be retrieved. |

#### Returns

`MetadataValue`[]

A list of values associated with the given key.

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/metadata.d.ts:46

___

### getMap

▸ **getMap**(): `Object`

Gets a plain object mapping each key to the first value associated with it.
This reflects the most common way that people will want to see metadata.

#### Returns

`Object`

A key/value mapping of the metadata.

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/metadata.d.ts:52

___

### getOptions

▸ **getOptions**(): `MetadataOptions`

#### Returns

`MetadataOptions`

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/metadata.d.ts:69

___

### merge

▸ **merge**(`other`): `void`

Merges all key-value pairs from a given Metadata object into this one.
If both this object and the given object have values in the same key,
values from the other Metadata object will be appended to this object's
values.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `other` | [`Metadata`](protobufs.Metadata.md) | A Metadata object. |

#### Returns

`void`

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/metadata.d.ts:67

___

### remove

▸ **remove**(`key`): `void`

Removes the given key and any associated values. Normalizes the key.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `key` | `string` | The key whose values should be removed. |

#### Returns

`void`

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/metadata.d.ts:40

___

### set

▸ **set**(`key`, `value`): `void`

Sets the given value for the given key by replacing any other values
associated with that key. Normalizes the key.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `key` | `string` | The key to whose value should be set. |
| `value` | `MetadataValue` | The value to set. Must be a buffer if and only if the normalized key ends with '-bin'. |

#### Returns

`void`

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/metadata.d.ts:27

___

### setOptions

▸ **setOptions**(`options`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `options` | `MetadataOptions` |

#### Returns

`void`

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/metadata.d.ts:68

___

### toHttp2Headers

▸ **toHttp2Headers**(): `OutgoingHttpHeaders`

Creates an OutgoingHttpHeaders object that can be used with the http2 API.

#### Returns

`OutgoingHttpHeaders`

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/metadata.d.ts:73

___

### toJSON

▸ **toJSON**(): `Object`

This modifies the behavior of JSON.stringify to show an object
representation of the metadata map.

#### Returns

`Object`

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/metadata.d.ts:79

___

### fromHttp2Headers

▸ `Static` **fromHttp2Headers**(`headers`): [`Metadata`](protobufs.Metadata.md)

Returns a new Metadata object based fields in a given IncomingHttpHeaders
object.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `headers` | `IncomingHttpHeaders` | An IncomingHttpHeaders object. |

#### Returns

[`Metadata`](protobufs.Metadata.md)

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/metadata.d.ts:87
