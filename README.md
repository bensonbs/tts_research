# tts_research
tts_research

## Vall-E X

### 多語言 TTS
可使用三種語言 - 英語、中文和日語 - 進行自然、富有表現力的語音合成。


    [JA]今日の朝食はエッグパンケーキにしたいです[JA]
    [ZH]今天早餐我想要吃蛋餅[ZH]
    [EN]I want to have egg pancakes for breakfast today.[EN]
    

[gen-multi-lang.webm](https://github.com/bensonbs/tts_research/assets/120996184/495b11b1-1731-4014-86de-7e0a1bc56146)

### 🎙聲音克隆
Voice Cloning VALL-E X 支持聲音克隆！您可以使用任何人、角色或甚至您自己的聲音來創建語音提示，並像其他語音預設一樣使用它。要製作語音提示，您需要提供一個時長為3~10秒的語音，以及該語音的文字稿。您也可以不提供文字稿，讓Whisper模型來生成文字稿。

    
- 錄製樣本(Whisper模型生成文字)

      就是他整個身體是瀰漫在空間之間的
      他所有的力氣, 他所有的生長的力氣已經消耗盡了
[js-209.webm](https://github.com/bensonbs/tts_research/assets/120996184/f2da39de-5783-46c3-b032-873b4e9e3dde)

#### 生成樣本

      這裡是蔣勳, 歡迎來到美的沉思
      今天早餐我想要吃蛋餅
      蛋餅裡面一定要包薯餅, 再沾點番茄醬
[gen-js-209.webm](https://github.com/bensonbs/tts_research/assets/120996184/3f6aa6be-5912-4eb7-8b11-60d686c6193e)

## coqui/XTTS-v1
### DR
TTS 建立在 Tortoise 的基礎上，進行了重要的模型更改，使跨語言語音克隆和多語言語音生成變得非常容易。不需要跨越無數小時的大量訓練資料。
#### 錄製樣本
  
[dr.webm](https://github.com/bensonbs/tts_research/assets/120996184/3496ff1d-b9b8-4a2d-a8ee-64d6666e3fbb)

#### 生成樣本

[CH-dr-xtts_v1.webm](https://github.com/bensonbs/tts_research/assets/120996184/e6dff7d4-b47e-42a1-b570-9eeef6e91e53)

[dr_2.webm](https://github.com/bensonbs/tts_research/assets/120996184/5d29f305-d826-4534-8081-033c9405e196)

### JS

#### 錄製樣本

  
[js.webm](https://github.com/bensonbs/tts_research/assets/120996184/e3e30022-7e00-4db1-8bd9-efb4c9f95e0e)

  
#### 生成樣本
  
[CH-js2-xtts_v1.webm](https://github.com/bensonbs/tts_research/assets/120996184/f64d2888-ac3b-4488-ab6e-28cb3f5b8790)
