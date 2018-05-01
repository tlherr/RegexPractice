# Regex Golf
## https://alf.nu/RegexGolf

### Classic

#### Warmup

Match all of these…
afoot
catfoot
dogfoot
fanfoot
foody
foolery
foolish
fooster
footage
foothot
footle
footpad
footway
hotfoot
jawfoot
mafoo
nonfood
padfoot
prefool
sfoot
unfool

and none of these…
Atlas (no match)
Aymoro (no match)
Iberic (no match)
Mahran (no match)
Ormazd (no match)
Silipan (no match)
altared (no match)
chandoo (no match)
crenel (no match)
crooked (no match)
fardo (no match)
folksy (no match)
forest (no match)
hebamic (no match)
idgah (no match)
manlike (no match)
marly (no match)
palazzi (no match)
sixfold (no match)
tarrock (no match)
unfold (no match)

Solution: foo
Description: Easiest to just match on the literal

#### Anchors


Match all of these…
Mick
Rick
allocochick
backtrick
bestick
candlestick
counterprick
heartsick
lampwick
lick
lungsick
potstick
quick
rampick
rebrick
relick
seasick
slick
tick
unsick
upstick


Kickapoo (no match)
Nickneven (no match)
Rickettsiales (no match)
billsticker (no match)
borickite (no match)
chickell (no match)
fickleness (no match)
finickily (no match)
kilbrickenite (no match)
lickpenny (no match)
mispickel (no match)
quickfoot (no match)
quickhatch (no match)
ricksha (no match)
rollicking (no match)
slapsticky (no match)
snickdrawing (no match)
sunstricken (no match)
tricklingly (no match)
unlicked (no match)
unnickeled (no match)

Solution: ick$
Description: all of the required matches end in ick

#### It never ends  
###### ($ not allowed)

Match all of these
fu
tofu
snafu


and none of these…
✔futz (no match)
✔fusillade (no match)
✔functional (no match)
✔discombobulated (no match)

Solution: u\b
Description: Have to use \b because $ not allowed, all words end in u (\b is word boundry in this case end of string)
