
> **注意**: 現在の `practice` ブランチは、書籍「Five Lines of Code」の実践演習のためのブランチです。このブランチでは、書籍で学んだリファクタリング手法を実際に適用していきます。

# five-lines

In this kata your task is to refactor the code for a small game. When finished it should be easy to add new tile types, or make the key draw as a circle, so we can easily distinguish it from the lock. 

The code already abides by the most common principles "Don't Repeat Yourself", "Keep It Simple, Stupid", and there are only very few magic literals. There are no poorly structured nor deeply nested `if`s.

This is *not* an easy exercise.

# About the Game
In the game, you are a red square and have to get the box (brown) to the lower right corner. Obstacles include falling stones (blue), walls (gray), and a lock (yellow, right) that can be unlocked with the key (yellow, left). You can push one stone or box at a time, and only if it is not falling. The flux (greenish) holds up boxes and stones but can be 'eaten' by the player. 

![Screenshot of the game](game.png)

# How to Build It
プロジェクトのビルドには以下の手順を実行してください：

1. 必要な依存関係をインストールします：
   ```
   npm install
   ```

2. TypeScriptコードをコンパイルします：
   ```
   npm run build
   ```

ビルドが成功すると、`index.js`ファイルが生成されます。

# How to Run It
ゲームを実行するには、まず上記の手順でビルドを行ってください。その後、ブラウザで`index.html`ファイルを開くだけです。矢印キーを使用してプレイヤーを操作できます。

開発中は以下のコマンドを使用すると、ファイルの変更を監視して自動的に再ビルドされます：
```
npm run watch
```

# Thank You!
If you like this kata please consider giving the repo a star. You might also consider purchasing a copy of my book where I show a simple way to tackle code like this: [Five Lines of Code](https://www.manning.com/books/five-lines-of-code), available through the Manning Early Access Program.

[![Five Lines of Code](frontpage.png)](https://www.manning.com/books/five-lines-of-code)

If you have feedback or comments on this repo don't hesitate to write me a message or send me a pull request. 

Thank you for checking it out.

