# 使用 font-spider 提取字体
1. 在终端执行 `npm install` 安装依赖；
2. 将 `.ttf` 格式的字体文件命名为 `font.ttf`，放入项目 `font` 目录中，覆盖掉原本的 `font.ttf`；
3. 在 `index.html` 的 `<dev />` 标签里写上要从字体包中提取的字；
4. 在终端执行 `npm run start`，新生成的字体包会出现在根目录中，覆盖掉旧的字体包，除 `ttf` 外的其它格式也会自动生成。