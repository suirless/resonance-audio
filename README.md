# [Resonance Audio](https://developers.google.com/resonance-audio) Source Code [![Travis CI](https://travis-ci.org/resonance-audio/resonance-audio.svg?branch=master)](https://travis-ci.org/resonance-audio/resonance-audio)

This is the official open source project for the Resonance Audio SDK. This
repository consists of the full source code of the Resonance Audio C++ library,
as well as the platform integrations into [Unity](https://unity3d.com/),
[FMOD](https://www.fmod.com/),
[Wwise](https://www.audiokinetic.com/products/wwise/) and DAW tools.

Resonance Audio started as a Google product and has since graduated to open
source. It is supported by members of our [steering
committee](#steering-committee) who are also project committers.

In this document there are some quick instructions for how to build the SDK from
source code.

For more detailed documentation about using the SDK, visit our [developer
docs](https://developers.google.com/resonance-audio/). If you are interested in
contributing to the project, please read the [Contributing to Resonance
Audio](#contributing-to-resonance-audio) section below.

## Build Instructions

Clone the repository:

    git clone https://github.com/resonance-audio/resonance-audio $YOUR_LOCAL_REPO

### Software Requirements

In addition to the system C++ software development platform tools / toolchains,
the following software is required to build and install the Resonance Audio
SDKs:

-   [CMake](https://cmake.org/download/)
-   [Git (with Git-Bash on Windows)](https://git-scm.com/downloads)

_Note: For Windows builds, [Visual Studio
2015](https://www.visualstudio.com/vs/older-downloads/) is recommended._

### Notes

Note that this fork is only for use with the Fresponze framework. For this reason, we do not recommend using these sources as the basis of your project. 

##### E.g.

To build and run the Resonance Audio unit tests:

    ./$YOUR_LOCAL_REPO/build.sh -t=RESONANCE_AUDIO_TESTS

## Citations

If you find Resonance Audio useful and would like to cite it in your publication, please use:

Gorzel, M., Allen, A., Kelly, I., Kammerl, J., Gungormusler, A., Yeh, H., and Boland, F., *"Efficient Encoding and Decoding of Binaural Sound with Resonance Audio"*, In proc. of the AES International Conference on Immersive and Interactive Audio, March 2019

The full paper is available (open access) at: http://www.aes.org/e-lib/browse.cfm?elib=20446 ([BibTeX](http://www.aes.org/e-lib/browse.cfm?elib=20446&fmt=bibtex))

## Contributing to Resonance Audio

If you would like to contribute changes to the Resonance Audio project, please
make a pull request for one of our project committers to review.

### Steering Committee

The Resonance Audio project is overseen by a steering committee established to
help guide the technical direction of the project in collaboration with the
entire developer community.

The intention of the steering committee is to cultivate collaboration across the
developer community for improving the project and ensuring Resonance Audio
continues to work well for everyone.

The committee will lead the Resonance Audio project in major decisions by
consensus and ensure that Resonance Audio can meet its goals as a truly open
source project.

The steering committee consists of the following members (company name ordered):

-   Martin Dufour, Audiokinetic
-   Aaron McLeran, Epic Games
-   Mathew Block, Firelight Technologies
-   Alper Gungormusler, Google
-   Eric Mauskopf, Google
-   Haroon Qureshi, Google
-   Ian Kelly, Google
-   Julius Kammerl, Google
-   Marcin Gorzel, Google
-   Damien Kelly, Google (YouTube)
-   Jean-Marc Jot, Magic Leap
-   Michael Berg, Unity Technologies

Affiliations are listed for identification purposes only; steering committee
members do not represent their employers or academic institutions.
