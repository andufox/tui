# React + TypeScript + Vite + shadcn/ui

This is a template for a new Vite project with React, TypeScript, and shadcn/ui.

## Adding components

To add components to your app, run the following command:

```bash
npx shadcn@latest add button
```

This will place the ui components in the `src/components` directory.

## Using components

To use the components in your app, import them as follows:

```tsx
import { Button } from "@/components/ui/button"
```


## GitHub Action
git tag v0.1.1
git push origin v0.1.1


# 1. 添加所有修改过的文件（包括修复后的 release.yml）
git add .

# 2. 提交代码（请务必加上双引号括住你的提交说明）
git commit -m "v0.1.3"

# 3. 将最新的修复代码推送到 GitHub 的 master 分支
git push origin master

# 4. 在本地当前的最新提交上打上 v0.1.3 的版本标签
git tag v0.1.3

# 5. 将该版本标签独立推送到 GitHub（这将立刻触发自动化跨平台打包）
git push origin v0.1.3
