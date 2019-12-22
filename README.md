# Chess-Testmedia
Testmedia (video and images) for chess board recognition <br />

TK_scholarsmate1.avi - Travel Chess Set, autofocus, variable gain, contrast and brightness <br />
TK_scholarsmate2.avi - Travel Chess Set, autofocus, variable gain, contrast and brightness <br />
TK_legalsmate1.avi   - Travel Chess Set, autofocus, variable gain, contrast and brightness <br />
<br />
TK_scholarsmate3.avi - Travel Chess Set, no autofocus, fixed gain and brightness <br />
TK_scholarsmate4.avi - Travel Chess Set, no autofocus, fixed gain and brightness <br />
<br />
TK_scholarsmate7.avi - Tournament Chess Set, no autofocus, fixed gain and brightness <br />
TK_Trompowsky.avi    - Tournament Chess Set, no autofocus, fixed gain and brightness <br />
<br />
These Videos work as of Dec 22nd 2019:<br />
scripts/run --input testMedia/TK_scholarsmate30.avi --warp '[[80,20],[273,17],[270,203],[88,203]]' --debug --nomoves --rotation 90<br />
scripts/run --input testMedia/TK_scholarsmate29.avi --warp '[[167,41],[544,39],[544,408],[167,407]]' --debug --nomoves --rotation 90<br />
scripts/run --input testMedia/TK_scholarsmate27.avi --autowarp --debug --nomoves --rotation 90<br />
<br />
all other Videos are of bad quality for move detection. You could try anyway... e.g.:<br />
scripts/run --input testMedia/TK_scholarsmate28.avi --warp '[[167,41],[544,39],[544,408],[167,407]]' --debug --nomoves --rotation 90<br />
scripts/run --input testMedia/TK_scholarsmate25.avi --warp '[[531,84],[1374,81],[1363,919],[544,909]]' --debug --nomoves --rotation 90<br />
scripts/run --input testMedia/TK_scholarsmate26.avi --autowarp --debug --nomoves --rotation 90<br />
<br />
