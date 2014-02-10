This repository - https://github.com/greyscalepress/catalogue-lumiere - contains a list of the 1428 identified films produced by the Lumière company between 1895-1905.

The list comes as a simple CSV file, containing a set of metadata for each title. 

The data is also available through the website http://catalogue-lumiere.com/ which offers an interface for browsing / searching through specific parameters.

## Understanding the data

Here is the key to the table:

1. "Numero-original": the original catalog number of the film, as it appeared in the Lumiere catalog.
2. "Numero-livre": The item number that was used by the researchers (Michelle Aubert and Jean-Claude Seguin) in their book "La production cinématographique des Frères Lumière" in 1996.
3. "titre": The title of the film.
4. "id-operateur": numerical ID of the camera operator.
5. "operateur": name of the operator.
6. "remarque": comments and notes.
7. "description": the original item description, from the Lumière catalogue.
8. "projection": information about screenings (when, where...) 
9. "lieu": human-readable location names (where it was filmed).
10. "id-pays": country-ID.
11. "id-ville": city-ID.
12. "id-lieux": location-ID (mountain, seaside, train station, zoo...). 33 elements.
13. "date": human readable date of production.
14. "timestamp": machine-readable date stamp (approximate date of production).
15. "info-1": mysterious metadata.
16. "info-2": mysterious metadata.
17. "info-3": mysterious metadata.
18. "info-4": mysterious metadata.
19. "info-5": mysterious metadata.
20. "info-6": mysterious metadata.
21. "info-7": mysterious metadata.
22. "id-events": mysterious metadata.
23. "id-genres": mysterious metadata. 14 elements.
24. "id-sujet": types of people (acrobats, peasants, children...).
25. "id-identity": numerical ID of persons appearing in the film.
26. "sequence-1": mysterious metadata.
27. "sequence-2": mysterious metadata.
28. "personnes": notes about persons appearing in the film.
29. "technique": technical details about the filming process (camera motions, etc).
30. "id-objet": motives (train, boat, machines...). 19 elements.
31. "id-mouv": type of action (arrival, departure...). 9 elements.
32. "support": technical details about the film negative.

## Source of the data

The data has been extracted from the CD-Rom that accompanies the book "La production cinématographique des Frères Lumière", published 1996 by the Centre national de la Cinématographie and Université Lumière-Lyon 2.

This catalogue is out-of-print, and will be hard to get, unless you have access to a good academic libraray.

The CD-Rom contains a bibliographic application, made in Macromedia Director. It was targetted for MacOS System 7 and Windows 95, and is unreadable on current operating systems.

However, the raw binary files of the CD-Rom contain some readable text data, which I was able to retrieve.

With some GREP magic, I produced this CSV table, that holds the essential metadata for the 1428 identified movies from the Lumiere catalogue.

## What's the copyright of that data? Is it public domain?

The research team that produced this list gathered all the information from the original trade catalogues of the Lumière company (published 1897-1907), from newspapers published in that time period, and from an inventory established by the Cinémathèque française in 1948.

It's pretty much impossible to establish a clear copyright situation for this type of metadata. 

Personally, I place all my contributions to this set of metadata under the Creative Commons Zero Public Domain Dedication (CC0), in order to facilitate research.

Manuel Schmalstieg<br/>
Ditigal archivist<br/>
December 2013

