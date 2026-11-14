# Dyvosvit — Ukrainian Folklore Atlas

A small, bilingual folklore explorer with 22 figures and a full 78-card folklore tarot (22 Major Arcana and 56 Minor Arcana). Search the atlas, filter figures by realm, switch between English and Ukrainian, open a short sourced story, draw a daily card, or lay a three-card past, present and future reading. Choose a serious, sarcastic, or funny reading voice. The cards have gothic frames and a layered 3D tilt (pointer on a computer, motion or touch on a phone). The layout changes for phones, tablets, and large screens. Three site themes — Folk, Classic, and Futuristic — are saved in the browser, as are your language, reversals, draw pool (Major only or full 78), and reading voice.

Play it at **https://oleksavr.github.io/ukrainian-folklore-atlas/**

On an iPhone, open that link in Safari and choose Share → Add to Home Screen if you want it on your home screen.

## Run it

No build tools or dependencies are needed. Open `index.html` in a browser, or use the GitHub Pages link above.

The app is a static site, so it also works on any ordinary static host.

## The cards

The 22 Major Arcana and 56 Minor Arcana (Wands, Cups, Swords, and Pentacles) are paired with Ukrainian folklore figures and customs. The pairings are a modern reading for reflection and for fun, not a traditional village tarot, and not a claim about fate or the supernatural. A daily card stays the same until midnight (saved in the browser). You can draw from the Majors only or from the full 78-card deck. Reversed meanings and reading voices are optional. Your language, theme, and sound preference are remembered.

## Sound

UI chimes, whooshes and sparkles are synthesized in the browser with the Web Audio API. The optional night soundscape is off until you turn sound on. It mixes a quiet looping bed of night crickets (two overlapping layers of different lengths, crossfaded so the join is hard to hear) with distant dog barks that arrive at random times, volumes, and stereo positions. There is no wind. A volume slider sits next to the sound toggle. Audio starts only after you turn sound on (a user gesture, which also satisfies iOS Safari).

### Sound credits (CC0, public domain)

Remixed for this site; attribution is not required by the licenses, but the sources are:

- Joseph Sardin, *Campaign at Night #4*, [BigSoundBank](https://bigsoundbank.com/campaign-at-night-4-s1880.html), CC0
- Joseph Sardin, *Barking dog #1*, [BigSoundBank](https://bigsoundbank.com/barking-dog-s0916.html), CC0

Files live in `audio/` as Opus/WebM plus AAC/M4A for iOS Safari.

## Chat

When two or more people are on the site at once, a small self-clearing chat can open. Messages are plain text, are never stored, and fade after about a minute. Visitors are connected peer to peer (no server of this project). There is a simple bad-word filter and a local mute. If the public discovery network is unavailable, the site shows a quiet “chat unavailable” note and keeps working.

## Images

The creature and card pictures are realistic illustrations generated with Grok Imagine. They are imaginative depictions of folklore figures and customs, not historical artworks or photographs of real beings. The home-screen icon is a crop of the Mavka illustration.

## Customize

All app content, styles, and interactions are in `index.html`, with card images in `images/` and `images/minor/`, and sound files in `audio/`. Creature summaries are paraphrased and linked to sources in the app. The collection emphasizes regional variation; it is an introduction to recorded traditions, not a claim that supernatural beings exist.

## Sources

Sources are listed on each figure’s story page and on each card. Starting points include:

- [Encyclopedia of Ukraine: Demonology](https://www.encyclopediaofukraine.com/display.asp?linkpath=pages%5CD%5CE%5CDemonology.htm)
- [Encyclopedia of Ukraine: Mavka](https://www.encyclopediaofukraine.com/display.asp?linkpath=pages%5CM%5CA%5CMavkaIT.htm)
- [Encyclopedia of Ukraine: Rusalka](https://www.encyclopediaofukraine.com/display.asp?linkpath=pages%5CR%5CU%5CRusalkaIT.htm)
- [Encyclopedia of Ukraine: Lisovyk](https://www.encyclopediaofukraine.com/display.asp?linkpath=pages%5CL%5CI%5CLisovykIT.htm)
- [Encyclopedia of Ukraine: Witch](https://www.encyclopediaofukraine.com/display.asp?linkpath=pages%5CW%5CI%5CWitch.htm)
- [Encyclopedia of Ukraine: Vampire](https://www.encyclopediaofukraine.com/display.asp?linkpath=pages%5CV%5CA%5CVampire.htm)
- [Encyclopedia of Ukraine: Kupalo festival](https://www.encyclopediaofukraine.com/display.asp?linkpath=pages%5CK%5CU%5CKupalofestival.htm)
- [Encyclopedia of Ukraine: Christmas](https://www.encyclopediaofukraine.com/display.asp?linkpath=pages%5CC%5CH%5CChristmas.htm)
- [Encyclopedia of Ukraine: Ancestor worship](https://www.encyclopediaofukraine.com/display.asp?linkpath=pages%5CA%5CN%5CAncestorworship.htm)
- [Encyclopedia of Ukraine: Harvest rituals](https://www.encyclopediaofukraine.com/display.asp?linkpath=pages%5CH%5CA%5CHarvestrituals.htm)
- [Ivan Honchar Museum: Ukrainian Worldviews and Folk Demonology](https://honchar.org.ua/en/blog/ukrainian-worldviews-and-folk-demonology-i154)
- [UkraineWorld, in partnership with the Ukrainian Institute: From Mavka to Chuhayster](https://www.ukraineworld.org/en/articles/analysis/ukrainian-mythology)
- [Great Ukrainian Encyclopedia: Molfar](https://vue.gov.ua/%D0%9C%D0%BE%D0%BB%D1%8C%D1%84%D0%B0%D1%80)
- [Great Ukrainian Encyclopedia: Didukh](https://vue.gov.ua/%D0%94%D1%96%D0%B4%D1%83%D1%85)
- [Yesypenko, Hryshchenko, and Danylyuk, “Folkloric Viy: The Chthonic in Gogol and Ukrainian Folk Demonology,” *Religions* 15, no. 1 (2024)](https://doi.org/10.3390/rel15010033)

## License

MIT. See [`LICENSE`](LICENSE).
