# cast wallet vanity

生成虚拟地址

```bash
$ cast wallet vanity --help
用法： cast wallet vanity [OPTIONS]

选项：
      --starts-with <HEX>
          Prefix for the vanity address

      --ends-with <HEX>
          Suffix for the vanity address

      --nonce <NONCE>
          Generate a vanity contract address created by the generated keypair with the specified nonce

      --save-path <PATH>
          Path to save the generated vanity contract address to.
          
          If provided, the generated vanity addresses will appended to a JSON array in the specified file.

  -h, --help
          Print help (see a summary with '-h')
```