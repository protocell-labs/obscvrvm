```

     ██████╗  ██████╗  ███████╗  ██████╗ ██╗   ██╗ ██████╗  ██╗   ██╗ ███╗   ███╗
    ██╔═══██╗ ██╔══██╗ ██╔════╝ ██╔════╝ ██║   ██║ ██╔══██╗ ██║   ██║ ████╗ ████║
    ██║   ██║ ██████╔╝ ███████╗ ██║      ██║   ██║ ██████╔╝ ██║   ██║ ██╔████╔██║
    ██║   ██║ ██╔══██╗ ╚════██║ ██║      ╚██╗ ██╔╝ ██╔══██╗ ╚██╗ ██╔╝ ██║╚██╔╝██║
    ╚██████╔╝ ██████╔╝ ███████║ ╚██████╗  ╚████╔╝  ██║  ██║  ╚████╔╝  ██║ ╚═╝ ██║
     ╚═════╝  ╚═════╝  ╚══════╝  ╚═════╝   ╚═══╝   ╚═╝  ╚═╝   ╚═══╝   ╚═╝     ╚═╝
                                            
     
          O B S C V R V M  |  { p r o t o c e l l : l a b s }  |  2 0 2 2       
```

Code for a GENTK generative token on [fxhash.xyz](https://www.fxhash.xyz/) Tezos NFT platform.

You can run live generator of the collection with random seeds here:
- [O B S C V R V M (generator)](https://protocell-labs.github.io/obscvrvm/)

Collection overview on fxhash.xyz (original minting site):
- [O B S C V R V M (fxhash)](https://www.fxhash.xyz/generative/slug/o-b-s-c-v-r-v-m)

Collection overview on fxfam.xyz (better layout and filtering):
- [O B S C V R V M (fxfam)](https://fxfam.xyz/22182)

You can find a detailed description of the algorithms and code in this fx(text) article:
- [O B S C V R V M - Algorithms and Code](https://www.fxhash.xyz/article/o-b-s-c-v-r-v-m-algorithms-and-code)

# Token description

“Felix, qui potuit rerum cognoscere causas”
Virgil, from Georgica, 29 BCE

The miracle of the appropriateness of the language of mathematics for the formulation of the laws of physics is a wonderful gift which we neither understand nor deserve. OBSCVRVM, meaning “darkness” in Latin, takes this profound insight from physicist Eugene Wigner and explores it through a series of code generated spatial compositions. This collection redefines basic concepts of distance and time, with elements in the scene seemingly evolving at different spatial and temporal scales. Its universe exists on the ambiguous boundary between the cosmic and subatomic, forgoing color in place of structure, articulated through a single light source and myriad of shadows it casts on the intricate lattice geometries.

Every token is a spatial composition consisting of a frame, a central lattice and a background, layered in space like theater scenography. Many frames are narrow and take a form of a portal, some take up the whole space in between, and some are missing altogether. Background features a star field with celestial objects like stars, planets, moons, eclipses and comets. The universe of OBSCVRVM is highly ordered, with lattice-like structures imprinted in star fields that span thousands of light years. You might find shattered lattices close to ancient celestial objects like meteor fields, novas, quasars and space-time raptures. In this universe time flows unevenly, and it might take eons for destructive forces to completely disintegrate the lattice and take it to its ultimate state – heath death. Lattices themselves are formed through iterative subdivision rules from basic Platonic primitives. Special types of derived primitives called stations also appear, their origin still a mystery. Occasionally, a central lattice is missing from the composition, leaving the portal to frame a seemingly empty region of space. With over 250 calls to a random function within the code, the number of spatial configurations this generative system can produce is astoundingly large, although the collection explores only a small subset of them.

Virgil’s quote from the beginning translates to: “Fortunate them, who were able to know the causes of things”. We know little about the origin of these lattices, but through their intricate geometries, OBSCVRVM takes you on a journey to explore deep space and time and ponder over our own place in them.

LLP 🖖

__________

OBSCVRVM collection is written in JavaScript using THREE.js library for displaying instantiated 3D geometry. Generation of lattices is done using our own, open-source mesh subdivision module, which includes a custom mesh class.

Key controls:

- a : jump light angle
- f : cycle light framerate
- t : cycle light tick
- i : info
- g : start / stop gif capture
- b : white / black background
- 1 – 5 : image capture 1-5x resolution

Token looks best in live mode and 100% browser zoom. Change pixel density by changing your browser's zoom level (50% zoom doubles the pixels etc.) Tested on multiple browsers (Chrome, Firefox, Safari, Edge), devices (desktop, mobile) and operating systems (Windows, iOS). For best viewing experience, we recommend Chrome on desktop with a newer generation GPU card and enabled hardware acceleration. Due to recursive nature of geometry generation, some tokens might take much more time to generate. Please make sure the token works on your device before minting.

We were greatly inspired by Jacek Markusiewicz’s “adrift”, lunarean's “Heat Death”, and Monotau’s “Cradle” collections on fxhash, both by their approach to code as well as aesthetic synthesis of elements of their work. They motivated us to leave our code open (unminified and unobfuscated), available on public repositories (GitHub), and well documented through writing and talks so they can serve as inspiration to others. We see our support for open generative tools as a mission every generative artist should partake in.

Created in 2022 by {protocell:labs}. You can find us on Twitter - @LukaPiskorec @00000Kane00000
