# XAUUSD Trade Judge Ver.1.1

BTCUSD版とは完全に別のXAUUSD専用アプリです。

## 判定順序
1. 4H / 1H の上位足環境
2. 水平線・ゾーン（直近高安値、複数反応、複数時間足重複）
3. EMA20 / EMA75 / EMA200
4. Point 1〜9 のセットアップ
5. 5分・15分の中期確認
6. 1分足の反応・揉み・ブレイク・リテスト
7. LONG候補 / SHORT候補 / WAIT

## 使用しないもの
- APS（BTC/暗号資産用のためXAUUSD判定から除外）
- TAKEO
- TAKEKO

単純多数決ではなく「環境 → 場所 → 形 → タイミング」の階層判定です。

Ver.1.1は手動入力版です。TradingView Webhook/Worker自動連携は次段階で追加できます。
