# data-encoder

The project is being finalized, plans include adding more algorithms

Developed by Nikita Derevyankin (Dronikon) (c) 2022

## Installation

```bash
$ pip install data-encoder
```

## Examples of How To Use

Advanced Encryption Standard

```python
from data-encoder import Encoder

encoder = Encoder()
message = "test"
key = "12345"
en = encoder.aes_encrypt(message, key)
de = encoder.aes_decrypt(message, key)
print("Encrypted data: ", en)
print("Decrypted data: ", de)
```

Blowfish

```python
from data-encoder import Encoder

encoder = Encoder()
message = "test"
key = "12345"
en = encoder.blowfish_encrypt(message, key)
de = encoder.blowfish_encrypt(message, key)
print("Encrypted data: ", en)
print("Decrypted data: ", de)
```
https://pypi.org/project/data-encoder/