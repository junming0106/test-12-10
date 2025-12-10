# 用聊天指令讓玩家說話

這個教學要讓學生學會使用 `player.onChat`，輸入指令後讓玩家說出一句話。

## 步驟一：在輸入「run」後，讓玩家說「:)」

```block
player.onChat("run", function () {
    player.say(":)")
})
```