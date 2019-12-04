# BIOF509 Applied Machine Learning Final Project

Braden Yang
Fall 2019

## Introduction and Problem Statement

Every week since 1958, *Billboard* magazine compiles their list of the top 100 songs currently trending in the United States. Some songs are instant number one hits, while other songs barely crack the bottom of the chart. Some songs only appear on the chart for as little as one week, while other songs remain near the top for multiple weeks. But is there a secret formula in how a song is written that leads to success in getting to the top of the charts, particularly in the chord structure of a song?

In this BIOF509 Applied Machine Learning project, we will attempt to predict a song's peak rank attained in the *Billboard* Hot 100 chart (the **hotness index**) using information about the chord progressions it uses. We will also attempt to predict how long a song stays on the charts (the **catchiness index**) using the same chord progression features.

## The Dataset

Data was obtained from *The McGill Billboard Project*, which has released annotated text files on 890 total songs . Each text file, which is named "salami_chords.txt", contains full information about the chord structure of a song, along with the key it is in, the time signature, and the verse structure. Link to the data download and citation are listed below:

https://ddmal.music.mcgill.ca/research/The_McGill_Billboard_Project_(Chord_Analysis_Dataset)/

    John Ashley Burgoyne, Jonathan Wild, and Ichiro Fujinaga, ‘An Expert Ground Truth Set for Audio Chord Recognition and Music Analysis’, in Proceedings of the 12th International Society for Music Information Retrieval Conference, ed. Anssi Klapuri and Colby Leider (Miami, FL, 2011), pp. 633–38, http://ismir2011.ismir.net/papers/OS8-1.pdf.

Data in this repository are located in the "data/McGill-Billboard" branch. Each "salami_chords.txt" file is stored in a song-specific directory that is named the integer index that it was assigned in the database.