# Interface: JWTDecryptGetKey

[💗 Help the project](https://github.com/sponsors/panva)

## Callable

### JWTDecryptGetKey

▸ **JWTDecryptGetKey**(`protectedHeader`, `token`): `Uint8Array` \| [`KeyLike`](../types/types.KeyLike.md) \| `Promise`<`Uint8Array` \| [`KeyLike`](../types/types.KeyLike.md)\>

Interface for JWT Decryption dynamic key resolution. No token components have been verified at
the time of this function call.

#### Parameters

| Name | Type |
| :------ | :------ |
| `protectedHeader` | [`CompactJWEHeaderParameters`](types.CompactJWEHeaderParameters.md) |
| `token` | [`FlattenedJWE`](types.FlattenedJWE.md) |

#### Returns

`Uint8Array` \| [`KeyLike`](../types/types.KeyLike.md) \| `Promise`<`Uint8Array` \| [`KeyLike`](../types/types.KeyLike.md)\>
