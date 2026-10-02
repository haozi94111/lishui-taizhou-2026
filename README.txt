index.html 是完全自包含的单文件，不依赖任何本地资源（五张图都是内联 SVG）。
唯一的联网请求是 Google Fonts（拉不到会自动回退到系统字体，不影响使用）。

页面上方有「行程」/「其他住宿参考」两个页签，会记住你上次停在哪一个。
打印 / 存 PDF 时两个页签的内容都会出来。

改内容请改 lishui-taizhou.html（源文件），然后依次跑
make_pdf.py / build_share.py / sync_maps.py 重新生成。
别直接改 index.html，会被覆盖。
