# Autonomous-Driving-Level_1
A survey for Autonomous Driving Level 1
=========================================================================================================================
Slef-parking Mission
-------------------------------------------------------------------------------------------------------------------------
前処理：    

	視認性向上
  	認識前処理
  	キャリブレーション  // (Real-time Calibration)

周囲情報センシング：

	周辺路面情報：
		全周囲レーン検知
		前方レーン検知  //(Lane Detection)=====================================
			Review of Lane Detection and Tracking Algorithms In Advanced Driver Assistance System
			airccse.org/journal/jcsit/7415ijcsit06.pdf
			---------------------------------------------------------------
			[2014]Adaptive regions of interest based on HSV histograms for lane marks detection
			http://www98.griffith.edu.au/dspace/bitstream/handle/10072/61725/91721_1.pdf?sequence=1
			---------------------------------------------------------------
			[2014]Multiple Lane Boundary Detection Using A Combination of Low-Level. Image Features
			http://www.researchgate.net/publication/272148332_Multiple_lane_boundary_detection_using_a_combination_of_low-                         level_image_features
			---------------------------------------------------------------
			[2014]Robust lane detection and tracking based on novel feature extractionand lane categorization
			http://www.mirlab.org/conference_papers/International_Conference/ICASSP%202014/papers/p8179-ozgunalp.pdf
			---------------------------------------------------------------
			[2013]An Efficient Lane Detection Algorithm For Lane Departure Detection
			http://dspace.kaist.ac.kr/bitstream/10203/188028/1/79112.pdf
			---------------------------------------------------------------
			[2013]Gradient-enhancing conversion for illumination-robust lanedetection
			**
			---------------------------------------------------------------
			[2013]Annealed Particle Filter Algorithm Used for Lane Detection and Tracking
			http://www.joace.org/uploadfile/2013/0506/20130506040205524.pdf
			---------------------------------------------------------------
			[2013]Stochastic Lane Shape Estimation Using Local Image Descriptors
			http://www.dpi.physik.uni-goettingen.de/cns/modules/BibtexModule/uploads/PDF/liuwoergoettermarkelic2012.pdf
			---------------------------------------------------------------
			
			---------------------------------------------------------------
			---------------------------------------------------------------
			---------------------------------------------------------------
			---------------------------------------------------------------
			
			
			
			
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
  
