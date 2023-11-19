# NKU-Marp-Themes
本仓库存放适用于南开大学的Marp主题，基本改编自相关的Marp主题，每个部分会给到链接。
## 配置环境
对于Marp的初学者，可以直接在 vscode 中下载 marp-for-vscode 使用，需要打开 `enable HTML` 选项（对 Obsidian 的 Marp-Slides 插件也同样），否则无法渲染源文件中的HTML标签，例如以下代码：

```html
<div class = ldiv>
  使用五五分时，一个 div 中支持 markdown 语法，因此可以直接打想要的内容：

- 行内数学公式: $\lim_{a\to 0} a^2=0$ ，行间数学公式：
$$
\int _a^b x \mathrm{d}y =a+bc
$$

- 引用：
  > 列表内引用

- 代码块：见右侧，如果需要增加支持的语言，vscode的扩展设置中有相关内容。

</div>
```


----
## NKU-Beamer
本主题改编自 Beam 主题：<a href="https://github.com/rnd195/my-marp-themes">Beam Theme</a>，效果类似Beamer，但比较简单，适合短平快的Presentation.

### 相较于 Beam 主题的变化
- 主题色改为 NKU 相关的颜色主题，例如经典的南开紫；
- 新增目录页 `contents` ，并定制为有序列表方案；
- 新增致谢页 `final` ，为简洁起见仅更改二级标题。若二级标题使用字体 `Edwardian Script ITC` 在你的设备上没有，可以直接在CSS文件中更改；
- 字体增加中文字体；
- 底部栏更改颜色及内容；

### 效果预览
<img width="459" alt="image" src="https://github.com/xiong-ZH-zq/NKU-Marp/assets/68729283/d3d1bd04-e305-4f6c-bfee-40e9a367ed4a">
<img width="457" alt="image" src="https://github.com/xiong-ZH-zq/NKU-Marp/assets/68729283/06efc55d-cb1d-4f94-a148-ccf44d036cd3">
<img width="461" alt="image" src="https://github.com/xiong-ZH-zq/NKU-Marp/assets/68729283/d0e69072-dc5a-4ec0-bb48-c946bb10f60d">





----

## NKU-Marp

本主题改编自Awesome-Marp主题：<a href="https://github.com/favourhong/Awesome-Marp">Awesome-Marp主题</a> ，仅供学习交流使用。在此感谢原作者。

### 相较于 Awesome-Marp 的变化

- 主题色改为南开紫；
- 校徽校训等内容改为南开大学的校徽与校训；
- 示例文件给出校徽图片，可直接套用；
- 给出数学公式的示例；

### 后续更新
后续可能会根据具体需求进行更改，并改编更多友校的Marp主题。
