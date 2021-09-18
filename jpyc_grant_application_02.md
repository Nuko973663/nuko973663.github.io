# JPYC Grant Application 02 JPYC Stabilizer - @Nuko973663

## Project Name

JPYC ユーザーコミュニティーによる二次流通安定化を目指したエコシステムの実装と実践: JPYC Stabilizer

## Description of the project

### JPYC の二次流通における課題

JPYC は QuickSwap や SushiSwap などの DEX において二次流通が行われており、JPYC の様々な活用が進んでいる。一方、市場ニーズに大して流動性プールへの供給量が十分でなく、JPYC の二次流通価格は頻繁に乱高下していた。二次流通価格の不安定さは二次流通量の増加の足枷となると考えられるため、JPYC エコシステムのさらなる発展のためにはこの課題を解決することが重要である。

### 本プロジェクトが提供した解決策

そこで、本プロジェクトでは二次流通価格を安定させるための web アプリ JPYC Stabilizer を開発し公開した。

- JPYC Stabilizer [https://nuko973663.github.io/JPYCstabilizer/](https://nuko973663.github.io/JPYCstabilizer/)

本 web アプリは JPYC の流通量が最も多い Polygon Network を対象としている。本アプリは流動性供給量の多い QuickSwap と SushiSwap の JPYC/USDC スワップレートを定期的に確認し、一定以上レートが乖離した場合に自動スワップを行うことによりレートの乖離を修正する。

この自動スワップ機能により以下の効果が期待される。

- JPYC の二次流通価格の安定
- DEX における JPYC の流通量の増加による流動性提供報酬の増加
- 流動性供給量の増加
- 流動性プール拡大による JPYC 二次流通価格のさらなる安定

加えて、本アプリを利用することによって利用者はスワップレートの差による差益を得ることができる。これにより JPYC のユーザーコミュニティによる自発的な二次流通価格の安定化が期待できる。

このように本 web アプリは JPYC の安定化に貢献した JPYC ユーザーにインセンティブをもたらすことから、JPYC Stabilizer は JPYC ユーザーコミュニティードリブンの JPYC の二次流通価格安定化システムである。

### 解決されていない課題とプロジェクトが取り組む今後の課題

本アプリケーションのリリースにより一定のスワップレート安定効果と流動性供給量の増加が実現された<sup>[1](#ref1),[2](#ref2)</sup>。しかしながら JPYC から他の暗号通貨へのスワップ需要が依然として高く、1 JPYC = 1 JPY のレート実現には至っていない。

そこで、本プロジェクトでは今後以下の課題にも取り組む予定である。

- JPYC Stabilizer 利用者のリーダーボードの実装によるユーザーコミュニティの強化
- JPYC Stabilizer の利回りの明示によるコミュニティユーザーの呼び込み
- QuickStap および SushiSwap の流動性供給による利回りの表示による流動性供給需要の喚起
- JPYC と JPY のレートの乖離を明示することによる暗号通貨から JPYC へのスワップ需要の喚起

## Website

- JPYC Stabilizer [https://nuko973663.github.io/JPYCstabilizer/](https://nuko973663.github.io/JPYCstabilizer/)
- https://nuko973663.github.io

## Grant Level

Level 3

## Grant use

- 開発費用
- サーバー運営費用（利用者カウント、リーダーボード用）

## Network

Polygon Network

## References

1. [QuickSwap JPYC-USDC pair](https://info.quickswap.exchange/pair/0x205995421c72dc223f36bbfad78b66eea72d2677)<a id="ref1"></a>
2. [SushiSwap JPYC-USDC pair](https://analytics-polygon.sushi.com/pairs/0xfbae8e2d04a67c10047d83ee9b8aeffe7f6ea3f4)<a id="ref2"></a>
