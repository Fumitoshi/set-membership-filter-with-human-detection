MATLABファイル
・setmembershipfilter5cameras.m:5台のカメラで集合値オブザーバにより歩行者の位置の予測・推定を行うもの

	・cal_3ell_intersection.m:3つの楕円体の共通部分を囲む体積最小の楕円体を計算する関数
	・cal_2ell_intersection.m:2つの楕円体の共通部分を囲む体積最小の楕円体を計算する関数
	・cal_quaternion.m:回転行列からクォータニオンを計算する関数
	・h.m:透視投影モデルに基づいた3次元空間上から2次元画像平面への写像を与える関数
	・movie_make.m:複数の画像から動画を作るもの
	・myfun.m:共通部分を囲む体積を最小化するための目的関数

・SMFfinalreverse.m:5台のカメラで集合値オブザーバにより歩行者の位置の予測・推定を行うものに速度に関する補正を行ったもの

data:MATLABとBlenderを連携させるためのtxtファイルを置くところ

Blenderファイル
・setmembershipfilterfinalcamera_reverse_including_velocity_revision.blend:Blenderのファイル。カメラの位置や歩行者の歩行軌跡などを直感的に決めることができる．こちらで直感的に決めた後にmatlab内の数値を書き換えなくてはいけない。


実行後して出力された画像データから作成した動画ファイルは以下のDriveにある
https://drive.google.com/open?id=0B_zKOj4hxvlEZmpSWU9uQ1o3R28