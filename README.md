# Autonomous-Driving-Level_1
A survey for Autonomous Driving Level 1
=========================================================================================================================
Slef-parking Mission

前処理：    
  視認性向上
  認識前処理
  キャリブレーション  // (Real-time Calibration)

周囲情報センシング：
	周辺路面情報：
		全周囲レーン検知
		前方レーン検知  //(Lane Detection)
		駐車枠認識
		路面認識・立体物認識  //(Road Region Detection)
		（交差点認識）
		
	周辺車両情報：
		車両認識  //(Vehicle Recognition)
		車両動線予測  //(Vehicle Pridection)
		二輪車認識  //(Two-wheel Recognition)
		二輪車動線予測  
		
	周辺歩行者情報：
		歩行者認識  //(Pedestrian Detection)
		歩行者動線予測  //(Pedestrian Moving Preditecting)
		
	その他異動物：
		移動物認識  //(Moving Object Detection)
		（灯火検知）
		
	自車位置情報：
		Visual　Odometry  //(SfM/ SLAM)
		自車位置補正
		自車現位置演算
		
	信号・標識情報：
		信号・標識（状態、意味、位置）
  
