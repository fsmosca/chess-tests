# Chess tests
Computer chess program test results on different test suites such as positional, tactical, opening, middle and ending phases of the game. Engines are run on single thread at 5s/position analysis time.

[Test results](https://fsmosca.github.io/chess-tests/)

![](https://i.imgur.com/CRSj64P.png)

### Test sets

* Arasan20.epd<br>
Author: Jon Dart<br>
Category: Tactical<br>
Number of positions: 200<br>
Description: Not an easy test set for most engines at fast time and single thread. It also contains 16 ending positions.<br>
Download: [Arasan20.epd](https://www.arasanchess.org/testsuite.shtml)
* OTSv4.epd<br>
Author: Sedat Canbaz<br>
Category: Opening<br>
Number of positions: 400<br>
Description:<br>
Download: [OTSv4.epd](https://sites.google.com/site/computerschess/ots-v4-ranking)
* ssm_4_5_men.epd<br>
Author: Sergei Markoff<br>
Category: Ending<br>
Number of positions: 391<br>
Description: 4 and 5 men ending, modified by me selecting only those with single bm also added some opcodes.<br>
Download: [ssm_4_5_men.epd](https://drive.google.com/file/d/1s8yNKYQNkJ7XwiHiDMYCnT2yOtnpyGfp/view?usp=sharing)
* midgames250.epd<br>
Author: Kai Laskos<br>
Category: Positional<br>
Number of positions: 250<br>
Description: Middle phase positions based from human games around move 15 to 22.<br>
Download: [midgames250.epd](http://talkchess.com/forum3/download/file.php?id=414)
* ecmgcp.epd<br>
Author: <br>
Category: Middle<br>
Number of positions: 183<br>
Description: Encyclopedia of Chess Middlegames<br>
Download: [ecmgcp.epd](http://www.arasanchess.org/tests.zip)

### Conditions
* Each position is analyzed at 5s or 5000ms
* Engine is set to use 1 thread and 256 MB hash
* End Game Tablebases are not used
* System: Processor i7-2600K 3.4 Ghz 12GB RAM, Windows 7 Prof. OS

### Credits
* [Datatables ](https://datatables.net/)
