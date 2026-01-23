<h2 class="c-project-heading--task">Open and read from a file</h2>
--- task ---
BRIEF SUMMARY OF STEP - one line
--- /task ---

--- task ---

Open the `insults.csv` file and look at the contents. 

![The code editor sidebar with a pink arrow pointing to the file 'insults.csv'](images/insults.png){:style="width:50%;"}

--- /task ---
<h2 class="c-project-heading--explainer">PROBABLY UNNECCESARY TITLE</h2>

Click back on the `main.py` file. 

Add code to open `insults.csv` in read mode `"r"`, read all of the contents and output the result:

<div class="c-project-code">
--- code ---
---
language: python
filename: main.py
line_numbers: true
line_number_start: 1
line_highlights: 
---
with open("insults.csv", "r") as f:
  lines = f.readlines()
  print(lines)
--- /code ---
</div>

<div class="c-project-output">
<pre>['artless,base-court,apple-john\n', 'bawdy,bat-fowling,baggage\n', 'beslubbering,beef-witted,barnacle\n', 'bootless,beetle-headed,bladder\n', 'churlish,boil-brained,boar-pig\n', 'cockered,clapper-clawed,bugbear\n', 'clouted,clay-brained,bum-bailey\n', 'craven,common-kissing,canker-blossom\n', 'currish,crook-pated,clack-dish\n', 'dankish,dismal-dreaming,clotpole \n', 'dissembling,dizzy-eyed,oxcomb\n', 'droning,doghearted,codpiece\n', 'errant,dread-bolted,death-token\n', 'fawning,earth-vexing,dewberry\n', 'fobbing,elf-skinned,flap-dragon\n', 'froward,fat-kidneyed,flax-wench\n', 'frothy,fen-sucked,flirt-gill\n', 'gleeking,flap-mouthed,foot-licker\n', 'goatish,fly-bitten,fustilarian\n', 'gorbellied,folly-fallen,giglet\n', 'impertinent,fool-born,gudgeon\n', 'infectious,full-gorged,haggard\n', 'jarring,guts-griping,harpy\n', 'loggerheaded,half-faced,hedge-pig\n', 'lumpish,hasty-witted,horn-beast\n', 'mammering,hedge-born,hugger-mugger\n', 'mangled,hell-hated,jolthead\n', 'mewling,idle-headed,lewdster\n', 'paunchy,ill-breeding,lout\n', 'pribbling,ill-nurtured,maggot-pie\n', 'puking,knotty-pated,malt-worm\n', 'puny,milk-livered,mammet\n', 'quailing,motley-minded,measle\n', 'rank,onion-eyed,minnow\n', 'reeky,plume-plucked,miscreant\n', 'roguish,pottle-deep,moldwarp\n', 'ruttish,pox-marked,mumble-news\n', 'saucy,reeling-ripe,nut-hook\n', 'spleeny,ough-hewn,pigeon-egg\n', 'spongy,rude-growing,pignut\n', 'surly,rump-fed,puttock\n', 'tottering,shard-borne,pumpion\n', 'unmuzzled,sheep-biting,ratsbane\n', 'vain,spur-galled,scut\n', 'venomed,swag-bellied,skainsmate\n', 'villainous,tardy-gaited,strumpet\n', 'warped,tickle-brained,varlet\n', 'wayward,toad-spotted,vassal\n', 'weedy,urchin-snouted,whey-face\n']</pre>
</div>

<div class="c-project-callout c-project-callout--tip">




