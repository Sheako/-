24H 便利购 H5 自建入口
---------------------

文件说明：
- index.html    : 主页面，扫码后会先打开此页，然后在 2 秒后跳转到目标售货机链接。

修改说明：
- 当前内置的目标模板链接是：
  https://m.xiaomai24h.com/q/822123?_wxpmm0=0ED3000D0000
  若需替换，请编辑 index.html 顶部的 template 常量。

使用方法（Vercel）：
1. 在本地下载并解压 vending-h5.zip。
2. 登录 vercel.com → Add New → Project → Upload → 选择解压后的文件夹或直接上传 zip。
3. 部署后得到的域名如： https://your-project.vercel.app
4. 设备二维码示例：
   https://your-project.vercel.app/?device=123456
