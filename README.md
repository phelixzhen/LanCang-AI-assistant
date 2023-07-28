# LanCang-AI-assistant

想法是做一个AI助手的框架，使用openai格式的API嵌入一个LLM，接上TTS和STT做语音交互，让LLM输出一些系统命令写一个解释器来执行。

现阶段是先用微调的chatglm2-6b来开发解释器。

本项目现在提供开发解释器用的微调模型及一些微调经验和微调数据生成器。

现阶段支持命令:

/message 发送消息对象 "消息内容"

只需要和微调的模型说：请帮我问问ccc吃饭了吗，模型便会输出你需要的命令。<br /><br />

使用了很多项目的代码，在这里给出引用：

chatglm2-6b: https://github.com/THUDM/ChatGLM2-6B

微调方案：https://github.com/hiyouga/ChatGLM-Efficient-Tuning

开源协议 Apache-2.0 License

允许免费商用

小孩子不懂事做着玩的，第一次上传仓库，如果哪里有做的有问题，请联系我：15288750162@163.com
