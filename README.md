Robert Reiners
Project 1

##Question 1
spark-submit --class "project_1.main" --master "local[*]" target/scala-2.12/project_1_2.12-1.0.jar this_is_a_bitcoin_block_of_51745511 2 10000000
	found. count:38908
	(1147117158this_is_a_bitcoin_block_of_51745511,00c05f3f2b83892a5526123a27786c516aa1506174b9487cad33222cc0b81419)
	Time elapsed:20s

spark-submit --class "project_1.main" --master "local[*]" target/scala-2.12/project_1_2.12-1.0.jar this_is_a_bitcoin_block_of_51745511 3 10000000
	found. count:2413
	(991567799this_is_a_bitcoin_block_of_51745511,0002e444cf72788a42599f3bcbbef382033858a49946468fa7b65c38371526f3)
	Time elapsed:20s

spark-submit --class "project_1.main" --master "local[*]" target/scala-2.12/project_1_2.12-1.0.jar this_is_a_bitcoin_block_of_51745511 4 10000000
	found. count:147
	(124247143this_is_a_bitcoin_block_of_51745511,000039e56350392c99a324cff317735b7cba2330486b5c6e9365791824271d9e)
	Time elapsed:19s

spark-submit --class "project_1.main" --master "local[*]" target/scala-2.12/project_1_2.12-1.0.jar this_is_a_bitcoin_block_of_51745511 5 10000000
	found. count:6
	(1636083248this_is_a_bitcoin_block_of_51745511,00000def1816746a2df81d7eaab326fae4c9669b9742badfa1ea7da3a1bdb990)
	Time elapsed:21s

spark-submit --class "project_1.main" --master "local[*]" target/scala-2.12/project_1_2.12-1.0.jar this_is_a_bitcoin_block_of_51745511 6 10000000
	found. count:78
	(2086194004this_is_a_bitcoin_block_of_51745511,0000004546bc39497a304a7a35829acbf6e1606f7123581d19cfcd1013d5628e)
	Time elapsed:2012s

##Question 2
GCP
this_is_a_bitcoin_block_of_51745511
7
999999999
	found. count:3
	(1094678240this_is_a_bitcoin_block_of_51745511,0000000aeb3b870eabf9d881fe526447b61c03c7fa02199c40700dee0ed1b297)
	Time elapsed:3397s

##Question 3
Non-Random
	found. count:164
	(651976365this_is_a_bitcoin_block_of_51745511,00006579b4999adb94608f4ab0fd420918ebb6c130fd134e6fd50484862090a4)
	Time elapsed:21s

This would be less efficient because the randomization increases the chance that a correct answer will be found. When the numbers are tried in order it is much more likely that there will be a string of numbers that are not correct.