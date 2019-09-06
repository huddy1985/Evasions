# Evasions

As malicious threats evolve, the necessity in automated solutions to analyze such threats emerges. It's a very common case when malware samples are executed in some kind of virtualized environment.

These environments differ from usual host systems by a huge amount of artifacts: non-common files, registry keys, system objects, etc. By examining such artifacts malware samples are able to say if they are run in a virtualized environment. Depending on the answer to this question, malware will continue its usual execution thus giving the researchers an opportunity to monitor its behavior - or will behave itself in an unexpected way and reveal nothing about its behavior. 

If the latter was the case, we say that malware has successfully applied evasion technique, or simply evasion.

In this encyclopedia we have attempted to gather all the known ways to detect virtualized environment grouping them into big categories. Some categories are inactive on main page: it means that content will be added later.

Within each category the reader will find the following information:
* description of the technique
* code sample showing its usage
* signature recommendations to track attempts to apply this technique
* table with breakdown of which particular environments are detected with the help of certain constants
* possible countermeasures

A lot of solutions with implemented techniques exist in open-source community. These solutions are used throughout the encyclopedia in the form of code excerpts from them. We are giving credits to open-source projects from where code sampes were taken: 
* al-khaser project on [github](al-khaser)
* pafish project on [github](pafish)

It's important to add that Check Point researchers have produced their own tool called [InviZzzible](invizzzible).

You're welcome to check out all the tools, browse through evasions encyclopedia and enjoy the journey!

Raman Ladutska


[al-khaser]: <https://github.com/LordNoteworthy/al-khaser>
[pafish]: <https://github.com/a0rtega/pafish>
[invizzzible]: <https://github.com/CheckPointSW/InviZzzible>