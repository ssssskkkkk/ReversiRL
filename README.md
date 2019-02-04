<h1>リバーシAIを0から強化学習</h1>
<p>ランダムAI相手に100%近い勝率を出すことを目標に約4日間学習を行いました。</p>
<p>ネットワークはResNetです。</p>
<p>reversi_main.pyを実行することで実際に学習を行い、学習過程のログを確認することができます。</p>
<p>play_reversi.pyを実行することでプレイヤーを2人選び、リバーシをプレイすることができます。</p>
<p>プレイヤーは以下の3人が用意されています。</p>
<ul>
<li>Random(ランダムに手を打つAI)</li>
<li>DQN(今回学習させたモデル)</li>
<li>Human(人間が盤面を見て手を選ぶことができます。)</li>
</ul>
<p>上記のプレイヤーから2人を選び、任意の組み合わせで対戦させることができます。</p>
<hr>

<h2>ランダムAIに対する勝率</h2>
<p>最終的にはランダムAIに対しては100%近い勝率を達成することができました。</p>
<hr>

<h2>合法手の認識率</h2>
<p>学習初期には合法手を全く認識することができませんでしたが約1日で合法手をほとんど完璧に認識できるようになりました。</p>