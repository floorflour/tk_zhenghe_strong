★このファイルはeratohoK用フランドールの口上を正常に動作するよう改変したパッチです(動作確認ver1.29.3) 修正者:第2トリプル
--------------------------------------------------------------------------------------
■概要■
サヨナキ様作成のフランドール口上をver1.29.3環境下で正常に動作するよう修正したパッチです。

_KOJO_DAILY_K11_質問.ERB
	93行目 「SKILL_FORGET_BY_NAME(対象, スキル_ジャンル_SP, "狂気")」を「SKILL_FORGET_BY_NAME(対象, スキル_ジャンル_PERSONAL, "狂気")」に
	97行目 「SKILL_LEARN_BY_NAME(対象, PERSONAL, "レーヴァテイン")」を「SKILL_LEARN_BY_NAME(対象, スキル_ジャンル_PERSONAL, 11, "レーヴァテイン")に」

-----------------------------------------------------------------
■使い方■
-----------------------------------------------------------------
同封の「11 フランドール口上」フォルダを、eratohoK ver.1.29.3eratohoKのERBフォルダにある口上フォルダにそのまま上書きしてください。

--------------------------------------------------
※加筆・修正・改造・再配布等

自分が改変・加筆した部分に関しては、全て可能です。
その余についてはライセンス及び原著作者サヨナキ様のReadmeをご確認ください。

--------------------------------------------------
※苦情・バグ報告等
したらば掲示板のera板＋eratoho総合スレにご一報ください。
常駐しておりませんので、連絡が遅くなる場合がございます。予めご了承ください。
連絡先
 twitter account:@2kh000
--------------------------------------------------
-----------------------------------------------------------------

eraに関わる皆様方のご尽力に感謝いたします。
-----------------------------------------------------------------
更新履歴
2022年4月23日	ver1.03を公開
					「_KOJO_DAILY_K11_質問.ERB」に係る記述ミスを修正して正常に起動するように
