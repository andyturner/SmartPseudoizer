SmartPseudoizer
===============

A Smarter version of the Pseudoizer tool by Scott Hanselman and John Robbin, which doesn't overwrite existing genuine translations.


A 'fork' of the Pseudoizer tool by Scott Hanselman and John Robbin at

	http://www.hanselman.com/blog/PsuedoInternationalizationAndYourASPNETApplication.aspx. 

This version is a little smarter in that it doesn't overwrite translations in the target
output file if they appear to have already been translated (ie, they don’t start with a
square bracket). This allows it to be used when you’re adding in new strings to a resx
that’s already been properly translated, so that it adds in new pseudoized entries without
overwriting the genuine ones.
