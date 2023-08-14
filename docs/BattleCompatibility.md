# 戦闘中の相性

ユニットの武器タイプやユニットの持つ特性、味方の作戦・敵のレイジレートで決まる「相手ユニットへのダメージ倍率」の様なもので、
戦闘画面中央下に9段階で表示されている。

有利　　赤☆＞黄☆＞黄〇＞緑〇＞緑－＞青－＞青△＞灰△＞灰Ｘ　　不利

## ユニットの武器タイプでの相性

ユニットごとに設定された武器タイプの相性に、敵味方の戦術補正をかけたもので、ユニットや装備品の特性での補正をかける際の基準にもなる。

- 対戦相手の武器タイプとの相性が良い場合<br />
杖・鎌タイプの対戦相手が剣・槍・斧タイプだったり、弓タイプの対戦相手が杖・書タイプだった場合が当てはまる。
  - 味方Aggressive：赤☆　味方Neutral：黄〇　味方Passive：緑－
  - 敵MAX：赤☆　敵RAGE：黄☆　敵NONE：黄〇

- 対戦相手の武器タイプとの相性が普通の場合<br />
対戦相手の武器タイプが同じだったり、剣・槍・斧タイプの対戦相手が弓・杖・書タイプだった場合が当てはまる。
  - 味方Aggressive：黄〇　味方Neutral：緑－　味方Passive：青△
  - 敵MAX：黄〇　敵RAGE：緑〇　敵NONE：緑－

- 対戦相手との武器タイプの相性が悪い場合<br />
弓タイプの対戦相手が剣・槍・斧タイプだったり、杖タイプの対戦相手が書タイプだった場合が当てはまる。
  - 味方Aggressive：緑－　味方Neutral：青△　味方Passive：灰Ｘ
  - 敵MAX：緑－　敵RAGE：青－　敵NONE：青△

## 装備品・ユニット特性での相性変化

- 「（特定地形or時間帯）が得意」が適応された場合<br />
街道地形にナイトがいる場合やアサシンが夜間に戦闘を仕掛ける場合が当てはまる。
  - 対戦相手の武器タイプに左右されず、前述した「対戦相手の武器タイプと相性が良い場合」と同じ状態になる。
  - この状態なら苦手な武器タイプのユニットとも互角に渡り合う事が可能だが、有利な武器タイプのユニットとの戦いでさらに有利になる訳ではない。

- 「（森林地形or砂漠地形）が苦手」が適応された場合。<br />
前者はナイトの、後者はウンディーネのユニット特性となる。

- 「（特定属性）攻撃は無効」特性を持つユニットに、対応する属性攻撃をした場合。<br />
ヴァルキリー同士やウンディーネ同士で戦闘する場合が当てはまる。
  - この場合、敵味方で効果は変わらず相性は『灰Ｘ』となり、相手にダメージは全く通らなくなる。
  - ただし、発動率がLUKに左右されるフラッシュアタック（味方のＸタイプスキルチャージを妨害するアレ）は話が別で、属性がついていてもダメージが通る様になっている。

- 「（特定属性）攻撃力アップ」特性を持つ装備品を装備し、対応する属性攻撃をした場合。<br />
エクスカリバー装備のユグドラや、初登場時のイシーヌ（アイスジャベリン装備）などが当てはまる。
  - この場合、敵味方で効果は変わらず『黄〇⇒黄☆』といった具合に、それぞれAggressiveとRAGE時の相性が1ランク上昇する。
  - また、属性攻撃を続けている間は『黄〇⇒緑〇』といった具合に、対戦相手の相性を1ランク低下させる効果も持つ。
  - この相性ランク低下効果は、「（特定属性）攻撃は無効」の特性をもってしても防ぐ事が出来ない。

- 「（特定属性）攻撃に弱い」特性を持つ相手に、対応する属性攻撃をした場合。<br />
「神聖攻撃に弱い」ネクロマンサーを攻撃するAggressive時のユグドラや、「火炎攻撃に弱い」ニーチェを攻撃するRAGE時のウィッチなどが当てはまる。
  - 前述と同じく敵味方で効果が変わらず、それぞれAggressiveとRAGE時の相性が1ランク上昇し、対戦相手の相性を1ランク低下させる。

- 「（特定属性）攻撃に弱い」特性を持つ相手に、「（特定属性）攻撃力アップ」特性を持つ装備品を装備し、対応する属性攻撃をした場合。<br />
「神聖属性攻撃に弱い」ネクロマンサーにエクスカリバー装備で攻撃するAggressive時のユグドラが当てはまる。
  - 強化特性と弱体化特性の相乗効果で、属性攻撃を仕掛けた側の相性が2ランク上昇し、属性攻撃を受ける側の相性が2ランク低下すると思いきや･･･。
  - 味方の場合、前述と同じくAggressive時の相性が1ランク上昇し、相手の相性が1ランク低下する。

- 「（特定ユニット）に強い」特性を持つユニットで、対応するユニットと戦った場合。<br />
ナイトキラー装備のデュランでナイトを攻撃した場合などが当てはまる。
  - 味方の場合、Passive時で黄〇、それ以外で常時赤☆となる。この場合、AggressiveとNeutralの攻撃力に差はない。
  - 敵の場合、レートに関係なく相性が常時赤☆になる。

- 「（特定ユニット）に弱い」特性を持つユニットで、対応するユニットと戦った場合。<br />
ハンターと戦うグリフライダーや、グリフライダーと戦うナイトが当てはまる。
  - 味方の場合、Aggressive時で灰△、それ以外で常時灰Ｘとなる。この場合、PassiveとNeutralの攻撃力に差はない。
  - 敵MAX：青△　敵RAGE：灰△　敵NONE：灰Ｘ
  - なお、例え得意な地形や時間帯にいようが関係なく、対応するユニットと戦うと必ず上記の相性で戦う事となる。
  - また、対戦相手には「（特定ユニット）に強い」特性がついているのがほとんどなので、余程の能力差がない限り、不利な特性を持つユニットの勝利は絶望的だろう。
  - しかしながら、属性攻撃を無効化された時にも相性が灰Ｘの状態になるが、こちらの場合はわずかにダメージが通っており、勝つ事は出来ずとも相手メンバー数を削る事は可能。
  - 小さい胸当て（弓系ユニットに強い）を装備したBF27のエミリオ（ハンターに弱い）を、ハンターのクルスで攻撃した場合は・・・未検証。
  - ハンターに弱いエミリオを、ロープ（全ユニットに弱い）装備のクルスで攻撃した場合は・・・未検証。

## PAスイッチ戦法

「エースタイプが違う」「使用条件を満たしていない」などの理由でスキルに頼らず戦闘する際、<br />
まずはAggressiveでゲージを使い切った後、「Passive⇒Aggressive⇒Passive⇒Aggressive…」といった具合に細かく作戦変更する戦法である。<br />
攻撃力の大小は『Aggressive＞PAスイッチ＞Neutral』といった関係になっていると思われ、Neutral固定で戦うよりもダメージ量が向上する。<br />
敵ユニットのヘッドを倒せずに競り負けるので競り勝ちたい時や、敵生存メンバー数による味方ユニットへの士気ダメージの軽減の他、<br />
手早く戦闘に勝利して味方生存メンバー数による敵ユニットへの士気ダメージを増大させたりと、その用途は広い。<br />
作戦を変更するタイミングは、『ゲージ0％でPassive⇒10％位溜めたらAggressive』の繰り返しがちょうど良いか。戦闘スピードがHIGHでも割と切り替えやすい。<br />
溜める量が少なすぎると手元が忙しくなり、多すぎると効率が落ちてしまうのでご注意を。

- 比較検証
  - 検証ステージ:BF06　フェリナス湖畔（HARD）
  - 対戦ユニット：ミラノ（全ステータス☆☆☆）vsジルヴァ（LUK☆☆☆、それ以外☆☆）
  - 使用カード：レヴォリューション（白兵戦開始時でゲージ38％）
  - 戦闘条件：双方とも特性による相性変化なし。帝国軍のターンで開始し、ジルヴァ突撃後の時点でメンバー数は6人対8人。なお、クリティカルは発生せず。
  - ①Aggressiveでゲージを使い切った後、Neutralのまま戦った場合。（20回戦闘）
  - WIN：10回　LOSE：10回　　　勝率：50％
  - ②Aggressiveでゲージを使い切った後、10％刻みでPAスイッチをしながら戦った場合。（20回戦闘）
  - WIN：16回　LOSE：4回　　　 勝率：80％
  - この様に、PAスイッチで戦った方が敵ユニットに叩き込めるダメージが上昇しており、結果的に勝率も上昇する。
  - 補足：戦闘結果は勝った場合も負けた場合も『勝利ユニットのヘッドが1人だけ生き残る』結果となっている。
