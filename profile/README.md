# MTTLDev

Welcome to MTTLDev!

# 組織構成

```mermaid
graph TD
    org["MTTL Dev"] --> Programmer
    org --> Designer
    org --> Writer
```

# プログラムの構成

```mermaid
graph LR
    ts("TypeScript") --> mtsc["MTScript"]
    mtsc --> rpy["Ren'Py"]
    py("Python") --> rpy
    rpy --> app["Novel Game"]
    js("JavaScript") --> we["Web Extension"]
    app --> we
    we --> wp["Web Platform"]
    app --> mw["Mobile Wrapper"]
    mw --> mp["Mobile Platform"]
    app --> ds["Distributor"]
    py --> ds
    ds --> cp["Computer Platform"]
```

# よく使われる言語

## Python
Ren'Pyのサポート言語のため使用。  

## JavaScript
クライアントサイドとしてのJavaScriptを使用。  
Web Extensionの作成に使用。

## TypeScript
MTScriptのコンパイラ作成に使用。

## MTScript
Ren'Pyでのストーリー作成をより容易にするために開発されたトランスパイル型の独自言語。  
なお、言語の定義は曖昧なものとする。

## Ren'Py Script
ゲーム内のデザインやゲームのストーリー外のプログラムを作成する為に使用。

## Go
実行のし易さを活かし、セットアップ用プログラムの開発などに使用。
