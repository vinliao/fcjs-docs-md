[@farcaster/js](../README.md) / [Exports](../modules.md) / Eip712Signer

# Class: Eip712Signer

## Hierarchy

- `Eip712Signer`

  ↳ **`Eip712Signer`**

## Table of contents

### Constructors

- [constructor](Eip712Signer.md#constructor)

### Properties

- [scheme](Eip712Signer.md#scheme)
- [signerKey](Eip712Signer.md#signerkey)
- [signerKeyHex](Eip712Signer.md#signerkeyhex)

### Methods

- [signMessageHash](Eip712Signer.md#signmessagehash)
- [signMessageHashHex](Eip712Signer.md#signmessagehashhex)
- [signVerificationEthAddressClaim](Eip712Signer.md#signverificationethaddressclaim)
- [signVerificationEthAddressClaimHex](Eip712Signer.md#signverificationethaddressclaimhex)
- [fromSigner](Eip712Signer.md#fromsigner)

## Constructors

### constructor

• **new Eip712Signer**(`typedDataSigner`, `address`, `signerKey`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `typedDataSigner` | `TypedDataSigner` |
| `address` | `string` |
| `signerKey` | `Uint8Array` |

#### Inherited from

BaseEip712Signer.constructor

#### Defined in

node_modules/.pnpm/@farcaster+utils@0.2.3/node_modules/@farcaster/utils/dist/index.d.ts:153

## Properties

### scheme

• `Readonly` **scheme**: [`SIGNATURE_SCHEME_EIP712`](../enums/protobufs.SignatureScheme.md#signature_scheme_eip712) = `SignatureScheme.SIGNATURE_SCHEME_EIP712`

#### Inherited from

BaseEip712Signer.scheme

#### Defined in

node_modules/.pnpm/@farcaster+utils@0.2.3/node_modules/@farcaster/utils/dist/index.d.ts:147

___

### signerKey

• `Readonly` **signerKey**: `Uint8Array`

20-byte wallet address

#### Inherited from

BaseEip712Signer.signerKey

#### Defined in

node_modules/.pnpm/@farcaster+utils@0.2.3/node_modules/@farcaster/utils/dist/index.d.ts:149

___

### signerKeyHex

• `Readonly` **signerKeyHex**: `string`

#### Inherited from

BaseEip712Signer.signerKeyHex

#### Defined in

node_modules/.pnpm/@farcaster+utils@0.2.3/node_modules/@farcaster/utils/dist/index.d.ts:150

## Methods

### signMessageHash

▸ **signMessageHash**(`hash`): `HubAsyncResult`<`Uint8Array`\>

generates 256-bit signature from an Ethereum address

#### Parameters

| Name | Type |
| :------ | :------ |
| `hash` | `Uint8Array` |

#### Returns

`HubAsyncResult`<`Uint8Array`\>

#### Inherited from

BaseEip712Signer.signMessageHash

#### Defined in

node_modules/.pnpm/@farcaster+utils@0.2.3/node_modules/@farcaster/utils/dist/index.d.ts:155

___

### signMessageHashHex

▸ **signMessageHashHex**(`hash`): `HubAsyncResult`<`string`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `hash` | `string` |

#### Returns

`HubAsyncResult`<`string`\>

#### Defined in

[src/signers.ts:20](https://github.com/farcasterxyz/hubble/blob/57fee6a/packages/js/src/signers.ts#L20)

___

### signVerificationEthAddressClaim

▸ **signVerificationEthAddressClaim**(`claim`): `HubAsyncResult`<`Uint8Array`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `claim` | [`VerificationEthAddressClaim`](../modules/types.md#verificationethaddressclaim) |

#### Returns

`HubAsyncResult`<`Uint8Array`\>

#### Inherited from

BaseEip712Signer.signVerificationEthAddressClaim

#### Defined in

node_modules/.pnpm/@farcaster+utils@0.2.3/node_modules/@farcaster/utils/dist/index.d.ts:156

___

### signVerificationEthAddressClaimHex

▸ **signVerificationEthAddressClaimHex**(`claim`): `HubAsyncResult`<`string`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `claim` | [`VerificationEthAddressClaim`](../modules/types.md#verificationethaddressclaim) |

#### Returns

`HubAsyncResult`<`string`\>

#### Defined in

[src/signers.ts:31](https://github.com/farcasterxyz/hubble/blob/57fee6a/packages/js/src/signers.ts#L31)

___

### fromSigner

▸ `Static` **fromSigner**(`typedDataSigner`, `address`): `HubResult`<[`Eip712Signer`](Eip712Signer.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `typedDataSigner` | `TypedDataSigner` |
| `address` | `string` |

#### Returns

`HubResult`<[`Eip712Signer`](Eip712Signer.md)\>

#### Overrides

BaseEip712Signer.fromSigner

#### Defined in

[src/signers.ts:15](https://github.com/farcasterxyz/hubble/blob/57fee6a/packages/js/src/signers.ts#L15)
