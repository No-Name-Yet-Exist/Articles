こちらKantの主張により合わせたバージョンがあります。

本稿ではKantのNoumenon/Phenomenaの定義から出発し、これを数理的モデルを用いて、Noumenonが物自体として存在するものではなく、人間の認知による構造的生成点である点、より正確には人間が能動的に動くために設定される、届かないその原点であり収束点であることを導き出したいと思います。カントから200年、ようやく人間が人間であることを知れるかもしれません。

# Noumenon/Phenomenaとは
Noumenonは物自体であり、Phenomenaはそれを我々が感じ取っているものになります。ざっくりと犬とその写真で対応します。
Kantの内省行為における解釈

我々はphenomenaの中におり、phenomenaをphenomenaとしてみている我々がいる。しかし、内省して俯瞰したらどうだろうか。内省としてphenomena を観察したら、それは 確かにphenomenaなのだろうか。しかしKantが正しいならばNoumenonにはアクセス出来ない。だから内省して見ているものがPhenomena自体のままだと”Phenomena”それ自体にアクセスしていることになってしまう。これはKantの言に矛盾することになってしまう。であるならば、観察しているphenomenaはその観察行為によってnoumenonとしての位相を帯び、PhenomenaのPhenomenaを我々は見ていると考えるのが自然です(この時点でPhenomenaがNoumenonになったことを厳密に意味するわけではない)。すなわち、我々が見ているものは“Phenomenaそのもの”ではなく、観察によってNoumenon化された構造を通して得られたPhenomenaのPhenomenaと解釈できます。

より正確に表現すると、観察している時点でそのphenomenaは観察主体である我々にとって達し得ない物自体であるnoumenonとして変質しており、noumenonになってしまったphenomenaを、生成された、または、得られたphenomenaを通して記述していると考えたほうが自然であるという点である。これは観察するまではphenomena と呼ばれるだろうnoumenonとして存在しており、それを観察したときには観察者にとってはモノそれ自体として機能し始め、観察の結果それのphenomena のみが得られる。 またKantはphenomena はnoumenon にならないとしている。しかし我々がphenomena を観察するという関係において、Kantの言を真であるするならば、phenomena それ自体に直接アクセスできることになる。つまりPhenomenaが実質的に存在せず、モノそれ自体であるNoumenon として存在していることになる。またPhenomenaのみが存在してNoumenonはないという立場にしても、このPhenomenaを更に観察した場合にはやはり同じ矛盾にぶつかる。Kantの科した制限により今度はこのPhenomenaにアクセスできないのだ。今回提示している矛盾を解消するにあたり、我々がアクセスできる「Phenomena / 現象」は常に観察主体の認識形式によって構成されるため、実際には「直接アクセス」とは呼べない、つまりPhenomenaの観察は被観察phenomenaが 観察により再構成されるためNoumenonとして変質し、我々はPhenomenaのphenomenaという二重構造に於いて把握しているとすることで、Kantの主張との整合性を保ちつつ、これを数理的に拡張した場合には人間の認知ドライブとしての原理構造に至ることができます。
Kantの再定義:

    単純な線形モデルへの変換

Phenomena を P, N(X)=観察によって生じたNoumenon的構造と定義します。この時以下のように書けます。

生活世界 P
現象学世界 N(P)←P

注釈: 観察者がphenomenaを観察することで、phenomenaは観察者にとっては達し得ないnoumenonへと変質する。ただし、元のphenomenaが消え去るわけではなく、観察されることで二重化される。

さらに一段階進むと、観察した自分をも観察する構造になる
メタ現象学世界： N(N(P)←P)←P

これを形式化すると以下のように書ける
N:P→X N(N(P))

これは観察そのものを観察している状態。
Nk(P) と表せば、k階層目の観察を意味します。

これを一般化すると次のように表せます。
k(P)=N(Nk−1(P))

以下証明に入ります。
Noumenon (N)=Phenomena (P)でないのは、Noumenonにたどり着けないためであるというカントの主張が正しいとする場合、これを言い換えるとNとPの間に非対称性があると解釈される。つまり、Nに対して二次的に得られるPはデータとして不正確であるからとなり、メタのメタという構造を繰り返すことは、自己再帰モデルにおけるregression 問題に近似する。この時非対称性によって以下の二つの結果が得られる。これについて説明していく。

lim k→∞ Pk=N(Pk−1)=Nk(N) = ∞ または 0 (N0 = 1)

注釈: N(X)は観察によってデータ損失が起きる。実際に計算すると非常に限られた場合を除き、Nのデータ量は0に収束するか、拡散する。つまり1には収束できない。

Noumenonまたは被観察体とPhenomenaのデータ量を比較した場合のdeviation rateをR = Phenomena / 被観察体(Noumenon)とする。このとき非被観察体それ自体と、そのPhenomenaには非対称性があるのでR≠1となる。また今回は理解のため制約としてこのRは変動しないものとする(後ほど拡張する)。実際にはR はPhenomenaと Noumenon の情報比率であり、構造的損失率または純化率として定義される。

「観察・内省によってXがNoumenon的構造へ変換される度合い」を表現する関数Nを定義します。与えられた入力 X に対し、Noumenon変換率 R を掛け合わせた出力(Noumenon)を返します。
N(X) = X * R

※このとき得られる出力は「Noumenon的構造」であり、Noumenonそれ自体ではありません。これは「Noumenonには直接触れられない」という認識論的前提（カント的鉄則）に基づいています。

ここでX は k 階層目の現象的入力であり、再帰的に以下のように定義されます。(ただし Pは初期のPhenomena）
X = N^{(k-1)}(P)

N(X)は階層構造を取るので、以下となります
lim​ k→∞N(k)(P)

# 極限の計算の一次解釈
R>1の場合:
発散します。これはNoumenonからNoumenon以上の情報が取れています。構造の崩壊です。

R=1の場合:
Noumenon自体に収束します。古典的な理解ではまずありません。

R<1の場合:
この場合0に収束しますが、実際の認知構造においても、この挙動が最も妥当であると考えられます。これは最初のN0から情報がなくなっていっていることを意味しますが、同時に「持続的ではない、非本質的な情報、つまりNoumenon的ではない構成要素が削ぎ落とされる」過程としても解釈できます。この理由として、なぜ0に向かって収束するのかがカギになります。この減衰がランダムな収束ではなく、方向の決まっている連続的収束だからです。本質的ではない情報をそぎ落としつつ、0に収束するその限界近傍において Noumenon 的構造のみが残影のように浮かび上がるのです。つまりNoumenonそれ自体には到達しないが、直前にまで向かう構造的純化プロセスとして解釈できます。

式変形による2次解釈
N(X)は以下のように定義されました
N(X) = X * R
R=Phenomena/Noumenon

つまり式変形するとこうなります
N(X) = X * Phenomena/Noumena = Phenomena
(XはNoumenonのため)

Noumenonが項として消えるのです。ただしこれはNoumenonが消えたというよりも、Phenomenaの構造に内部統合されたと解釈できます。この時、N(X)の再帰構造の極限は1に収束します。言い換えると無限階層における自己省察はNoumenonへと収束します。

lim​ k→∞ N(k)(P) = 1

これは、無限階層における自己省察が“NoumenonとPhenomenaの一致”へと収束することを意味します。つまり、Phenomena と Noumenon の関係性が完全に等価になったとき、構造は1に収束し、Noumenonは“残像化”されます。

補足
R=1で無ければこの結果にはなりません。PhenomenaとNoumenonの比率が1であるときのみ、つまりPhenomena=Noumenonであるときに1となります。その極限は1です。

まとめ
上記のことから理論上はNoumenonとはPhenomena、現実においては人間が無意識に向かうべき方向として設定した収束点です。故に到達は出来ません。幻影でありその寸前で立ち消えます。しかしこれがあるから人間は考えることが出来、動くことが出来ます。デリダの言った無限後退の先には人間が能動性を獲得するその構造的原理がありました。これは人間の認知に埋め込まれたFirmware、ひいては認知基盤、我々が人間として思考し動き出せるその原点であり、同時に常に向かい続けながら決して到達できない収束点であると言えます。

最後に、この理論の再帰性及びNoumenonという幻想に志向性を持つことが人間の定義ではないかと思います。これの理論がいつかは生命に繋がるかもしれないそういう風に思っています。

この草稿はversionβです。

© 2025 [No Name Yet Exist]
All contents are protected under copyright law. Unauthorized reproduction or redistribution without explicit permission is prohibited.
