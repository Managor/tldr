# pacman --database

> ஆர்ச் லினக்ஸ் தொகுப்பு தரவுத்தளத்தில் செயல்படவும்.
> நிறுவப்பட்ட தொகுப்புகளின் சில பண்புகளை மாற்றவும்.
> இதையும் பார்க்கவும்: `pacman`.
> மேலும் விவரத்திற்கு: <https://manned.org/pacman.8>.

- ஒரு தொகுப்பை மறைமுகமாக நிறுவியதாகக் குறிக்கவும்:

`sudo pacman --database --asdeps {{நிரல்தொகுப்பு}}`

- ஒரு தொகுப்பை வெளிப்படையாக நிறுவியதாகக் குறிக்கவும்:

`sudo pacman --database --asexplicit {{நிரல்தொகுப்பு}}`

- அனைத்து தொகுப்பு சார்புகளும் நிறுவப்பட்டுள்ளதா என சரிபார்க்கவும்:

`pacman --database --check`

- அனைத்து குறிப்பிட்ட சார்புகளும் உள்ளனவா என்பதை உறுதிசெய்ய, களஞ்சியங்களைச் சரிபார்க்கவும்:

`pacman --database --check --check`

- பிழை செய்திகளை மட்டும் காட்டு:

`pacman --database --check --quiet`

- உதவியைக் காட்டு:

`pacman --database --help`
