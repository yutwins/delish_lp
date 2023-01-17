＜Todo＞
・フォントファミリーが整っているか確認する（WebflowでデフォルトではArialが設定されているから）

・line-heightの設定も細かく確認する必要がある。




＜Components＞
<h2 class="section__title feature__title">DELISH AGENTは<span class="section__title--orange">SNS担当者を月額定額制で</span>導入できるサービスです</h2>


＜メモ＞
【カスタムコードで読み込んでいる部分まとめ】
◉全体
・scroll-behavior: smooth;

◉Topセクション
・Topセクションスライダー部分

◉Feature
・背景色の画像を疑似要素で入れている部分
・navのhoverアクション部分
・itemの番号の背景の丸部分
・itemのflex-direction: row-reverse;部分とnot(:first-child)部分

◉Effect
・.effect-ex__smallTextのアイコン部分
・.effect-ex__list:nth-child(#{$i})部分
・.effect-ex__listDesc部分をEmbedで記入(span要素が入っているため)
・「中長期に効果を見ながら施策と改善をします」という真ん中のタイトル部分をEmbedで記入（span要素が入っているため）


