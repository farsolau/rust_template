### 1.安装 cargo generate

cargo generate 是一个用于生成项目模板的工具。它可以使用已有的 gitee repo 作为模版生成新的项目。

```bash
cargo install cargo-generate
```

以后新的项目会使用`farso/rust_template`模版生成基本的代码:

```bash
cargo generate farso/rust_template
```

### 2.安装 pre-commit

pre-commit 是一个代码检查工具，可以在提交代码前进行代码检查。

```bash
pip install pre-commit
```

安装成功后运行 `pre-commit install` 即可。

### 3.安装 Cargo deny

Cargo deny 是一个 Cargo 插件，可以用于检查依赖的安全性

```bash
cargo install --locked cargo-deny
```

### 4.安装 typos

typos 是一个拼写检查工具。

```bash
cargo install typos-cli
```

### 5.安装 git cliff

git cliff 是一个生成 changelog 的工具。

```bash
cargo install git-cliff
```

### 6.安装 cargo nextest

cargo nextest 是一个 Rust 增强测试工具。

```bash
cargo install cargo-nextest --locked
```
