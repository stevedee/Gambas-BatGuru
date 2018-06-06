# Gambas-BatGuru
A bat echolocation call identifier written in Gambas

This program uses bat echolocation call data by Chris Russ as described in his excellent book: British Bat Calls. This book is an essential reference book for anyone interested in bat call analysis.

BatGuru only attempts to identify a bat after you have manually entered the 6 key parameters taken from a full-spectrum bat call recording.

Open your recordings in Audacity, then use the Spectrogram & Frequency Analysis displays to determine the key parameters, which are:-
   - call type (e.g. FM, qCF & so on)
   - FmaxE (the dominant frequency)
   - Fstart (frequency at start of call)
   - Fend (frequency at end of call)
   - duration (the length of the individual call)
   - interval (the typical time between the end of a call and the start of the next call)
