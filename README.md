# gatto
Driver/s for the G{T,B}0{1,2} cat-shaped printer. _Il gatto con il dente blu_, or GATTo to their friends, is an adorable cat-shaped thermal printer that can be purchased from various sites on the so-called Internet.

This repo was mostly started so I could make bad cat jokes and translate Italian poorly with Google Translate.
You should be looking at https://github.com/JJJollyjim/catprinter and https://github.com/amber-sixel/gb01print

# Windows

Right now hitting ctrl-C makes the event loop go away, which means the tasks never get cancelled. You'll need to kill python.exe. Sorry. Pull requests welcome. I tried to read the asyncio documentation but my one remaining braincell is busy playing *Darude - Sandstorm*
