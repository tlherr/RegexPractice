# Regex Golf
## https://alf.nu/RegexGolf

### Classic

#### Warmup
| Match   | No Match |
|---------|----------|
| afoot   | Atlas    |
| catfoot | Aymoro   |
| dogfoot | Iberic   |
| fanfoot | Mahran   |
| foody   | Ormazd   |
| foolery | Silipan  |
| foolish | altared  |
| fooster | chandoo  |
| footage | crenel   |
| foothot | crooked  |
| footle  | fardo    |
| footpad | folksy   |
| footway | forest   |
| hotfoot | hebamic  |
| jawfoot | idgah    |
| mafoo   | manlike  |
| nonfood | marly    |
| padfoot | palazzi  |
| prefool | sixfold  |
| sfoot   | tarrock  |
| unfool  | unfold   |

```
Solution: foo
Description: Easiest to just match on the literal
```

#### Anchors

| Match        | No Match      |
|--------------|---------------|
| Mick         | Kickapoo      |
| Rick         | Nickneven     |
| allocochick  | Rickettsiales |
| backtrick    | billsticker   |
| bestick      | borickite     |
| candlestick  | chickell      |
| counterprick | fickleness    |
| heartsick    | finickily     |
| lampwick     | kilbrickenite |
| lick         | lickpenny     |
| lungsick     | mispickel     |
| potstick     | quickfoot     |
| quick        | quickhatch    |
| rampick      | ricksha       |
| rebrick      | rollicking    |
| relick       | slapsticky    |
| seasick      | snickdrawing  |
| slick        | sunstricken   |
| tick         | tricklingly   |
| unsick       | unlicked      |
| upstick      | unnickeled    |

```
Solution: ick$
Description: all of the required matches end in ick
```

#### It never ends  
###### ($ not allowed)

| Match | No Match        |
|-------|-----------------|
| fu    | futz            |
| tofu  | fusillade       |
| snafu | functional      |
|       | discombobulated |

```
Solution: u\b
Description: Have to use \b because $ not allowed, all words end in u (\b is word boundry in this case end of string)
```
