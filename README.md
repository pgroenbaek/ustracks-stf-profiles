# USTracks STF Profiles

This is an attempt to mimic USTracks as best as possible using the Open Rails STF track profile format.

These track profiles enable use of the super-elevation feature in Open Rails together with Norbert Rieger's USTracks.

If you wish to replace dynamic tracks within a route and/or generate new track shapes, you should instead use the DPP profiles provided by Norbert with Dynatrax.


## Installation

TODO how and where to add them

This repository only contains the STF track profiles. The textures needed can be obtained from the [DBTracks package](https://the-train.de/downloads/entry/11252-DBTracks/) (USTracks is included in this).

You more than likely have the textures in your route already if you ever need these profiles for super-elevation.


## Usage

A guide on how to use these track profiles is available in the [Open Rails documentation](https://open-rails.readthedocs.io/en/latest/options.html#superelevation). 

More information about the technical aspects of STF track profiles in Open Rails is available in [this document](https://static.openrails.org/files/OpenRails-Testing-How%20to%20Provide%20Track%20Profiles%20for%20Open%20Rails%20Dynamic%20Track.pdf).


## Roadmap

The plan is to add STF profiles for all USTracks variants.

| USTracks package  | Variants to do                                   | Variants done |
|-------------------|--------------------------------------------------|---------------|
| US1               | US1b, US1h, US1he             | US1           |
| US2              | US2, US2b, US2h, US2he               |           |
| US3              | US3, US3b, US3h, US3he, US3r, US3rb, US3rh, US3rhe                              |               |






Feel free to suggest more by creating an issue, or by submitting a pull request if you want more added.


## Known issues

- Have yet to find a good way to place objects at an interval along the generated track. For example connectors between the two overhead wires for f-variants.
- When superelevation is enabled Open Rails will generally remove the existing curved track sections. But this does not happen for Dynatrax pieces that have both curved and straight sections. If such Dynatrax pieces exist in a route you will find that the superelevated sections overlap with those Dynatrax pieces (at least in Open Rails 1.5.1).


## License

These STF track profiles were created by Peter Grønbæk Andersen based on Norbert Rieger's work on USTracks and are licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/).


## Acknowledgements

In memory of Norbert Rieger.

All credit goes to Norbert as he is the author of the original USTracks shapes.