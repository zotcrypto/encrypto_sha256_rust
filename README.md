![Visitor Badge](https://visitor-badge.laobi.icu/badge?page_id=encrypto-sha256-rust)
![Crates Badge](https://img.shields.io/crates/v/encrypto_sha256_rust)
![Crates Downloads](https://img.shields.io/crates/d/encrypto_sha256_rust)


# About Project
Easy to use Sha256 hash for rust, compatible with all other ZotCrypto projects!

| Icon |             Item              |
|:----:|:-----------------------------:|
|  🥳  |   [**Upcoming**](#Upcoming)   |
|  ⚖️  |    [**License**](#License)    |
|  📝  | [**ChangeLog**](CHANGELOG.md) |

# Usage (rust)

## Implementation
### Cargo
`encrypto_aes =` [latest](https://crates.io/crates/encrypto_sha256)


## RSA


### Documentation will be published soon at our [website](https://www.ssdd.dev/zot/crypto/sha256/rust)

## You can try:

```rust       
        let msg = b"abc";
        let encoded_hex = ZotSha256::encode_to_hex(msg);
        let encoded_b64 = ZotSha256::encode_to_base64(msg);
        let encoded_bytes = ZotSha256::encode_to_bytes(msg);


        assert_eq!(encoded_bytes.clone(), hex::decode(encoded_hex).unwrap());
        assert_eq!(encoded_bytes.clone(), base64::decode(encoded_b64).unwrap());
```

### Please raise an issue [here](https://github.com/zotcrypto/encrypto-aes/issues) if the documentation isn't uploaded in long time

## Upcoming

| Supported Languages | Status              |
|---------------------|---------------------|
| Flutter             | Priority: Less      |
| Java                | Priority: Very high |
| JavaScript          | Priority: High      |


## License

### Click [here](LICENSE.md)
