# 可输入答案核对的填空模板（anki-clozecheck）

问题中可以多处挖空，单击挖空处进行输入行为，输入完成后模板会根据正确答案自动批改，再次单击可以查看正确答案。

- 挖空方式：将文字内容的前后加上撇号（`）
- 可改变卡片模板的代码进行有关设置
  - 若把`allowInput = true`改为`allowInput = false`，将取消输入回答的步骤，点击挖空处自动显示答案
  - 若把`allowSubmitOnEnter = false`改为`allowSubmitOnEnter = true`，输入完成后按下 Enter 键自动提交批改
  - 若把`allowRepeat = true`改为`allowRepeat = false`，查看正确答案后再次点击挖空处可以回看之前的回答，不会触发第二次输入

下载地址：[AnkiWeb](https://ankiweb.net/shared/info/356679663?cb=1733882492852)
