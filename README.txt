index.html 是完全自包含的单文件，不依赖任何本地资源。
唯一的联网请求是 Google Fonts（拉不到会自动回退到系统字体，不影响使用）。

改内容请改 lishui-taizhou.html（源文件），然后跑 build_share.py 重新生成这个文件。
别直接改 index.html，会被覆盖。
