Strongest-Link
==============

Fun, collaborative Game for several NAO robots on the same network!

The first robot will ask a question to his human. If the human is right, NAO adds a candy and chooses another player whose robot is going to ask a new question...
If the human is wrong, all non-banked candies are lost and the player out. To bank, you need to touch NAO's front head sensor when he's saying your name.

How to add players
==================

To add players, please go inside the Strongest Link repository and edit list.csv file.

Left column: please add the players' names.

Middle column: please add the players' robots' IP addresses. The robots should be on the same network!

Right column: please add Yes in front of the first player, No in front of the other ones

How to add/delete questions:
============================

Please open quiz.csv in the Strongest Link repository.

Left column: questions

2nd column: Right answer

3rd column: Wrong answer

Right column: another wrong answer

Library
======

If you want to recreate the game or use some parts, you can use the StrongestLink.cbl box library for Choregraphe. 
