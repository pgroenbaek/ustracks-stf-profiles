# USTracks STF Profiles

These track profiles mimic USTracks as best as possible to allow use of the super-elevation feature in Open Rails with Norbert Rieger's USTracks.

If you wish to replace dynamic tracks within a route and/or generate new track shapes, you should instead use the DPP profiles provided by Norbert with Dynatrax.


## Installation
This repository only contains the track profiles. The textures for USTracks can be obtained from the [DBTracks package](https://the-train.de/downloads/entry/11252-dbtracks/).

If you ever need these profiles for super-elevation the textures required most likely are in your route already.

**NOTE:** Use of multiple profiles is only supported from testing version _T1.5.1-1390_ onwards.


### Open Rails _T1.5.1-1390_ onwards (testing version):
1. Download all the .stf files from [./TrackProfiles](./TrackProfiles) as a zip file.

2. Place all of them into the `<route folder>/TrackProfiles` folder.

Open Rails will now select track profile automatically based on the type of USTracks used in the route.

TODO about Dynatrax generated dyntrack replacements


## Usage
A more detailed guide on how to use these track profiles is available in the [Open Rails documentation](https://open-rails.readthedocs.io/en/latest/options.html#superelevation). 

More information about the technical aspects of STF track profiles in Open Rails is available in [this document](https://static.openrails.org/files/OpenRails-Testing-How%20to%20Provide%20Track%20Profiles%20for%20Open%20Rails%20Dynamic%20Track.pdf).


## Track Variants

| USTracks package  | Variants to do                                   | Variants done |
|-------------------|--------------------------------------------------|---------------|
| US1               |             | US1, US1b, US1h, US1he           |
| US2              |                | US2, US2b, US2h, US2he          |
| US3              |                               | US3, US3b, US3h, US3he, US3r, US3rb, US3rh, US3rhe              |



Feel free to suggest more by creating an issue if anything is missing.


## Known issues

- Have yet to find a good way to place objects at an interval along the generated track. For example:
	- Connectors between the rails in the US3r variants


## License

These STF track profiles were configured by Peter Grønbæk Andersen based on Norbert Rieger's original work on USTracks.

The profiles are licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/).


## Acknowledgements

In memory of Norbert Rieger.

All credit goes to Norbert as he is the author of the original USTracks shapes.