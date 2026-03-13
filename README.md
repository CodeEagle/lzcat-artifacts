# lzcat-artifacts

集中存放 `lzcat-trigger` 产出的 `.lpk` 制品和 `build-report.json`。

## 内容

- 每个 release 对应一个目标仓库的一次构建结果
- release asset 至少包含：
  - `.lpk`
  - `build-report.json`

## 命名规则

- release tag: `<owner>--<repo>-v<build_version>`
- release title: `<owner>/<repo> v<build_version>`

## 下载页面

仓库启用 GitHub Pages 后，可通过 `docs/index.html` 浏览并下载所有制品。
