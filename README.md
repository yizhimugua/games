# 贪吃蛇小游戏

一个纯前端实现的贪吃蛇小游戏，打开 `snake.html` 就可以直接游玩。项目不依赖构建工具或第三方库，适合放在 GitHub Pages 上作为一个轻量小游戏页面。

## 玩法

- 控制蛇吃到食物，每吃到一次获得 10 分，并让蛇身变长。
- 分数每满 50 分，速度等级会提升，游戏节奏会变快。
- 撞到墙壁或撞到自己的身体时，游戏结束。
- 最高分会保存在当前浏览器的 `localStorage` 中。

## 操作方式

- 方向键或 `WASD`：控制移动方向。
- 空格键：暂停或继续游戏。
- “开始 / 暂停”按钮：开始、暂停或继续。
- “重新开始”按钮：重置当前游戏。
- 移动端支持方向按钮和滑动手势。

## 本地运行

克隆仓库后，直接用浏览器打开 `snake.html`：

```bash
git clone https://github.com/yizhimugua/games.git
cd games
```

然后双击 `snake.html`，或在浏览器中打开这个文件即可。

## GitHub Pages

如果仓库开启了 GitHub Pages，可以通过类似下面的地址访问：

```text
https://yizhimugua.github.io/games/snake.html
```

## 文件结构

```text
.
├── README.md
└── snake.html
```

## 技术栈

- HTML
- CSS
- JavaScript
- Canvas

