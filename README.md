# B2C / C2C Pre-Label

由於這次需要標註的商品數量不少，為了讓大家省時省力，我們簡化了一些流程！請大家跟著下面的步驟來完成

### 資料
檔案放在Google雲端裡面(後續會改放在Hugging Face)
https://drive.google.com/drive/folders/1sOHFLJzTK5UAUSCQ2zUV2i9VFJaMr0N2?usp=sharing
資料夾 `b2c_map` 和 `c2c_map` 中的檔案為初始數據，請大家直接使用來進行標註即可，並將標註結果填入`label欄位`

## 標註方式
每組只要依據提供的檔案，利用**自己組內的商品匹配模型**進行標註即可，並將標註的結果放入label欄位。過程中請記得：
- 如果採用相似性匹配的方法，建議適當調低閥值，這樣可以避免過濾掉真正相同的商品。
- 我們使用數字的0和1來代表相同(1)跟不相同(0)

## 報告內容
請分析模型的標註結果，並整理成報告形式。

## 繳交方式
1. **資料整理：**
   - 將模型推論結果壓縮後繳交。
   - 注意：總共有四份檔案需要繳交。每組請指派兩位代表，分別負責 B2C 和 C2C 的檔案整理與報告統整。
2. **檔案規範：**
### 繳交檔案要求
- **B2C 部分：** 檔名格式為 `A_組_B2C_label.csv`
- **C2C 部分：** 檔名格式為 `B_組_C2C_label.csv`
   - **C2C (壓縮檔)：**
   將`A_組_B2C_label.csv`和`A_組_B2C_結果分析.pptx`壓縮在一起後繳交
     - 檔名格式：`組別_B2C.rar`
   - **C2C (壓縮檔)：**
   將`A_組_C2C_label.csv`和`A_組_C2C_結果分析.pptx`壓縮在一起後繳交
     - 檔名格式：`組別_C2C.rar`

## 時間規劃
- **星期三晚上前：** 請上傳各組程式分析後的結果。

祝大家順利完成任務，如果有任何問題，隨時聯繫我～💪

### 繳交期限：
- **星期三2023/11/27 23:59 前：** 請上傳各組程式分析後的結果。

**星期四上課時** 針對後續人工標注的部分進行說明。
* 如果有問題請找助教
* 助教：旭清
* Email：stanley890314@gmail.com