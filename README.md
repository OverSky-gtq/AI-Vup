# AI-Vup
B站AI虚拟主播，调用gpt3.5的api进行回复。

### 配置
+ 将上面的文件放入同一个文件夹
+ 缺的python库都装上 `pip install -r requirements.txt`
+ 在`config.json`里的添加你的openai key和直播间id
+ `config`里的`preset`是人设，会作为与chatGPT交互的第一句话
+ 运行，在直播间发送弹幕测试，以'。'或'？'结尾的弹幕才会回复

每个用户都是独立的会话，好像不太适合直播，但又不能完全没有记忆，也许短期记忆比较合适？
