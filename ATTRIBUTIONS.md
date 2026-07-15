# Attributions

The generator itself (`index.html`) is © 2026 David Krexa and licensed under the
MIT License (see `LICENSE`). It bundles the following third-party components,
which keep their own licenses.

## Simplex noise (GLSL)

The fragment shader uses the `permute` / `snoise` 2D simplex-noise functions from
**webgl-noise** by Ian McEwan (Ashima Arts) and Stefan Gustavson. These are used
under the MIT License and remain under it:

> Copyright (C) 2011 by Ashima Arts (Simplex noise)
> Copyright (C) 2011-2016 by Stefan Gustavson (Classic noise and others)
>
> Permission is hereby granted, free of charge, to any person obtaining a copy
> of this software and associated documentation files (the "Software"), to deal
> in the Software without restriction, including without limitation the rights
> to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
> copies of the Software, and to permit persons to whom the Software is
> furnished to do so, subject to the following conditions:
>
> The above copyright notice and this permission notice shall be included in all
> copies or substantial portions of the Software.
>
> THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND.

Source: https://github.com/ashima/webgl-noise / https://github.com/stegu/webgl-noise

## Demo photo (Foto-Mix)

The default second photo in the **Foto-Mix** style is a demo asset only, not part
of the licensed code:

- "Dülmen, Dernekamp, Feld -- 2018 -- 0051" by **Dietmar Rabich**
- License: **CC BY-SA 4.0** — https://creativecommons.org/licenses/by-sa/4.0/
- Source: https://commons.wikimedia.org/wiki/File:D%C3%BClmen,_Dernekamp,_Feld_--_2018_--_0051.jpg

If you reuse the code without this image (e.g. by dropping in your own photos),
the CC BY-SA obligations do not apply to your work. Replace or remove the embedded
`IMG_GRASS` data URI in `index.html` to drop it.
