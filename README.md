1. Install

```shell
# npm 10.9.0
npm install
```

2. List cross-spawn dependency

```shell
npm ls cross-spawn
# ├─┬ @nestjs/cli@10.4.7
# │ └─┬ glob@10.4.2
# │   └─┬ foreground-child@3.3.0
# │     └── cross-spawn@7.0.6 deduped
# ├─┬ eslint@9.15.0
# │ └── cross-spawn@7.0.6
# └─┬ jest@29.7.0
#   └─┬ @jest/core@29.7.0
#     └─┬ jest-changed-files@29.7.0
#       └─┬ execa@5.1.1
#         └── cross-spawn@7.0.6 deduped
```

3. List cross-spawn dependency (prod only)

```shell
npm ls --prod cross-spawn
└─┬ typeorm@0.3.20
  └─┬ glob@10.4.5
    └─┬ foreground-child@3.3.0
      └── cross-spawn@7.0.6
```
