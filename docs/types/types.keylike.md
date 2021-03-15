# Type alias: KeyLike

[types](../modules/types.md).KeyLike

Ƭ **KeyLike**: KeyObject \| CryptoKey \| Uint8Array

KeyLike are platform-specific references to keying material.

- [KeyObject](https://nodejs.org/api/crypto.html#crypto_class_keyobject) instances come from
node's [crypto module](https://nodejs.org/api/crypto.html) (see crypto.generateKeyPair,
crypto.createPublicKey, crypto.createPrivateKey, crypto.createSecretKey).
- [CryptoKey](https://www.w3.org/TR/WebCryptoAPI) instances come from
[Web Cryptography API](https://www.w3.org/TR/WebCryptoAPI) (see SubtleCrypto.importKey,
SubtleCrypto.generateKey, SubtleCrypto.deriveKey, SubtleCrypto.unwrapKey).
- [Uint8Array](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Uint8Array)
is used exclusively for symmetric secret representations, a CryptoKey or KeyObject is
preferred, but in Web Crypto API this isn't an option for some algorithms.

Defined in: [types.d.ts:96](https://github.com/panva/jose/blob/v3.9.0/src/types.d.ts#L96)
