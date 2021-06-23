# logseq-default-dark-0-saturation

Default [Logseq](https://logseq.com/) dark theme with 0 saturation background and some other tweaks.

## Modifications

All these changes are based on default dark theme of Logseq.

- 0 saturation background
- Red accent color
  - link
  - highlight
  - searchbar
  - checkbox
  - …
- Added highlight to focused block
- Added 🔴 🟡 🟢 to `[#A]` `[#B]` `[#C]`, respectively
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
- Fixed some CodeMirror issues
- Red accent color in light theme
  - I seldom use light theme, so it might be buggy 😢

## How to use

Copy and paste the contents of `custom.css` file into your `logseq/custom.css` file.

Or

Add the following line to your `logseq/custom.css` file.

```css
@import url('https://cdn.jsdelivr.net/gh/LeonWong0609/logseq-default-dark-0-saturation@main/custom.css');
```

## Screenshots

![image](https://user-images.githubusercontent.com/58762081/123148201-86fd6800-d492-11eb-9550-e3d4a442d1fc.png)
