# forge fmt

格式化 Solidity 源文件

```bash
$ forge fmt --help
```

```txt
用法： forge fmt [OPTIONS] [PATH]...

参数：
  [PATH]...
          Path to the file, directory or '-' to read from stdin

选项：
      --root <PATH>
          The project's root path.
          
          By default root of the Git repository, if in one, or the current working directory.

      --check
          Run in 'check' mode.
          
          Exits with 0 if input is formatted correctly. Exits with 1 if formatting is required.

  -r, --raw
          In 'check' and stdin modes, outputs raw formatted code instead of the diff

  -h, --help
          Print help (see a summary with '-h')
```