# Stroke data

The stroke-order data used in [CantoPass](https://cantopass.com), the Hong Kong Cantonese app.

It is a modified version of [Make Me a Hanzi](https://github.com/skishore/makemeahanzi)'s stroke data (via
[hanzi-writer-data](https://github.com/chanind/hanzi-writer-data) 2.0.1), which was made from Arphic's fonts and is under
the **Arphic Public License** ([ARPHICPL.TXT](ARPHICPL.TXT)). As that licence asks, the modified version is free for
anyone to copy, change and share under the same licence.

- [strokes.json](strokes.json): the data. Its `_notice` entry says what was changed and when.
  Each other key is a character: `s` holds each stroke's outline as an SVG path, `m` its centre line, in a 1024 box
  with y pointing down, strokes in writing order.
- [ARPHICPL.TXT](ARPHICPL.TXT): the licence, unaltered.
