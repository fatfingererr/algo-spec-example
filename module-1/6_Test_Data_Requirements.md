## Test Data Requirements

- 通常你的演算法一定可以跑個簡單範例，這邊就可以列出那個簡單範例，

- 同時也可以強調測試資料得應該具備的一些特徵，通常就是要強調測試資料的一致性（conformance）

- 基本上就是幫你的演算法寫可能需要撰寫的單元測試，這部分是整份演算法規格裡面最重要的。

### Design conformance test data

- 如果你的測試資料可以根據某一種準則產生出來，也可以特別說明方法

### Input/Output test data

- 這邊可以舉一些例子，甚至說你直接準備好測試資料

### Test Efficiency Requirement for test data

- 在你這樣產生出來的資料中, 運行時需要留意的測試效率為何

### Algorithm evaluation criteria

- 這裡主要是說演算法在那些例外情形可以不需要求值，簡單來說就是丟 Error 的罷工時機

### The extent of the mathematical analysis

- 這裡主要是驗證演算法的一些數學性質，如果是迭代的話是否要做收斂性的檢查？

### Statistical testing applied to the algorithm

- 這裡主要是如過輸出是具有統計性質的，你需要在輸出上面做的統計檢定是什麼