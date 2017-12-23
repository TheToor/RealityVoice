# RealityVoice

RealityVoice is an open-source 3D voice chat for GTA 5 ([Grand Theft Multiplayer](https://gt-mp.net/)), based on OpenAL and Lidgren.

**Important:** This application is not for daily use, there are many bugs and it is quite network-heavy. The good thing is: It can be fixed. This application is for developers who want to integrate it in their own launcher - not for end-users.

Nevertheless, it would be nice if there will be an active contribution as it would greatly improve the stability.

# Serverside implementation
To use RealityVoice on the serverside, a reference to Lidgren is necessary. The compiled Dll can be found [here](https://github.com/Cryma/RealityVoice/tree/master/libs).

# TODO
  - [ ] Reduce network messages
  - [ ] Push-to-talk / Improved voice recognition
  - [ ] Volume-controls

# Used libraries
  * [OpenAL.NET](https://github.com/DevJohnC/OpenAL.NET/) ([MIT](https://github.com/DevJohnC/OpenAL.NET/blob/master/mit);[LGPLv2](https://github.com/DevJohnC/OpenAL.NET/blob/master/lgpl))
  * [Lidgren](https://github.com/lidgren/lidgren-network-gen3/) ([MIT](https://github.com/lidgren/lidgren-network-gen3/blob/master/LICENSE))