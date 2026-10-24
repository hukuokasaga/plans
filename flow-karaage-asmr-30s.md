# Google Flow 制作メモ：唐揚げASMRショート動画（30秒）

## 概要
| 項目 | 内容 |
|---|---|
| 目的 | ショート動画（Reels / TikTok / Shorts） |
| アスペクト比 | 縦長 9:16 |
| 尺 | 30秒（6ショット） |
| ジャンル | ASMRの料理（ひとり飯）動画 |
| メニュー | 唐揚げ定食 |
| 人物 | あり（「ひとりで食べるスーツの中年男性」という型のオリジナル人物） |
| 音声 | セリフなし。ナレーション（心の声）と効果音のみ |

## ⚠️ 権利面の注意
- **井之頭五郎そのもの、または松重豊さんに似せた人物は避ける。** 実在の俳優の肖像や既存のキャラクターに当たるため、生成が拒否されたり、公開後に権利の問題になったりする。
- 「ひとりで食べるスーツの中年男性」という型だけを借りた**オリジナルの人物**にする。名前やナレーションの決め台詞もオリジナルにする。

---

## 1. 人物の設定と参照画像
**設定**：40代後半、長身でやせ型、短い黒髪、無表情だが目つきは穏やか。濃紺のスーツに白シャツ、ノーネクタイ。小さな革のカバンを持っている。

**参照画像のプロンプト（Imagenで縦長9:16）**
```
Vertical 9:16 portrait. An original Japanese man in his late 40s, tall and slim,
short black hair, calm expressionless face with gentle eyes, navy suit, white shirt,
no tie. Standing in front of a small old-fashioned Japanese diner at dusk,
warm lantern light. Cinematic, photorealistic, 35mm film look.
```
→ 気に入った1枚を**素材として保存**し、以降のショットはすべてこの画像を参照して作る（Ingredients to Video など）。

## 2. 唐揚げ定食の参照画像
ショットごとに盛り付けや個数が変わるのを防ぐため、料理の画像も1枚固定しておく。
```
Vertical 9:16, top-down photo of a Japanese karaage set meal on a wooden counter:
five large golden-brown fried chicken pieces with craggy crispy coating,
a lemon wedge, shredded cabbage, a small dab of mayonnaise, a bowl of white rice,
miso soup. Glistening, steam rising, warm diner lighting. Photorealistic, appetizing.
```

---

## 3. 30秒のショット表
| # | 秒数 | 内容 | 主な音 |
|---|---|---|---|
| 1 | 0〜3秒 | **フック**：唐揚げが油の中でジュワーッと泡立つ超接写 | 揚げる音（泡がはじける音） |
| 2 | 3〜9秒 | 男がのれんをくぐり、カウンターに座る | 戸の開く音、揚げ物の音が小さく聞こえる |
| 3 | 9〜15秒 | 揚げたてを網から引き上げる → 定食が目の前に置かれる | 油を切るチリチリという音、器を置く音 |
| 4 | 15〜19秒 | レモンを搾る手元の接写 | しずくが落ちる音、衣にしみる音 |
| 5 | 19〜26秒 | 箸で持ち上げる → 断面から肉汁 → 一口食べて目を閉じる | **ザクッ**という音、ジュワッという音 |
| 6 | 26〜30秒 | 満足げな横顔と、もう1個に伸びる箸 | 環境音が消えていく（冒頭の揚げる音につながる） |

## 4. 各ショットのプロンプト
**すべてのプロンプトに、次の一文を付け加える：**
```
Vertical 9:16, centered subject. No dialogue, no speech, no music. ASMR-focused, crisp detailed sound.
```

### #1 フック
```
Extreme close-up of karaage chicken pieces deep-frying in bubbling golden oil,
tiny bubbles bursting around the craggy coating, slow push-in, warm light.
Sound: intense crackling and bubbling of deep-frying oil.
```

### #2 入店（人物の参照画像を使う）
```
The man from the reference image ducks under a navy noren curtain and enters
a small cozy Japanese diner, sits alone at the wooden counter. Eye level, handheld.
Sound: sliding wooden door, faint deep-frying sounds from the kitchen, quiet ambience.
```

### #3 揚げたてが届く（料理の参照画像を使う）
```
Close-up: golden karaage lifted out of the oil with a wire strainer, oil dripping.
Then the karaage set meal from the reference image is placed on the counter. Steam rising.
Sound: crackling oil draining, ceramic plate set down on wood.
```

### #4 レモンを搾る
```
Extreme close-up: a hand squeezes a lemon wedge over crispy karaage, juice droplets
falling onto the golden coating in slow motion.
Sound: soft squeeze, droplets sizzling lightly on hot coating.
```

### #5 一口
```
Close-up: chopsticks lift a crispy karaage piece; it is bitten, revealing juicy
steaming white meat inside. Cut to the man's face in profile, eyes calmly closing
in quiet satisfaction.
Sound: loud crunchy bite, juicy sound, gentle chewing.
```

### #6 締め
```
Medium close-up of the man's satisfied profile at the counter, his chopsticks
reaching for another karaage piece. Warm light. Static camera.
Sound: diner ambience slowly fading.
```

---

## 5. ナレーションの台本（心の声）
ナレーションはFlowでは生成せず、**編集ソフトで後から入れる**（自分で録音、または音声合成）。声がショットごとに変わるのを防げて、タイミングも合わせやすい。

| 秒数 | ナレーション |
|---|---|
| 3〜8秒 | 「……この音。今日は、揚げ物の日だ。」 |
| 10〜14秒 | 「唐揚げ。揚げたて。それ以上、何がいる。」 |
| 16〜18秒 | 「レモンは……かける派だ。」 |
| 21〜25秒 | 「……ザクッ、じゅわっ。ああ、これだ。」 |
| 27〜30秒 | 「ご飯が、足りない。」 |

- 「ザクッ」「じゅわっ」の直後は**1秒ほど無音の間**を空けて、食べる音を聞かせる。
- ナレーションは少なめにし、音を聞かせる間をしっかり空ける。
- 音を消して見る人向けに、**字幕も入れる**。

---

## 6. 制作のコツ
- **#5の断面と肉汁はいちばん崩れやすいショット。** 5〜6回の作り直しを見込む。うまくいかない場合は、「持ち上げる」と「断面のアップ」の2本に分けて生成する。
- **食べる口元の接写は崩れやすい**ので、箸で持ち上げる手元と表情に分けて見せる構成にしている。
- **衣の質感**：「craggy crispy coating」「golden-brown」を入れると、ゴツゴツした唐揚げらしい衣になりやすい。
- **音はプロンプトで具体的に書く**（crackling、crunchy など）。揚げる音やザクッという音が弱い場合は、編集ソフトで効果音素材を重ねて強調する。
- **料理は唐揚げ定食に固定**し、料理の参照画像を毎回使う。
- **縦型の構図**：被写体は中央からやや上に置く。画面の下20%ほど（キャプションやボタン）と右端（いいねなどのアイコン）には重要なものを置かない。
- 9:16で生成できないモデルやモードの場合は、16:9で被写体を中央に置いて生成し、縦に切り抜く。

## 7. クレジットの目安
- 6ショット × 3〜5回 = **およそ18〜30回の生成**
- #1（フック）と#5（一口）に多めに配分する
- 試しは**高速モード**、本番は**高品質モード**

## 8. 作業の順番
1. 人物と唐揚げ定食の参照画像を作る（Imagen）
2. 高速モードで#1〜#6を一通り試す
3. 良い方向が見えたショットから、高品質モードで本番を作る
4. 編集ソフト（CapCut / Premiere / DaVinci など）で、つなぎ、ナレーション、字幕、効果音の補強をする

> ※ Flow の機能、プラン、クレジットの体系は更新が多いため、細かい仕様は最新の公式ヘルプで確認する。
