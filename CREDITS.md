# Credits & sources

Voyager 1 Explorer is an independent, non-commercial study. It is **not affiliated with or endorsed by NASA or JPL**. No NASA insignia is used.

## 3D model and images

| File(s) | Content | Source | Credit / terms |
|---|---|---|---|
| `app/assets/voyager.gltf.json`, `app/assets/model_tex*` | Voyager 3D model (converted from glTF binary to glTF JSON, textures re-encoded) | [NASA 3D Resources](https://science.nasa.gov/3d-resources/) | NASA/JPL-Caltech · [NASA Images and Media Usage Guidelines](https://www.nasa.gov/nasa-brand-center/images-and-media/) |
| `app/assets/record-cover-disc.jpg`, `app/assets/record-panel.jpg` | Golden Record cover (“Instructions for Aliens”), cropped | [nasa.gov](https://www.nasa.gov/image-detail/the-sounds-of-earth-record-cover) | NASA/JPL-Caltech |
| `app/assets/record-disc-back.jpg` | Golden Record disc, “The Sounds of Earth”, cropped | [science.nasa.gov](https://science.nasa.gov/image-detail/voyager-gold-record-front) | NASA/JPL-Caltech |
| `app/assets/pre-sunrise.jpg` | Orbital sunrise seen from the International Space Station, cropped to 16:9 | NASA image library | NASA |
| `app/assets/bg-jupiter.jpg` | Jupiter rendered as a lit globe from an equirectangular texture, plus a generated starfield | Texture: [Solar System Scope](https://www.solarsystemscope.com/textures/) | © Solar System Scope, [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) – changes: projected onto a sphere, relit, cropped and darkened |
| `assets/shot-*.jpg`, `assets/og-image.jpg` | Screenshots of this presentation | – | Contain the material listed above |

## Mission facts

- NASA Science – [Voyager 1: What Is a Light-Day?](https://science.nasa.gov/mission/voyager/voyager-1/voyager-1-what-is-a-light-day/) (milestone time Nov 18, 2026, 5:16:07 a.m. EST; 16,094,799,096 mi / 25,902,068,356 km)
- NASA Science – [Where Are Voyager 1 and Voyager 2 Now?](https://science.nasa.gov/mission/voyager/where-are-voyager-1-and-voyager-2-now/)
- NASA Voyager blog – [NASA Shuts Off Instrument on Voyager 1 to Keep Spacecraft Operating](https://science.nasa.gov/blogs/voyager/2026/04/17/nasa-shuts-off-instrument-on-voyager-1-to-keep-spacecraft-operating/) (Apr 17, 2026)
- NASA Science – [The Golden Record Cover](https://science.nasa.gov/mission/voyager/golden-record-cover/)
- NASA Science – [Voyager mission overview](https://science.nasa.gov/mission/voyager/)

The distance counter is an approximation anchored to NASA's light-day figure (see the comment in `app/index.html`). It is not an ephemeris.

## Software and fonts

| Component | Version | License |
|---|---|---|
| [three.js](https://threejs.org/) (`app/lib/three.module.js`, `app/lib/jsm/`) | r169 | MIT |
| [Inter](https://rsms.me/inter/) (`app/lib/fonts/inter-*`) | via @fontsource/inter 5.1.0 | SIL Open Font License 1.1 |
| [IBM Plex Mono](https://github.com/IBM/plex) (`app/lib/fonts/ibm-plex-mono-*`) | via @fontsource/ibm-plex-mono 5.1.0 | SIL Open Font License 1.1 |

The ambient sound is synthesized in the browser with the Web Audio API; no audio files are used.
