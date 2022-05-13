# Test Cases and Corresponding Output
## High Level Test Cases 
Test ID |	Description |	Exp.i/p |	Exp.o/p |	Actual o/p |	STATUS
-- | -- | -- | -- | -- | --
1	| check if the Button is pressed |	program execution |	Microcontroller/Engine starts  |	LED ON(RED) |	PASS
2 |	check if the Button is pressed |	program execution	| Wiper starts	| LED ON(BLUE)   | PASS
3 |	check if the Button is pressed	| program execution	| Wiper starts	| LED ON(GREEN)	 | PASS
4 |	check if the Button is pressed |	program execution | Wiper starts	| LED ON(ORANGE) | PASS
5	| check if the Button is pressed	| -	| Microcontroller/Engine stops	| LED TURNED OFF | PASS
## Low Level Test Cases 
Test ID |	Description |	Exp.i/p |	Exp.o/p |	Actual o/p |	STATUS
-- | -- | -- | -- | -- | --
1	| check if the Button is pressed |	program execution |	Microcontroller/Engine starts  |	LED ON(RED) |	PASS
2 |	check if the Button is pressed again |	program execution	| Wiper starts and speed of wiper is low	| LED ON(BLUE)   | PASS
3 |	check if the Button is pressed	again | program execution	| Wiper starts and speed of wiper is medium	| LED ON(GREEN)	 | PASS
4 |	check if the Button is pressed again |	program execution | program execution Wiper starts and speed of wiper is good	| LED ON(ORANGE) | PASS
5	| check if the Button is pressed	again | -	| Microcontroller/Engine stops	| LED TURNED OFF | PASS
