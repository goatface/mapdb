# mapdb
Kaldonis-moderated mapdb mainly touched by bona fide map editors.

# 3 April 2021 - various works
1) Updated Cysaegir graphics, new Stables room, supernode tags, bar RP entry fixed.
2) Updated Halcyon Hills graphics, added new rooms
3) All the Beacon Hall lockers and tags that were missing
4) All public rooms on gswiki that are supernodes are now tagged
5) All rooms on Western Dragonspine had check_location turned off
6) A couple paths around IMT/Pinefar now have adjectives to avoid warcamps
7) IMT public lockers can now ;go2 from town, etc

# 4 April 2021 - FWI CHE lockers
22227 [Annex, Cairnfang Manor Lobby]
Fixed door adjective (ivory), in case a new CHE was ever added.
---
21324 [Annex, White Haven Lobby]
25997 [Annex, White Haven Lobby] -- squished and given to Rone locker
;mapnav merge 25997 21324
Change timeto from 12297 (outside) to 21324 (inside) to 0.2 from 2.0 because this was probably done to avoid pile-ons below, now fixed.
Same Locker: 25998
Scrap SilverGate and Sylvanfair pile-on tag, wayto, timeto
White Haven gets to keep Kaldonis's StringProc for auto-closing lockers, despite his player having no members.  Lucky devils!
---
25901 [Annex, Rone Academy Lobby]
New Locker: 25997 (was duplicate White Haven entry #)
wayto & timeto both ways
---
28224 [Annex, House Sylvanfair Lobby]
New Locker: 29569
(also, we remove the wayto and time to 25998 which was piled on)
wayto & timeto for the new locker
---
29568 [Annex, Willow Hall Lobby]
New Locker: 29570
wayto & timeto for the new locker
---
24210 [Annex, House Brigatta Lobby]
New Locker: 29571
wayto & timeto for the new locker
---
25885 [Annex, House Sovyn Lobby] 
NB: This room was probably already broken.
@paths=["Obvious exits: out"]
updated manually
;e echo Room[25885].paths.push('Obvious exits: none')
@paths=["Obvious exits: out", "Obvious exits: none"]
New Locker: 29572
wayto & timeto for the new locker
---
27634 [Annex, Silvergate Inn Lobby]
New Locker: 29573
Scrap wayto & timeto 25998 pile-on
wayto & timeto for the new locker
---
We add tags like the following style:
;e echo Room[29573].tags.push('peer curtain =~ /^\\[Annex, Silvergate Lobby\\]$/')


