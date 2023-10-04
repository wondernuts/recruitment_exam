# テーブル設計の試験
基礎的なテーブル設計のテストを実施しております。  
LEAN BODYではMySQLをDBとして利用しており、テーブル設計の経験を必須スキルとして定義しております。

## 提出方法
* 招待したnotionのページにアウトプットの作成をお願いします
* 成果物についてER図の画像でも表でも箇条書きでも大丈夫です
  * 記載方法は評価に影響しません

## 評価対象
基本的なRDBMSのテーブル設計の経験があるのかテストしております。

--------

## 前提
PMは、親レッスンページと子レッスンページを作成して、どのようなレッスンがあるのか伝わるページを作成したいと考えております。  

## 問題
以下の仕様書とデザインとデータを元にDB設計を行なってください。

### 仕様書
- 親レッスンページの表示
    - ヘッダー
        - 画像
        - タイトル
        - 子レッスンの最小難易度
        - 子レッスンの最大難易度
        - 子レッスンの最小レッスン時間
        - 子レッスンの最大レッスン時間
        - タグ

        <img width="380" alt="img1" src="https://github.com/wondernuts/recruitment_exam/assets/22848303/bc7adc08-f269-4bea-8fa3-b9c6802700c0">
        
    - Body
        - 子レッスンのインストラクター一覧
        - 説明文
        - 子レッスンの使用するアイテム一覧
        
        <img width="380" alt="img2" src="https://github.com/wondernuts/recruitment_exam/assets/22848303/9841e8dc-5dc4-4618-a493-17a66174af31">
        
    - 子レッスン一覧
        - レッスン数
        - 子レッスンのタイトル
        - 子レッスンの難易度
        - 子レッスンの最小カロリー
        - 子レッスンの最大カロリー
        - 子レッスンの速度
        - 子レッスンのレッスン時間
        
        <img width="380" alt="image" src="https://github.com/wondernuts/recruitment_exam/assets/22848303/9d8fe167-295e-45ab-9b20-f9e49d1b9083">
        
- 子レッスンページの表示
    - ヘッダー
        - 親レッスンのタイトル
        - タイトル
        - 難易度
        - 最小カロリー
        - 最大カロリー
        - 速度
        - タグ
        - ジャンル
        
        <img width="380" alt="img4" src="https://github.com/wondernuts/recruitment_exam/assets/22848303/a294f9d5-d3da-49c0-93d0-e1fafa589f57">
        
    - Body
        - インストラクター一覧
        - 説明文
        - 使用するアイテム一覧
        
        <img width="380" alt="img5" src="https://github.com/wondernuts/recruitment_exam/assets/22848303/3104185c-17e7-45cb-a54d-13480a405d67">


### デザインのリンク
https://www.figma.com/file/XZcZNqtZZVIQJvENTNnwQd/ENGINEER-SKILL-CHECK?type=design&node-id=0-1&mode=design&t=Fvjkb9mLRoVuRZHp-11


### データ
https://docs.google.com/spreadsheets/d/1KEmrxCbG_AP692MrgGe7di6sjAmxIf_U4YaTo3Oo2GE/edit?usp=sharing
