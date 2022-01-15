TODO
====

*JJ van Zon, 2022*

[back](./)

More specific TODO lists may be in other documents.

2022-01-13 TODO GitHub Pages
----------------------------

- [x] Googling "convert markdown github to web page" leads to <a href="https://dev.to/bolajiayodeji/how-to-convert-github-markdown-files-to-a-simple-website-4e14" target="_blank">How to convert GitHub Markdown files to a simple website</a>
- [x] GitHub pages did not work yet. Waiting a while to see if it starts up automatically.
- [x] Renaming root README to have lower case extension .md helped.
- [x] Links to folders do not seem to work. Maybe also change the file extension to lower case for those readme's.
- [x] Automatic links do not seem to work. Using the syntax `[Description](https:\\my-url)` may help.
- [x] Link to Archive seemed to not work: [Piano Playing Docs](https://jjvanzon.github.io/Piano-Playing-Docs/). Adding a README.md to that folder helped.
- [x] Perhaps adding name and date to articles, now that it is in web site form it may be useful. Or perhaps only the date or only the month or year.
- [x] Horizontal lines:
    - [x] Grid rows with only dashes in it seemed to not render.
    - [x] Horizontal line `-----` seems interpreted as headings in bullet pointed lists.
    - [x] `<br/><br/>` seems an alternative for horizontal space in lists.
    - [x] `-----` formatted as inline code seems to help inside table rows.
- [x] Table layout seems applied inappropriately when using `|` in a bullet point's text. Replaced with commas `,`.
- [x] MarkDown (tables) nested in HTML tables showed the MarkDown literally inside the rendered page.
    - [x] Trying a trick `<td markdown="1">` from <a href="https://stackoverflow.com/questions/15917463/embedding-markdown-in-jekyll-html" target="_blank">here</a> helped.
- [x] Links that start with slash, seem to use the wrong base URL and makes links break
    - [x] E.g. link to "/methods/practice-schema.md" does not seem to work.
    - [x] ~~baseurl in _config.yml did not help.~~
    - [x] ~~prefixing URL with {{ site.baseurl }} made link break in places other than GitHub Pages and GitHub pages would link to the .md instead of .html.~~
    - [x] Using absolute paths to the GitHub pages html page instead as a work-around.
- [ ] No home link, like clicking on the logo.
    - [x] Back buttons instead
    - [x] Like `<a href="./">back<a>`
    - [x] Or `[back](./)` in a document
    - [x] And `[back](..)` in a folder or README.md.
    - [x] Adding everywhere.
    - [x] Testing
- [x] "(MarkDown)" with a link does not seem to mean much on the GitHub Pages. Perhaps leave it call it "Web Page" instead.
- [x] Extra title "Piano Playing Docs" might be a bit redundant.
- [x] External links to open in new tab using `<a>` tags.
- [ ] More images at top of pages?

2021-11-16 TODO
---------------

- [ ] Changing fragment numbering for:
    - [ ] Chopin Ballade Ⅱ
    - [ ] Chopin Mazurka Op. 24, No. 2
- [ ] Chopin Mazurka Op. 24, No. 2
    - [ ] Phrase structure intermezzo 1 more detailed.
    - [ ] Memorizing chords
    - [ ] See specialized [TODO](chopin-mazurka-op-24-no-2/chopin-mazurka-op-24-no-2-todo.md)
- [ ] Debussy Arabesque Ⅰ
    - [ ] __Chords & sheet music__
    - [ ] See specialized [TODO](debussy-arabesque-1/debussy-arabesque-1-todo.md)
- [ ] Mozart Sonata Facile KV 545 Part 1 
    - [ ] Simplified sheet music rework
    - [ ] May redo simplified sheet music with non-copyrighted version.
    - [ ] Might add motion symbols to finger numbers.
- [ ] Sheet Music Software
    - [ ] Trying "Neuratron AudioScore First" / "Avid Sibelius First"
- [ ] __Technique:__
    - [ ] Rehearsing Barbara Lister-Sink suggestions.
    - [ ] There may be more instructional videos from Barbara Lister-Sink:
        - [ ] <a href="https://www.youtube.com/watch?v=OjSWu8ZADzI" target="_blank">Basic Stroke</a>
        - [ ] Might still want to summarize that and add to:
        - [ ] [Barbara Lister-Sink's "Freeing the Caged Bird" Videos Summary](methods/barbara-lister-sink-freeing-the-caged-bird-videos-summary.md)
        - [ ] <a href="https://www.lister-sinkinstitute.org/freeing-the-caged-bird-dvd/#1508990586220-02706448-751f" target="_blank">DVD Contents / Ordering
        - [ ] <a href="https://www.lister-sinkinstitute.org/freeing-the-caged-bird-dvd/#1508992509585-4388e2b5-8df3" target="_blank">More Preview Videos
        - [ ] I guess you'd really just have to buy the DVD.
    - [ ] Wire in the way: might not improve technique without replacing it
    - [ ] __Piano Motion Symbols idea__
        - [x] Considering Debussy Arabesque 1 motion annotations.
        - [x] Considering whatever motions comes to mind.
        - [x] Considering "Piano curriculum" doc "Motorische techniek".
        - [x] Considering "Piano Technique Ideas" doc.
        - [x] Considering loose idea docs
        - [x] Reorganized Piano folder.
        - [x] Less harsh wording in loose idea docs
        - [x] Digitizing what I have.
        - [ ] __Systemizing more details.__
        - [ ] Considering left-over things in "Piano Technique Ideas" under "2021-11-27 Brainstorm Motion Notation".
- [ ] Pieces to play:
    - [ ] Listing of pieces that I play / have played / would like to play.
    - [x] Using <a href="https://www.youtube.com/watch?v=PCx8Xcm9l7U&t=1099s" target="_blank">100 Songs You´ve Heard And Don´t Know The Name</a>
    - [x] Making links handier (HTML-style, open in separate tab).
    - [ ] Using books in closet.
    - [ ] Using books in attic.
    - [ ] Using spotify playlists.
    - [ ] Using MIDI recordings.
    - [ ] __Adding links to media.__
- [ ] Learning a piece by ear.
- [ ] [Nord Piano Sound Selections](nord-piano-4/nord-piano-4-sound-selection-notes.md)
    - [ ] Might become more relevant once I might improvise more.