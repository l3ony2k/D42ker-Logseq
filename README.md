# D42ker Logseq Theme

(logseq-default-dark-0-saturation)

Default [Logseq](https://logseq.com/) dark theme with 0 saturation background and some other tweaks.

Most of the enhanced features were inspired by great guys on [Logseq Discord server](https://discord.gg/KpN4eHY).

## Modifications

All these changes are based on default dark theme of Logseq.

- 0 saturation background (#121212)
- Red accent color
  - link
  - highlight (mark)
  - searchbar
  - checkbox
  - …
- Highlight current focused block (Thanks to @cannibalox, @pengx17)
- Added 🔴 🟡 🟢 to `[#A]` `[#B]` `[#C]`, respectively (Thanks to @pengx17)
- Colorful highlight (from [Yin and Yang Obsidian theme](https://github.com/chetachiezikeuzor/Yin-and-Yang-Theme))
  - thanks to @bettyzhang ([Discord Link](https://discord.com/channels/725182569297215569/756886540038438992/850029658351468574))
    
  - <details>
    <summary>Usage</summary>
    
      - add following code to your `config.edn`
        
        ```
        ["Blue Highlighter" [[:editor/input "<mark class='blue'></mark>" {:backward-pos 7}]]]
        ["Green Highlighter" [[:editor/input "<mark class='green'></mark>" {:backward-pos 7}]]]
        ["Gray Highlighter" [[:edior/input "<mark class='gray'></mark>" {:backward-pos 7}]]]
        ["Grey Highlighter" [[:editor/input "<mark class='grey'></mark>" {:backward-pos 7}]]]
        ["Orange Highlighter" [[:editor/input "<mark class='orange'></mark>" {:backward-pos 7}]]]
        ["Pink Highlighter" [[:editor/input "<mark class='pink'></mark>" {:backward-pos 7}]]]
        ["Red Highlighter" [[:editor/input "<mark class='red'></mark>" {:backward-pos 7}]]]
        ["Yellow Highlighter" [[:editor/input "<mark class='yellow'></mark>" {:backward-pos 7}]]]
        ["Purple Highlighter" [[:editor/input "<mark class='purple'></mark>" {:backward-pos 7}]]]
        ```
        
      - your `config.edn` should look like this
        
        ![image](https://user-images.githubusercontent.com/58762081/121205590-60dca300-c8aa-11eb-99c4-63a2ecc05976.png)
        
      - use `/blue` then select `Blue Highlighter` to apply
        
        ![image](https://user-images.githubusercontent.com/58762081/121207236-b5345280-c8ab-11eb-9d35-5c37469d659e.png)
        
    </details>

- Lightened table background
- ~~Fixed some CodeMirror issues~~
- Thin outline around block editor text area (Thanks to @sabre23t [Discord](https://discord.com/channels/725182569297215569/752845138148982877/857463855948103701))
- Red accent color in light theme
  - I seldom use light theme, so it might be buggy 😢

## How to use

Copy and paste the contents of `custom.css` file into your `logseq/custom.css` file.

Or

Add the following line to your `logseq/custom.css` file.

```css
@import url('https://cdn.jsdelivr.net/gh/LeonWong0609/logseq-default-dark-0-saturation@main/custom.css');
```

***

默认的 [Logseq](https://logseq.com/) 深色主题，0 饱和度的背景和其他一些调整。

大多数增强功能的灵感都来自 [Logseq Discord服务器](https://discord.gg/KpN4eHY) 的朋友们。

## 修改

所有的修改都基于 Logseq 的默认深色主题

- 0 饱和度主背景 (#121212)
- 红色作为强调色
  - 链接
  - 默认高亮
  - 搜索框
  - 待办列表
  - …
- 为当前聚焦的 block 增加高亮 (Thanks to @cannibalox, @pengx17)
- 在 `[#A]` `[#B]` `[#C]` 优先级的任务前分别添加 🔴 🟡 🟢 (Thanks to @pengx17)
- 多彩高亮 (from [Yin and Yang Obsidian theme](https://github.com/chetachiezikeuzor/Yin-and-Yang-Theme))
  - thanks to @bettyzhang ([Discord Link](https://discord.com/channels/725182569297215569/756886540038438992/850029658351468574))
    
  - <details>
    <summary>使用方法</summary>
    
      - 将以下代码加入到 `config.edn` 中
        
        ```
        ["Blue Highlighter" [[:editor/input "<mark class='blue'></mark>" {:backward-pos 7}]]]
        ["Green Highlighter" [[:editor/input "<mark class='green'></mark>" {:backward-pos 7}]]]
        ["Gray Highlighter" [[:edior/input "<mark class='gray'></mark>" {:backward-pos 7}]]]
        ["Grey Highlighter" [[:editor/input "<mark class='grey'></mark>" {:backward-pos 7}]]]
        ["Orange Highlighter" [[:editor/input "<mark class='orange'></mark>" {:backward-pos 7}]]]
        ["Pink Highlighter" [[:editor/input "<mark class='pink'></mark>" {:backward-pos 7}]]]
        ["Red Highlighter" [[:editor/input "<mark class='red'></mark>" {:backward-pos 7}]]]
        ["Yellow Highlighter" [[:editor/input "<mark class='yellow'></mark>" {:backward-pos 7}]]]
        ["Purple Highlighter" [[:editor/input "<mark class='purple'></mark>" {:backward-pos 7}]]]
        ```
        
      - 添加完成后 `config.edn` 应该看起来像这样
        
        ![image](https://user-images.githubusercontent.com/58762081/121205590-60dca300-c8aa-11eb-99c4-63a2ecc05976.png)
        
      - 编辑模式下使用 `/blue` 命令后，选中 `Blue Highlighter` 来应用
        
        ![image](https://user-images.githubusercontent.com/58762081/121207236-b5345280-c8ab-11eb-9d35-5c37469d659e.png)
        
    </details>

- 提亮表格背景
- ~~调整一些代码显示~~
- 为当前处于编辑状态的 block 增加边框 (Thanks to @sabre23t [Discord](https://discord.com/channels/725182569297215569/752845138148982877/857463855948103701))
- 修改浅色主题的强调色为红色
  - 我很少使用浅色主题，所以浅色主题不如深色主题完善 😢

## 使用方法

将 `custom.css` 文件中的内容复制粘贴到 `logseq/custom.css` 文件中。

或

在 `logseq/custom.css` 文件中添加下面这行代码：

```css
@import url('https://cdn.jsdelivr.net/gh/LeonWong0609/logseq-default-dark-0-saturation@main/custom.css');
```

***

## Screenshots / 截屏

![overview](https://user-images.githubusercontent.com/58762081/123148201-86fd6800-d492-11eb-9550-e3d4a442d1fc.png)

👆 overview / 总览

![table](https://user-images.githubusercontent.com/58762081/123220264-5ce28f00-d500-11eb-9744-edda002f2910.png)

👆 table / 表格

![highlights](https://user-images.githubusercontent.com/58762081/123220405-83a0c580-d500-11eb-8cad-e8dc011b1a13.png)

👆 highlights (mark) / 高亮标记

![outline around block editor text area](https://user-images.githubusercontent.com/58762081/123220763-d67a7d00-d500-11eb-82aa-66faa986908c.png)

👆 outline around block editor text area & highlight current focused block / 编辑状态指示边框 & 当前聚焦 block 高亮

![light theme](https://user-images.githubusercontent.com/58762081/123221022-13df0a80-d501-11eb-939a-16b87f1d7233.png)

👆 light theme / 浅色主题
