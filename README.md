# mapdb
**Kaldonis-moderated mapdb reviewed by bona fide map editors.**

## 3 April 2021 - various works
1) Updated Cysaegir graphics, new Stables room, supernode tags, bar RP entry fixed.
2) Updated Halcyon Hills graphics, added new rooms
3) All the Beacon Hall lockers and tags that were missing
4) All public rooms on gswiki that are supernodes are now tagged
5) All rooms on Western Dragonspine had check_location turned off
6) A couple paths around IMT/Pinefar now have adjectives to avoid warcamps
7) IMT public lockers can now ;go2 from town, etc

## Edit by anonymous
Seems sane, but we do not know who grabbed the mapdb (which we have been trying to prevent). 
___
16745 [Aradhul Road, Rocky Trail]
timeto: {"16744"=>0.2, "16746"=>15000} is now {"16744"=>0.2, "16746"=>15}
___
16746 [Aradhul Road, Rocky Trail]
timeto: {"16745"=>15000, "16747"=>0.2} is now {"16745"=>15, "16747"=>0.2}

## 4 April 2021 - FWI CHE lockers
Any CHE with an existing FWI Annex room but *not* a dedicated, unique locker room now has one!  CHEs that already had unique lockers were not modified (except one entry door), and CHEs without entry areas missed out on this update, because a non-member has no way to obtain the room description.

For full details, see https://pastebin.com/MhpSVd47
___
###[Annex, Cairnfang Manor Lobby]
Entry area: 22227 
Fixed entry door adjective (ivory), in case a new CHE was ever added.
___
###[Annex, White Haven Lobby]
Entry area: 21324 

Duplicate: 25997 -- merged to above room

**Same Locker: 25998**

White Haven gets to keep Kaldonis's StringProc for auto-closing lockers.  Lucky devils!
___
###[Annex, Rone Academy Lobby]
Entry area: 25901

**New Locker: 25997** (the room number was previously a White Haven duplicate)
___
###[Annex, House Sylvanfair Lobby]
Entry area: 28224 

**New Locker: 29569**

___
###[Annex, Willow Hall Lobby]
**New Entry area: 29568**, tagged: `;go2 WillowHall`

**New Locker: 29570**
___
###[Annex, House Brigatta Lobby]
Entry area: 24210 

**New Locker: 29571**
___
###[Annex, House Sovyn Lobby]
Entry area: 25885 

*NB: This room was probably already broken*; this should fix it: @paths=["Obvious exits: out", "Obvious exits: none"]

**New Locker: 29572**
___
###[Annex, Silvergate Inn Lobby]
Entry area: 27634 

**New Locker: 29573**

Tagged: `;go2 sglocker`

___
We add tags like the following style:

;e echo Room[29573].tags.push('peer curtain =~ /^\\[Annex, Silvergate Lobby\\]$/')
