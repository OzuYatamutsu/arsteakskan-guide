# ![](jinhai.png) Arsteakskan language reference, yo!

### tl;dr:
 * **Arsteakskan** is a fork of Chinese for Chinese and English speakers. It's
 meant to serve as a third auxiliary language for, like, if you want to look
 cool or something!

 * Chinese words and grammar remain largely the same.

 * However, there are a few Arsteakskan-specific words and grammar traits which extend Chinese grammar. Many of these are cat noises (it was written as a cat language).

 * It's pretty much a series of systems for representing written Chinese and
 English using [bopomofo](https://en.wikipedia.org/wiki/Bopomofo), with a few
 Japanese words thrown in.

 * There's going to be a lot of cat references coming up. _Be warned._

### Bopomofo
**Bopomofo** is a character system designed to represent sounds in Chinese.
In Arsteakskan, it can be used to represent sounds in Chinese _and English,_
and can also be substituted for entire Chinese characters, English words, or transliterated names.

Onomatopoeia is almost exclusively represented as bopomofo, as well as a few
Arsteakskan-specific words which do not exist in Chinese or English.

|**Symbol**|**Sound**|**Example (Chinese)**|**Example (English)**|
|:-:|:-:|:-:|:-:|
|ㄅ|b|**ㄅ**ㄚ (ba) _to hold_|**ㄅ**ㄚㄆ (bap) _bap_|
|ㄆ|p|**ㄆ**ㄠ (pao) _to run_|**ㄆ**ㄠㄋㄙ (paons) _pounce_|
|ㄇ|m|**ㄇ**ㄢ (man) _slow_|**ㄇ**ㄧㄠ (miao) _meow_|
|ㄈ|f|**ㄈ**ㄡ (fou) _no_|**ㄈ**ㄛㄍㄊ (fogt) _forget_|
|ㄉ|d|**ㄉ**ㄢ (dan) _egg_|**ㄉ**ㄛㄍㄡ (dogou) _doggo_|
|ㄊ|t|**ㄊ**ㄡ (tou) _head_|**ㄊ**ㄖㄎㄧ (trki) _turkey_|
|ㄋ|n|**ㄋ**ㄠ (nao) _brain_|**ㄋ**ㄧㄖㄅㄞ (nirbai) _nearby_|
|ㄌ|l|**ㄌ**ㄠ (lao) _old_|**ㄌ**ㄟㄗ (leiz) _laze_|
|ㄍ|g|**ㄍ**ㄡ (gou) _dog_|**ㄍ**ㄖㄟㄊ (greit) _great_|
|ㄎ|k|**ㄎ**ㄢ (kan) _to see_|**ㄎ**ㄚㄊ (kat) _cat_|
|ㄏ|h|**ㄏ**ㄝ (he) _to drink_|**ㄏ**ㄚㄊ (hat) _hat_|
|ㄐ|j|**ㄐ**ㄧㄠ (jiao) _foot_|**ㄐ**ㄇㄆ (jmp) _jump_|
|ㄑ|q|**ㄑ**ㄧㄢ (qian) _money_|**ㄑ**ㄨㄚㄎ (quak) _quack_|
|ㄒ|x|**ㄒ**ㄧㄢ (xian) _wire_|_does not exist in English_|
|ㄓ|zh|**ㄓ**ㄣ (zhen) _real_|_does not exist in English_|
|ㄔ|ch|**ㄔ**ㄡ (chou) _smelly_|**ㄔ**ㄧㄨ (chiu) _chew_|
|ㄕ|sh|**ㄕ**ㄢ (shan) _mountain_|**ㄕ**ㄟㄎ (sheik) _shake_|
|ㄖ|r|**ㄖ**ㄡ (rou) _meat_|**ㄖ**ㄧㄉㄨㄙ (ridus) _reduce_|
|ㄗ|z|**ㄗ**ㄠ (zao) _morning_|**ㄗ**ㄧㄖㄚㄎ**ㄗ** (zirakz) _Xerox_|
|ㄘ|c|**ㄘ**ㄠ (cao) _grass_|_does not exist in English_|
|ㄙ|s|**ㄙ**ㄚ (sa) _to spray_|**ㄙ**ㄟㄌㄧㄋ (seilin) _saline_|
|ㄚ|a|**ㄚ**ㄋ (an) _peace_ |**ㄚ**ㄊ**ㄚ**ㄎ！(atak) _attack!_|
|ㄛ|o|ㄉ**ㄛ** (duo) _many_|ㄧ**ㄛ**ㄋ (ion) _yawn_|
|ㄜ|e|||
|ㄝ|ê(h)|||
|ㄞ|ai|||
|ㄟ|ei|||
|ㄠ|ao|||
|ㄡ|ou|||
|ㄢ|an|||
|ㄣ|en|||
|ㄤ|ang|||
|ㄥ|eng|||
|ㄧ|i|||
|ㄨ|u|||
|ㄩ|ü||_does not exist in English_|

### Representing words
Arsteakskan bopomofo is **context-sensitive** -- the meaning of a word is largely dependent on the words around it. This is important, as words can be represented in _two different ways_ using bopomofo: as a representation of the Chinese pronunciation for a Chinese word, and as a representation of the English pronunciation of an English word. In special cases (detailed later), Japanese _kana_ can also be pronounced as Japanese or Arsteakskan based on a subscript marker.

_All_ English words are represented with bopomofo. _Any_ Chinese word can be represented as the original character, as its pronunciation in bopomofo, or as the pronunciation of the English translation of the word in bopomofo.

If bopomofo represents an English pronunciation, there is a many-to-one relationship between bopomofo and English -- as long as it sounds similar, a single English word can be represented multiple ways.

**car**

|  车 | ㄔㄜ | ㄎㄦ | ㄎㄚㄖ |
|:---:|:----:|:----:|:------:|
| che | ch e | k er |  k a r |


Unlike in Chinese bopomofo, Arsteakskan bopomofo tone markers are optional (the character specified by the pronunciation is chosen based on the context), but can be explicitly specified if needed. Tone markers are specified below:

| neutral | flat (1) | rising (2) | falling-rising (3) | falling (4) |
|:-------:|:--------:|:----------:|:------------------:|:-----------:|
|    ˙    |     ¯    |      ˊ     |          ˇ         |      ˋ      |

_Note that first tone is represented by ¯, unlike Chinese bopomofo._

Chinese words in Arsteakskan are **context-free** -- they maintain their original Chinese meaning regardless. The practical effect is that if there is any trouble remembering a particular Chinese character or pronunciation, multiple alternatives to represent that concept are available.

#### A few examples
Words along the same row have the same meaning.

| Chinese |  English  |  Bopomofo  | Bopomofo |
|:-------:|:---------:|:----------:|:--------:|
|   攻击  | to attack | ㄍㄨㄥㄐㄧ<br /><sub><sup>g u eng j i</sub></sup> | ㄚㄊㄚㄎ<br /><sub><sup>a t a k</sub></sup> |
|   保护  | to protect | ㄅㄠㄏㄨ<br /><sub><sup>b ao h u</sub></sup> | ㄆㄖㄡㄊㄝㄎ<br /><sub><sup>p r ou t e(h) k</sub></sup> |

The following sentences all have the same meaning. The word to represent as bopomofo was arbitrarily chosen.

###### _I walked my cat._

我跟我猫走路。<br />
<sub><sup>wo gen wo mao zou lu</sub></sup><br />
我ㄍㄣ我ㄇㄠ走ㄌㄨ。<br />
<sub><sup>wo gen wo mao zou **l u**</sub></sup><br />
我ㄍㄣ我ㄎㄝㄊㄗㄡ路。<br/>
<sub><sup>wo gen wo **k a t z ou** lu</sub></sup>

###### _I could still be at my house, unless I went to the bar._

我可以还在我家里，否则我去酒吧。<br />
<sub><sup>wo ke yi hai zai wo jia li, fou ze wo qu jiu ba</sub></sup><br />
我可以还在我家里，否ㄗㄜ我去ㄐㄧㄡㄅㄚ。<br />
<sub><sup>wo ke yi hai zai wo jia li, fou **z e** wo qu **j i u b a**</sub></sup><br />
我可以还在我ㄐㄧㄚ里，ㄈㄡ则我去ㄅㄦ。<br />
<sub><sup>wo ke yi hai zai wo **j ia** li, **f ou** ze wo qu **b er**</sub></sup><br />

###### _I hate Mondays, and love lasagna._

我恨星期一，爱吃千层面。<br />
<sub><sup>wo hen xing qi yi, ai chi qian ceng mian</sup></sub><br />
我恨ㄒㄧㄥㄑㄧ一，ㄞ吃千ㄘㄥ面。<br />
<sub><sup>wo hen **x i eng q i** yi, ai chi qian ceng mian</sup></sub><br />
我恨ㄇㄣㄉㄟㄙ，ㄞ吃ㄌㄚㄙㄚㄍㄚ。<br />
<sub><sup>wo hen **m en d ei s**, ai chi **l a s a g a**</sup></sub>
