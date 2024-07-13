# Caesar-Cipher-Scripts
This project contains three scripts for working with Caesar Ciphers. These scripts allow you to generate the necessary patterns, encode text using the Caesar Cipher, and decode text by testing all possible shifts.


## Scripts

### 1. `create_pattern`
Generates a pattern used for Caesar Cipher translation.

**Usage:**
```sh
./create_pattern -k <shift> [-u]

```

- -k <shift>: Specifies the shift amount.
- -u: Indicates that the pattern should be for uppercase letters.



### 2. `caesar`
Encodes input text using the Caesar Cipher with a specified shift.

**Usage:**
```sh
./caesar -k <shift> [-u] < input_file

```

- -k <shift>: Specifies the shift amount.
- -u: Indicates that the encoding should be for uppercase letters.
- < input_file>: Input text file to be encoded.


### 3. `decode`
Decodes input text by attempting all possible Caesar Cipher shifts (1 through 25).

**Usage:**
```sh
./decode <input_file>


```

- < input_file>: Input text file to be decoded.



