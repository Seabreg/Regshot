
Readme file of Regshot 1.9.0 (2013-02-02)

-----------------
Introduction:
-----------------
Regshot is a small, free and open-source registry compare utility that allows you to quickly
take a snapshot of your registry and then compare it with a second one - done after doing
system changes or installing a new software product. The changes report can be produced in
text or HTML format and contains a list of all modifications that have taken place between
the two snapshots. In addition, you can also specify folders (with subfolders) to be
scanned for changes as well.
(Most of above text was copied from webattack.com, thanks :)


-----------------
Usage:
-----------------
(1) Click the "1st shot" button
It pops up a menu which contains several items:
 (A) "Shot", to take a snapshot only, and it will not be kept if you exit Regshot program;
 (B) "Shot and save...", to take a snapshot of your registry and save the whole registry to
     a "hive" file and you can keep it in your hard disk for future use;
 (C) "Load...", to load a "hive" file previous saved.
If you want to monitor your file system, just check the "Scan Dir [dir..]" checkbox
and input the folder names below it. Note: Regshot has the ability to scan multiple
folders, just separate them with ";", Regshot will also scan the subfolders of the current
folders you entered.

(2) Run any program that may change your windows registry or the file system

(3) Click the "2nd shot" button

(4) Select your output LOG file type, "text" or "HTML", default is "text"

(5) Enter your comment for this action into the "comment field", e.g.: "Changes made after
winzip started". The comment will only be saved into the comparison log files not into "hive" files

(6) Click the "Compare" button
Regshot will do the comparison job now (auto detect which shot is newer), when it is finished,
Regshot will automatically load the comparison log as you defined above, the log files are
saved  in the directory where "Output path" is defined, default is your Windows Temp Path,
it was named as the "comment" you input, if the "comment field" is empty or invalid, the
log will be name as "~resxxxx.txt" or "~resxxxx.htm" where "xxxx" is 0000-9999.

(7) Click the "Clear" button
The two snapshots (or separately) previous made will be cleared and you can begin a new job.
Note: "Clear" does not erase the log files!

(8) To quit Regshot, just click the "Quit" button

(9) You can change the language of the Regshot at main window, all words are saved in the
file "language.ini". View it for details!

(10) New to 1.7: regshot.dat now changed to regshot.ini, skip dirs and skip registry keys
are included. The executable's size is smaller!

(11) New to 1.8:
File shots are now saved in hive file.
"UseLongRegHead" option added in regshot.ini to compatible with undoReg (1.46)
"UseLongRegHead=1" means using "HKEY_LOCAL_MACHINE" instead of "HKLM", default 0
Do not compare shots saved with different "UseLongRegHead" option! (limit gone in 1.9.0)

(12) New to 1.9.0:
x64 and Unicode versions.
You can compare shots saved with different "UseLongRegHead" option.
Loading ANSI hive files in Unicode builds and vice versa is not supported.


-----------------
Thanks:
-----------------
Alexander Romanenko   -- Former space provider! http://www.ist.md/
Ivan                  -- Former space provider! http://www.digitalnuke.com/
Toye                  -- Release!
zhangl                -- Debug!
firstk                -- Debug!
mssoft                -- Test!
dreamtheater          -- Test!
Gonzalo               -- Spanish
ArLang°¢ÀÉ            -- Chinese
Mikhail A.Medvedev    -- Russian[Thanks!]
Kenneth Aarseth       -- Norsk
Marcel Drappier       -- French
Vittorio "Capoccione" -- Italian
Gnatix                -- Deutsch
Murat KASABOGLU       -- Türkçe
Paul Lowagie          -- Nederlands
ondra                 -- Èesky
AVE7                  -- Fixed Deutsch!
Pau Bosch i Crespo    -- Catalan
Michael Papadakis     -- Greek
Per Bryldt            -- Danish
Rajah                 -- Latvian
Leandro               -- Portuguese
Roland Turcan         -- Slovak
Kentaro Okude         -- Japanese
Adam Mikusiñski       -- Polish
Computer Wizard[Wiz]  -- Serbian
Jack Gorji             -- Hebrew
Xos?Antón Vicente Rodríguez --Galego
Obelix                -- Hrvatski
Alex Simidchiev       -- Bulgarian
joup@algonet.se       -- Svenska
Bata György           -- Hungarian
Dmitry P.             -- Ukrainian
Mr Anonyme,Charles    -- French Update
kazakh                -- Erzhan Erbolatuly

Nick Reid             -- Advice
tongjiawang           -- Many help!

Franck Uberto, Patrick Whitted, Walter Bergner, Jim McMahon, Fred Bailey,
Dchenka, itschy, HANDLE and all those we forgot to mention!!


-----------------
LICENSE:
-----------------

Copyright 2011-2013 The Regshot Team : TiANWEi, Maddes, XhmikosR
Copyright 1999-2003,2007,2011 TiANWEi
Copyright 2004 tulipfan
Copyright 2007 Belogorokhov Youri

* License remark:
* TiANWEi - Original Author of Regshot, 1999-now
* Maddes  http://www.maddes.net/ - Coder and Maintainer, 2011-now
* XhmikosR - Coder and Maintainer, 2011-now
* Tulipfan (tfx) was the Designer & Coder of "Skiplist functions, regshot.ini setup, REGSHOT_TITLE define", he made the release 1.7.
* Belogorokhov Youri (HANDLE) was the contributor of "a better html color idea, a new style browse dialog function" in 1.8.

Multi-language translations are the property of their respective owner.

Regshot is free software; you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation; either version 2 of the License, or
(at your option) any later version.

Regshot is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with Regshot; if not, write to the Free Software
Foundation, Inc., 51 Franklin St, Fifth Floor, Boston, MA  02110-1301  USA

-----------------
The Regshot Team:
-----------------
http://sourceforge.net/projects/regshot/
