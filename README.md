contrib-snufflings
==================

This is a repository of user contributed snufflings. 

Snufflings are plugins for the
[Snuffler](http://emolch.github.io/pyrocko/v0.3/snuffler.html) application
which is part of [Pyrocko](http://emolch.github.io/pyrocko/). 

To use any of these snufflings, simply put the respective file or directory
into the `$HOME/.snufflings` directory. 

If you want to modify, develop, or keep up to date on any of these, it is
preferable to clone the whole repos somewhere in your filesystem and just make
symbolic links in `$HOME/.snufflings` for each snuffling to be used.

To add your own creation, simply clone this repos, add your stuff and a
screenshot and send a pull request. 


Create Map in OpenStreetMap or Google Maps
------------------------------------------

Plot station and event locations with OpenStreetMap or Google Maps

directory: [map](map)

![screenshot](screenshots/map.png)


Plot PSD
--------

Plot power spectral densities

file: [psd.py](psd.py)

![screenshot](screenshots/psd.png)

Cross correlation relocation
----------------------------

Relocate events by cross correlating waveforms

file: [cc\_relocation.py](cc_relocation.py)

![screenshot](screenshots/cc_relocation.png)

Cake Phase
----------

Add markers for synthetic arrivals

file: [cake\_phase.py](cake_phase.py)

![screenshot](screenshots/cake_phase.png)

Cross correlation search
------------------------

Find repeating events

file: [corrsearch.py](corrsearch.py)

![screenshot](screenshots/corrsearch.png)

Export wav Files 
----------------

file: [SeiSound.py](SeiSound.py)

![screenshot](screenshots/SeiSound.png)

Seismosizer
-----------

Calculate and show synthetic seismograms. The [Kiwi Tools](http://kinherd.org/kiwitools/) package must be installed for this to work.

file: [kiwi_seismosizer.py](kiwi_seismosizer.py)

![screenshot](screenshots/kiwi_seismosizer.png)

Time Line
---------

Plot time vs. magnitude

file: [time_line.py](time_line.py)

![screenshot](screenshots/timeline.png)

Extract Events
--------------

Save waveforms for time windows around selected events as MSEED. This is a
hybrid Snuffling which can be run from the command-line as well.

file: [extract_events.py](extract_events.py)

![screenshot](screenshots/extract_events.png)

