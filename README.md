------------------------- German---------------------------

# Ein Twitch-Chat-WLED-Controller

Steuern Sie eine WLED mit Twitch-Chat-Befehlen.

Diese Webseite hört auf Twitch-Chat-Befehle, die es ermöglichen, die WLED zu steuern. Diese Anwendung verwendet [WLED HTTP Request API](https://github.com/Aircoookie/WLED/wiki/HTTP-request-API).

Zum ausführen muss die Index.html ausgeführt werden.
Dazu den kompletten Ordner herunterladen und entpacken und die index.html im Browser öffnen oder in OBS einbinden.


## Farbe einstellen

Sagen Sie „!color RRGGBB“ (oder „#RRGGBB“) in [hexadezimaler Schreibweise](https://en.wikipedia.org/wiki/Hexadecimal) oder `!color R,G,B` wobei `R`, `G` and `B` einen Wert zwischen `0-255` haben müssen, um die Primärfarbe zu ändern.

Sie können eine Live-Demo davon im [dialogikTV Twitch Livestream-Chat] (https://www.twitch.tv/dialogikTV) sehen.

## Beispiele

HEX
```
!color 00acee (dialogikTV blau)
!color #ee00ac (rosa, beachten Sie das optionale #-Zeichen)
```
RGB
```
       RGB
!Farbe 0-255,0-255,0-255

!Farbe 255,0,0 (rot)
!Farbe 255,0,255 (lila)
!Farbe 200.255.200 (hellgrün)
```

## Einstellungseffekte

Sie können die WLED-Effekte mit dem Befehl „!fx“ ändern. (Technisch gesehen ändern diese Befehle [*Voreinstellungen*](https://github.com/Aircoookie/WLED/wiki/Presets), nicht [*Effekte*](https://github.com/Aircoookie/WLED/wiki/ Liste-der-Effekte-und-Paletten#Effekte)).

Sagen Sie „!fx <Effekt>“, wobei „Effekt“ für einen der definierten namen steht

* `android`,
* `scanner` bzw.
* `breathe`.

Um einen bestimmten Effekt auszuwählen. Sie können auch einfach „!fx“ sagen, um durch die Effekte zu schalten.




------------------------- English---------------------------

# A Twitch Chat WLED Controller

Control a WLED using Twitch chat commands.

This web page listens to Twitch chat WLED commands that allow to control the WLED. This application uses [WLED HTTP request API](https://github.com/Aircoookie/WLED/wiki/HTTP-request-API).





## Setting color

Say `!color RRGGBB` (or `#RRGGBB`) in [hexadecimal notation](https://en.wikipedia.org/wiki/Hexadecimal) or `!color R,G,B` where `R`, `G` and `B` must be a value between `0-255` to modify the primary color.

You can see a live demo of this in the [dialogikTV Twitch livestream chat](https://www.twitch.tv/dialogikTV).

## Examples

HEX
```
!color 00acee (dialogikTV blue)
!color #ee00ac (pink, note the optional # sign)
```
RGB
```
       R     G     B
!color 0-255,0-255,0-255

!color 255,0,0 (red)
!color 255,0,255 (purple)
!color 200,255,200 (light green)
```

## Setting effects

You can modify the WLED effects using the `!fx` command. (Technically, these commands change [*presets*](https://github.com/Aircoookie/WLED/wiki/Presets), not [*effects*](https://github.com/Aircoookie/WLED/wiki/List-of-effects-and-palettes#effects)).

Say `!fx <effect>`, where `effect` is

* `android`,
* `scanner` or
* `breathe`

to select a specific effect. You can also just say `!fx` to cycle through effects.
