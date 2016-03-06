# interactive-textbook-specification
Description of an ideal interactive textbook for mathematics courses

## Core objectives

* Interactive text
  * user responses can be integrated into the exposition, not just in isolated exercises
  * text can change dynamically based on user responses
  * facility for rich feedback

* Technology-independence
  * Independent of any specific mathematics engine, technology, or programming language
  * Authors isoloated from changes in the software system
  * Text portable to different systems
  * Mathematical specifications divorced from implementation details.  Implementation details explicitly removed from the markup author create.

* Simplicity
  * Authoring of basic documents simple for non-technical authors to pick up
  * Complexity introduced only as necessary for more complicated features or configurations

* Stability
  * addition of new features will not break documents based on previous version
  * if backwards incompatible changes are necessary, automatic conversion tools provided if possible

* Well-defined and well-documented


## Key benefits
* Educators could share problems and text even if use different systems.
* The mutual language would encourage collaboration and teamwork.
* Divorcing specification of the mathematics and text from implementation details could lead to a cleaner formulation of the content.
* The time-intensive investment of authoring text and problems could be preserved even when switching to different technology.
* Content could be readily adapted to new technologies and new possibilities for content delivery.


## Desired features

* Dynamic text
  * text can change based on user response

* Ability to specify answer checking mode
  * control over the range of mathematically equivalent answers deemed correct
  * specify globally, per section, or per individual answer

* Ability to specify weight/points of particular answers

* Ability to specify multiple (partially) correct answers
  (Specifying a single should be extremely simple)

* Integrated interactive media 
  * bidirectional communication api?
  * media can change dynamically based on user repsonses
  * text can change dynamically based on media


## Challenges

* Mathematical syntax
  * presumably use (a variant of) an existing mathematics language
  * must distinguish amount distinct expressions that have identical notation

* Converting from other formats
  * will work on only a fraction of problems because of the complex syntax of current languages such as PG/PGML.


## Complementary, but separate, features

* widgets, e.g., palettes, for user entry of mathematics

* recording and storage of user responses/scores

* links or integration with an LMS
