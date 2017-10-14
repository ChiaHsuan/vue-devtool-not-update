# vue-devtool 不更新

可以在 vue-devtool 觀察 component 的 data，有時候會發生「data 已經更新了，但是 devtool 沒有更新的狀況」

原因是如果畫面上沒有去使用該 data，沒辦法觸發 devtool 的更新

請參考 index.html 的實驗，以及 https://github.com/vuejs/vue-devtools/issues/323
