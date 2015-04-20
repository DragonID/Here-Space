# Here:Space
Conceptual Sonic Project for 2015 NASA Space Apps Challenge

Here:Space is a conceptual sonic project developed for the 2015 NASA Space Apps Challenge at the NASA Glenn Research Centre in Cleveland Ohio.

Inspired by open-source projects such as Listen to Bitcoin (http://www.bitlisten.com/) and Listen to Wikipedia (http://listen.hatnote.com/), Here:Space is a data pattern analysis tool and conceptual art project that uses real time/near real ISS Telemetry data to create unique, generative aural landscapes. Based on idea that pattern recognition is significantly different when data is interpreted aurally versus visually or textually, the translation of numerical data into sound opens up an exciting opportunity for novel engagement with a data set.

Here:Space is two part project featuring the Here:Space App and Here:Space installations.

The Here:Space App is a web based portal that allows the user to select different data sets from the ISS through a simple GUI and output their individual audio stream. This allows for portable access to the streams for personal/on-demand engagement with the Here:Space generative audio.

Here:Space installations are site-specific manifestations of the generative audio streams. These installations are set up as an immersive experience and allow the visitor to consider the generative audio in spatial context in addition to an aural one. 

Implementation
We are pulling real/near real time information from spacestationlve.jsc.nasa.gov and then using javascript libraries to generate an continuous audio stream from the information contained within the data streams.

The Here:Space App will allow the user to manually select which data source that they would like to listen from a range of telemetry data options. Each audio option will have its own unique sonic vocabulary giving a different “voice” to each data.

Here:Space installations will use MAX/MSP to create a realtime visualisation of the data and map the generated audio into a multi-point speaker system for audio/visual presentation.
