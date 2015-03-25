Google Nearby Connections C++ Samples
============================================================================
Copyright (C) 2015 Google Inc.

##Contents##

NearbyConnectionsNative: The sample demonstrates real time
multiplayer game on [C++ Nearby Connection interface SDK](https://developers.google.com/games/services/cpp/nearby).

##How to run a sample##

For generic play game related instruction, please follow steps described in [Getting Started for C++](https://developers.google.com/games/services/cpp/GettingStartedNativeClient)

For this specific demo, simple steps are:
  File: NearbyConnection.cpp
   Demonstrates features of Nearby Connections such as:
       1) Create nearby_connection interface gpg::NearbyConnections::Builder
       2) Connect to other peers via StartAdvertising(), StartDiscovery()
       3) Send messages with SendReliableMessage() and SendUnreliableMessage()
       4) Clean up Google Nearby Connection with Stop()
       5) Other in-game communication like relaying connections/messages
     Test Instructions:
       1) Build and install on phone
       2) Set ONE and ONLY ONE phone/device to be advertising first
       3) All other devices to be discovering after advertising is ready (indicator is "stop" button is enabled)
       4) Monitor bottom of the UI for connected Clients, once anyone connected, "start game" is enabled; play it at any time
       5) while playing, your own score and other player's score should be visible to you at the bottom of the screen
       note: play time is 30 second by default, set in GAME_DURATION in header file

##Support##

First of all, take a look at our [troubleshooting guide](https://developers.google.com/games/services/android/troubleshooting). Most setup issues can be solved by following this guide.

If your question is not answered by the troubleshooting guide, we encourage
you to post your question to [stackoverflow.com](stackoverflow.com). Our
team answers questions there reguarly.
