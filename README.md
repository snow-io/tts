# docker 部署

```shell
docker run -d -p 8080:8080 --name=tts zuoban/zb-tts
```


# cloudflare worker 部署
[worker.js](https://raw.githubusercontent.com/zuoban/tts/main/templates/worker.js)

## 示例
https://t.leftsite.cn/tts?t={{java.encodeURI(speakText)}}&v=zh-CN-XiaochenMultilingualNeural&r=100&p=0&o=audio-24khz-48kbitrate-mono-mp3
