# LanguageLearningTools
In this repository you can find tools that can be used for language learning.

Currently you can find:

## 01 - SubtitleConverter (OpenSource) - XML to TXT

This code allows you to input a XML subtitle file and convert it into a TXT file as output. 
The resulting text file will have timestamps removed and broken sentences joined into single, coherent sentences. 
The output is a clean, readable text file.
I created this code to support my language learning journey, allowing me to easily process subtitles extracted from TV series or movies.

### Example:
Input:
<p xml:id="subtitle174" begin="6790833334t" end="6811666667t" region="region0"><span style="style1">Min lillebror gik i klasse</span><br/><span style="style1">med ham i folkeskolen,</span></p>
<p xml:id="subtitle175" begin="6812500000t" end="6831666667t" region="region0"><span style="style1">og så er hans mor min fars grandkusine.</span></p>
<p xml:id="subtitle176" begin="6839583334t" end="6852500000t" region="region0"><span style="style1">-Nå, hvor sjovt.</span><br/><span style="style1">-[kvinde] Ja.</span></p>
<p xml:id="subtitle177" begin="6857916667t" end="6867916667t" region="region0"><span style="style1">[skoleklokke ringer]</span></p>
<p xml:id="subtitle178" begin="6868750000t" end="6881666667t" region="region0"><span style="style1">Nå, vi må hellere…</span></p>
<p xml:id="subtitle179" begin="6882500000t" end="6917916667t" region="region0"><span style="style1">Held og lykke med det.</span><br/><span style="style1">Og hils Morten. Karen Møller.</span></p>
<p xml:id="subtitle180" begin="6918750000t" end="6938333334t" region="region0"><span style="style1">Det skal jeg gøre. Og jeg hedder Pernille.</span></p>
<p xml:id="subtitle181" begin="6939166667t" end="6964583334t" region="region0"><span style="style1">Det ved jeg godt.</span><br/><span style="style1">Held og lykke på sygehuset.</span></p>
<p xml:id="subtitle182" begin="6981666667t" end="6992083334t" region="region0"><span style="style1">Tak.</span></p>
<p xml:id="subtitle183" begin="6992916667t" end="7017500000t" region="region0"><span style="style1">[Pernille] Ja, kom.</span><br/><span style="style1">Lad os finde dit klasselokale.</span></p>

Output:
Min lillebror gik i klasse med ham i folkeskolen, og så er hans mor min fars grandkusine.
-Nå, hvor sjovt.
-Ja.
Nå, vi må hellere…
Held og lykke med det.
Og hils Morten. Karen Møller.
Det skal jeg gøre. Og jeg hedder Pernille.
Det ved jeg godt.
Held og lykke på sygehuset.
Tak.
Ja, kom.
Lad os finde dit klasselokale.


## 02 - SubtitleConverter (OpenSource) - VTT to TXT

This code allows you to input a VTT subtitle file and convert it into a TXT file as output. 
The resulting text file will have timestamps removed and broken sentences joined into single, coherent sentences. 
The output is a clean, readable text file.
I created this code to support my Gaelic-Irish learning journey, allowing me to easily process subtitles extracted from Irish-language TV series like Ros na Rún and Saol Ella, both available on TG4.

### Link to Ros na Rún: 
https://www.tg4.ie/en/player/online-boxsets/?series=Saol%20Ella&genre=Cula4
### Link to Saol Ella: 
https://www.tg4.ie/en/player/categories/drama-tv-shows/?series=Ros%20na%20R%C3%BAn&genre=Drama

### Example:
Input:
08:57.280 --> 09:00.200
Cruinniú clainne
faoi cheann 10 nóiméad.

09:05.240 --> 09:07.280
Bhuel, dá gcloisfeá í.

Output:
Cruinniú clainne faoi cheann 10 nóiméad.
Bhuel, dá gcloisfeá í

