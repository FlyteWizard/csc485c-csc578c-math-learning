---
tags: [remathex,text-to-speech]
---

## Reader and Editor of the Mathematical Expressions

"\[REMathEx\] uses the combination of the braille display and the speech synthesis outputs to provide the user with all the information concerning studied mathematical expressions" [^1]. The system uses the MathML format to store the mathematical expressions and is designed as an object oriented system. It uses the Audis hypertext system.

Figure 1 shows a simplified structure of the REMathEx system. It begins by reading tables, transforming them into a Dokument Structure with resulting math expressions. Finally it is transferred to an application that uses text-to-speech.

![[REMathEx System Diagram.png]]
Figure 1: The simplified structure of the REMathEx system. The arrows show the dataflow when the system generates the preview and the braille form of the mathematical expression [^1].

The system still needs better navigation and faster orientation inside the mathematical expression. And it still needs a system for modifying mathematical expressions.

[^1]: P. Gaura. (2002). REMathEx – Reader and Editor of the Mathematical Expressions for Blind Students. Available: https://link-springer-com.ezproxy.library.uvic.ca/content/pdf/10.1007/3-540-45491-8_92. \[Accessed: 30-Oct-2022\].