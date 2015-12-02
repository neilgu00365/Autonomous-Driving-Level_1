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
			[2013]Novel boundary　determination algorithm for lane detection
			http://140.121.135.36/publications/Novel%20Boundary%20Determination%20Algorithm%20.pdf
			---------------------------------------------------------------
			[2013]Real-time detection and classification of road lane markings
			http://sibgrapi.sid.inpe.br/rep/sid.inpe.br/sibgrapi/2013/07.05.14.27?mirror=sid.inpe.br/banon/2001/03.30.15.3 			8.24&metadatarepository=sid.inpe.br/sibgrapi/2013/07.05.14.27.43
			---------------------------------------------------------------
			[2011]Lane shape estimation using a ́partitioned particle filter for autonomous driving
			http://markelic.de/professional/Documents/LiuPapers/icra2011.pdf
			---------------------------------------------------------------
			[2011]Polar randomized hough transform for lane detection using loose constraints of parallel lines
			http://www.mirlab.org/conference_papers/International_Conference/ICASSP%202011/pdfs/0001037.pdf
			---------------------------------------------------------------
			[2012]A Learning Approach Towards Detection and Tracking of Lane Markings
			http://www.umiacs.umd.edu/~raghuram/Publications/2012_ITS_LaneDetection.pdf
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
  
