# ソフトウェアカーペントリーの初日本語ワークショップ

４月に初めて日本語で[ソフトウェアカーペントリー](https://software-carpentry.org/)のワークショップを開きました（オンライン）。今回のワークショップは[beyond AI](https://beyondai.jp/)という、東京大学とソフトバンク株式会社による連帯事業との共同開催でした。[「Rによるデータ解析入門」](https://swcarpentry-ja.github.io/2021-04-02-todai-online-ja/)というタイトルで、[今まで翻訳してきたRレッスン](https://swcarpentry-ja.github.io/r-novice-gapminder/ja/)を元に行いました(このレッスンの翻訳についてのブログポストは[こちら](https://carpentries.org/blog/2021/02/complete-R-lesson-japanese/))。以下、[カーペントリーズ形式](https://datacarpentry.org/blog/2017/06/minute-cards)で「緑付箋」（上手く行ったこと）と「赤い付箋」（上手く行かなかったこと）に分けて感想をまとめました。

## 緑付箋

### 共同主催者と密接な連携

今回の共同主催者の[beyond AI](https://beyondai.jp/)に大変お世話になりました。beyond AIが参加者（主に東京大学文系大学院生）を募集して、重要な連絡をしてくれたので、[我々翻訳チーム](https://swcarpentry-ja.github.io/)はワークショップの準備に集中することが出来ました。対応がいつも丁寧かつプロフェッショナルでした。パートナーは大事です。　

### オンラインで行うワークショップの知識を生かす

今回のワークショップは新型コロナウイルスによってワークショップがオンラインに移り始めてからちょうど一年目というタイミングで行いました。その間に、カーペントリーズのコミュニティーからワークショップをオンラインで行う上でのヒント・アドバイスが色々挙げられました[^links]。インストラクターのためのオンラインで[ワークショップを行うワークショップもあります](https://carpentries.github.io/instructor-training-bonus-modules/01-online-workshops-module-1/index.html)！この資料を大いに参考にさせていただきました。そして、参加者もかなりすでにオンライン（zoom）に慣れていましたので、割とスムーズに行きました。

### 練習と準備

しかし、ヒントだけでは出来ません。ワークショップの前に２回ほど全員（インストラクター２人、ヘルパー４人）でミーティングをして、インストラクターだけで４−５回くらい練習会をしました。オンラインでワークショップを行うと本当に複雑ですから、落とし穴だらけです。何回も練習したら、ブログポストを読むだけでは分からないことを色々に気付きました。そして、毎回セッションが終わった後にインストラクターやヘルパーで30分くらい反省点など話し合うことによって次回の内容の調整ができました。

## 赤い付箋

### 教える内容が混乱した

元々は唯一今まで翻訳が完成したレッスンの[「R for Reproducible Scientific Analysis」](https://swcarpentry-ja.github.io/r-novice-gapminder/ja/)を教えることを前から決まっていましたが、参加者は主に文系の大学院生で、時間も短かったでした（全５回、２時間ずつ）。そう考えると、Rの基礎を丁寧に教えるSWCスタイルよりも、なるべく早く実際に応用できるデータ・カーペントリーの[「Data Analysis and Visualization with R for Social Scientists」](https://datacarpentry.org/r-socialsci/)の方がふさわしいことに気付きました。が、データ・カーペントリーのレッスンはまだ日本語訳が出来ていなかったので、最終的には翻訳済のR for Reproducible Scientific Analysisの用語を使いながら、教える内容をデータ・カーペントリーのレッスンのように教えることにしました（例えば、ベースRよりもtidyverseから使う、など）。ちょっと混乱しましたが、最終的はこのようにして良かったと思います。理想的にはいつか、他のレッスンも翻訳したいところです！

### オンラインで教えられる内容が限られている

オンラインのワークショップだと、教えられる内容が大幅に減ることを予想しましたので、レッスンの内容はかなり軽く設定しました。それにしても、４回目ではパイプ、`dplyr::group_by()`、`dplyr::summarize()`を全部教えようとしたら、これは流石に多すぎました。この三つのコンセプトはどれも初心者にかなり難しいので、もっと時間が必要だと反省しています。

## まとめ

初日本語SWCワークショップは全体的に上手く行ったと思います。翻訳が完成したレッスンは今のところ一つしかないことで多少困りましたが、近い将来に他のレッスンもどんどん翻訳したいと思います。皆様から日本語でのカーペンターズのコミュニティーのご参加をお楽しみにしています！

## ご参加の仕方

- ツイッター： [@swcarpentry_ja](https://twitter.com/swcarpentry_ja)
- フェースブック： [carpentries.ja](https://www.facebook.com/carpentries.ja)
- ギットハブ: [swcarpentry_ja](https://github.com/swcarpentry-ja)
 
スラックチャンネルもあります (日本語でも英語でも大丈夫です)。[ここ](https://carpentries-ja.herokuapp.com/)からご参加ができます。

どなたでもレッスンの翻訳に貢献できます。もしギットハブ上でのワークフローについてのご質問があったら、気軽に聞いてください。どうぞよろしくお願いします！

[^links]: これらのブログポストは特に参考になりました：[Online Workshop Logistics and Screen Layouts](https://carpentries.org/blog/2020/06/online-workshop-logistics-and_screen-layouts/), [Recommendations for Teaching Carpentries Workshops Online](https://carpentries.org/online-workshop-recommendations/), [Mapping & Planning a Live Coding Workshop for Digital Delivery](https://carpentries.org/blog/2020/04/plan-map-live-coding-workshop/#my-personal-teaching-setup)
