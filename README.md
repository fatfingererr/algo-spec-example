# algo-spec-example

演算法規格的範例

- Version : 5.0
    - 如果內部有自己定義的研發版號，可以獨立於 Repo
    - 如過這份檔案有 PDF/Word 可以下載，連結也可以放於此

## Preface

- 講解有多少個子演算法，或是模組，或是和其他 Repo 的規格的關係，是否屬於同一系列

## Introduction 

- 適當講解演算法要解決的問題
- 適當講解過去解決的辦法

```
這邊主要是強調這個演算法的特色，不用像寫論文那樣子做考古然後把道理說的頭頭是道。
可以想成，如果今天是要外包這個演算法，你需要告知對方相關背景知識到什麼程度。
```

## Notations and conventions

- 這邊就是把你的演算法會使用到記號與慣例做說明
- 必要也可以搭配範例（Example）做說明
- 還有你會使用到的縮寫術語（abbreviations）

```
這一節主要目的，是提供開發人員思考較不容易被規範的變數命名、函數命名
避免在 Code Review 的會議上，才被指正
```

### Notations


### Abbreviations


### Naming Conventions

## Uses of the XXXXXX algorithm 

- 這邊強調的是演算法如何搭配各種情況作使用

```
這邊可以想成，是要給開發人員思考可能運行的情況。
```

### Place of use

- 這通常是指環境需要那些 `前置的配置 (Config)`，例如可能使用到的第三方套件，或內部的其他模組（utils, helper ... etc.)。

### Use of algorithm with <something 1>

- 這主要是如果要在特定定義的什麼上面執行，需要說明接過來演算法會轉換成什麼

### Use of algorithm with <something 2>

### Use of algorithm with <something 3>	