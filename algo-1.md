# Algo 1

## 1. General Structure

- 通常就是演算法整體的結構，通常是放一張流程圖，或是一個 Pseudocode

### 1.1. Initialization

- 有些演算法的初始化和計算流程一樣複雜，因此可以把初始化獨立出來變成一個執行步驟

### 1.2. Working Stages

- 這邊就是演算法的運算階段，這裡提到的所有的流程和參數，都應該在前一節定義完成

### 1.3. Deinitialization

- 反初始化就是指說如果執行到一半，我臨時停掉了這個演算法，他會接著執行什麼動作保全階段結果，或是清除這段期間暫存的檔案等

## 2. Functional requirements

### 2.1. Type I and parameters of algorithm

- 這邊主要不是涉及到軟體開發上的型別或變數，而是演算法中各個參數的意義
- 如果演算法可以透過不同的 input 類型得到不同 output 就算做不同 type

####  INPUT - Interfaces to the algorithm

- 這邊主要講別人需要準備什麼才能輸入到你的演算法裡面

#### OUTPUT - Operation Modes

- 這邊主要講解演算法運算的各種輸出可能

### 2.2. Type II and parameters of algorithm

####  INPUT - Interfaces to the algorithm

#### OUTPUT - Operation Modes

### 2.3. Type III and parameters of algorithm

#### INPUT - Interfaces to the algorithm

#### OUTPUT - Operation Modes

## 3. Performance Requirements

### 3.1. Implementation and operational considerations

- 例如說你的演算法會算很久，這邊就要列出在怎樣的環境你的計算時間，要別人留意時間或速度還有就是記憶體的使用情況

### 3.2. Implementation complexity

- 這邊可以告訴別人，你的演算法要實際變成程式碼的過程中，有哪一段或哪個情況會特別難實作

- 要特別請開發人員留意，例如一些 workaround 或是需要大量程式碼撰寫的片段

## 4. Design and evaluation principles for the algorithm

- 既然別人要實現你的演算法，你可以講你的演算法巧妙設計的地方在哪裡

- 除此之外，你也要提供一些指標或原則，給開發人員參考，他要怎麼樣評估他實現你的演算法的完整程度

## 5. Reliability and scalability of the algorithm

- 簡單來說就這個演算法當輸入越來越大量、多元複雜時，能否仍然值得安心使用

- 或是和其他演算法混合使用的自由度，可不可以和其他演算法有複雜嵌套

## 6. Test Data Requirements

- 通常你的演算法一定可以跑個簡單範例，這邊就可以列出那個簡單範例，

- 同時也可以強調測試資料得應該具備的一些特徵，通常就是要強調測試資料的一致性（conformance）

- 基本上就是幫你的演算法寫可能需要撰寫的單元測試，這部分是整份演算法規格裡面最重要的。

### 6.1. Design conformance test data

- 如果你的測試資料可以根據某一種準則產生出來，也可以特別說明方法

### 6.2.  Input/Output test data

- 這邊可以舉一些例子，甚至說你直接準備好測試資料

### 6.3. Test Efficiency Requirement for test data

- 在你這樣產生出來的資料中, 運行時需要留意的測試效率為何

### 6.4. Algorithm evaluation criteria

- 這裡主要是說演算法在那些例外情形可以不需要求值，簡單來說就是丟 Error 的罷工時機

### 6.5. The extent of the mathematical analysis

- 這裡主要是驗證演算法的一些數學性質，如果是迭代的話是否要做收斂性的檢查？

### 6.6. Statistical testing applied to the algorithm

- 這裡主要是如過輸出是具有統計性質的，你需要在輸出上面做的統計檢定是什麼

## 7. Appendix

### 7.1. XXX Implementation

用什麼方法特別撰寫的一個可執行 Toy code ，通常就是只有運行 Happy Path 的部分。