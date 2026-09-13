## Notes

此作品是當使用者按下特定鍵盤按鈕時，會發出鼓聲，同時也會顯示簡單的特效。

## Snippets

利用全堿的 `window` 接收按鍵事件，將 `keyCode` 傳入對應的 `audio` 和 `key` 的 `data-key` 中，後 `audio.play()` 播放音效。

`audio.currentTime` 設為 0 可以重置音樂撥放時間。

運用 `.classList.add()` 可以加入 CSS 樣式，反之 `.classList.remove()` 則是刪除，所以才能讓特效消失。

## References


