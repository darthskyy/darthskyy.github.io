this is the source code to my public page, darthskyy.github.io. feel free to fork, clone, or anything you'd like. i also got it from jon barron, jonbarron.info

### specific changes
- **dynamic content loading**: 
    - added fetching from external text files for experience, publications, and miscellaneous sections
    - implemented pipe-separated (|) data format for easy content updates without touching HTML
    - publications load from data/pubs.txt with title|authors|venue|year|url|description|image format
    - experience loads from data/xp.txt with date|company|url|title|description format
    - miscellanea section:
        - each section should be its own file. the title of the section is the name of the file. use "-" to separate words in the filename not " ".
        - section loads from data/misc/section-name.txt with title|url

- **responsive design**:
    - i think it is responsive to mobile (TODO testing)

- **error handling**:
    - added proper error handling for missing data files (i think)
    - implemented fallback content when files can't be loaded

- **customization**:
    - this is a template you can change however you want
    - you can add different colours to the miscellanea section for more expressive colours.
    - custom social links (spotify, lastfm) in addition to standard academic links (i added mine because I like music)

- **accessibility improvements**:
    - simplified content updating workflow (edit .txt instead of grappling with html)
    - better indentation

\+ i just use lowercase because i find it aesthetically pleasing. you don't have to if you don't want.