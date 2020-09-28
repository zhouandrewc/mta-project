# Metis Data Science Bootcamp Fall 2020 Project 1: MTA Ridership Analysis

This repository contains the code, data, images, and documentation for Metis Project 1 by Andrew Zhou, Srividya Sistla, and Albert Lee.

## Problem Statement


We're a data science analytics firm that has been approached by WTWY (Woman Tech Woman Yes) to give them recommendations for where to collect signatures and contact information from potential attendees of and donors to their annual gala. They plan to position teams at MTA subway stations to take advantage of commuter traffic, and those who sign up for their email list will receive tickets to the gala. WTWY would then like to solicit donations from these individuals. They would like recommendations to optimize the placement of their street teams.

See the [project specifications](project_01.md). 

## Contents

* [Data](data)

Three `.txt` files in CSV format, sourced from the [MTA's website](http://web.mta.info/developers/turnstile.html). A description of their [format](http://web.mta.info/developers/resources/nyct/turnstile/ts_Field_Description.txt) may be found here. Each file contains the data for one week, starting 8/27/16, 9/03/16, and 9/10/16 respectively.

* [Images](img)

A number of plots generated by our code. They may be dynamically generated within our iPython notebook, but are saved here for backup and easy reference. They comprise plots of [traffic by day of week](img/dow_traffic.png), [traffic by four-hour timeslot](img/timeslot_traffic.png), [traffic by day of week and timeslot for 4 selected high-traffic stations](img/selected_traffic.png), and [traffic encountered for specific numbers of teams](img/exposure_by_num_teams.png).

* [Code](project_1_mta.ipynb)

The code to read and clean our data, generate our plots, and make specific recommendations to WTWY. The recommendation algorithm is of particular interest and may be found as `assign_teams`.

## Acknowledgments

Thanks to the awesome staff and students at Metis who were of great help to us during this project.