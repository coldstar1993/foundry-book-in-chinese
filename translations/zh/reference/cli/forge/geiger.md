# forge geiger

检测项目及其依赖项中不安全作弊代码的使用情况

```bash
$ forge geiger --help
用法： forge geiger [OPTIONS] [PATH]...

参数：
  [PATH]...
          Paths to files or directories to detect

选项：
      --root <PATH>
          The project's root path.
          
          By default root of the Git repository, if in one, or the current working directory.

      --check
          Run in "check" mode.
          
          The exit code of the program will be the number of unsafe cheatcodes found.

      --ignore <PATH>...
          Globs to ignore

      --full
          Print a report of all files, even if no unsafe functions are found

  -h, --help
          Print help (see a summary with '-h')
```