#  Node Zhihu Crawl (Zhihu.Answer.Picture)
用途：爬取知乎某一问题下所有回答里的照片~

# 安装
`npm install`

# 配置
例如某个问题的地址: https://www.zhihu.com/question/31159026
地址最后的数字部分，即问题的ID: 31159026
在 `setting.js ` 中设置为 `let answerId = "31159026";`

# 执行
执行 `node app.js`后，等待下载完成，所有图片保存在 `images` 目录