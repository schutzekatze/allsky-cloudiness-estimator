# Allsky Cloud Detector
This project is a work in progress, but the following is planned:

A cloudiness estimator for allsky camera images. The project was originally started for Petnica Meteor Group that sought to automate the manual process of estimating
cloudiness in night allsky camera images for the purposes of calculating Zenithal Hourly Rate.

Given a timeframe, field of view of the sky, and allsky camera images, the program will print a table with cloudiness percentages as it changes over the time.

Detection uses a neural network trained to recognize clouds, including non-obvious ones in the night sky, which are detected by the lack of stars where the clouds are.

Credits:<br/>
Project - Vladimir Nikolić (https://github.com/schutzekatze)<br/>
Neural network design - Leander Schröder (https://github.com/robinleander)<br/>
UI - Aleksa Tešić (https://github.com/Imafikus)