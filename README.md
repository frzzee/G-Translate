## ![download](https://github.com/user-attachments/assets/f425bdb5-7062-4e82-a00c-3a9f364d1b0d)
## G-Translate
* Fully support **Game Guardian** regular [api](https://gameguardian.net/help/classgg.html).
* The list is updated as new languages are added.
## Features
* Translation by [google-translate](https://translate.google.com).
* Most language code parameters conform to **ISO-639** identifiers, except where noted.
* Translations from any language to any language in this list are supported.
## Usage
The [translate.lua](https://raw.githubusercontent.com/frzzee/G-Translate/refs/heads/main/translate.lua) file can be dropped into an existing project or direct by url.
#### strings(text)
```lua
strings("hello") -- return "Hello"
```
#### translate(text, systemLangCode, targetLangCode)
```lua
translate("hello", "EN", "RU") -- return "Привет"
```
#### table_translate(array)
```lua
local v = { "a", "b", "c" }
table_translate(v) -- return v
```
#### openlanglist(string)
Language options menu
```lua
openlanglist("language") -- return choice
```
