# IDAGIO Pattern Library (2018)

## Index

### Perceptual Patterns
[Colour](perceptual/colour) | [Icons](perceptual/icons) | [Spacing](perceptual/spacing) | [Typography](perceptual/typography)

### Functional Patterns
#### Buttons
[Action Button](functional/buttons/action-button) | [Collection Button](functional/buttons/collection-button) |
[Play Button](functional/buttons/play-button) | [Utensil Button](functional/buttons/utensil-button)

#### Content Item Links
[Album](functional/content-item-links/album) | [Artist](functional/content-item-links/artist) | [Curator Card](functional/content-item-links/curator-card) | [Playlist](functional/content-item-links/playlist) | [Recording](functional/content-item-links/recording) | [Work](functional/content-item-links/work)

#### Content Labels
[Recording Info](functional/content-labels/recording-info) | [Work Authors](functional/content-labels/work-authors) | [Work Composers](functional/content-labels/work-composers)

#### Misc
[Flick Through](functional/misc/flick-through)

---

## Goals
- Identify and define existing patterns in our user interfaces.
- Establish a source of truth for those patterns.
- Enable discussion and contribution to this resource by designers, developers, and content specialists.

## Contribute
This is a shared resource and a collaborative effort. The interfaces of our apps should correspond exactly to the definitions in this library. If something is wrong or missing, [create an issue](https://github.com/IDAGIO/idagio-pattern-library/issues). If you have a question about anything, ask in the [Slack channel](https://idagio.slack.com/messages/C91FD96HE/).

## "Functional" vs "Perceptual" Patterns

*Functional* patterns are concrete modules of the interface, which can be described in terms of the function they serve, such as a button or a menu.
*Perceptual* patterns are styles which express the personality of the brand and product visually, such as colours and spacing units.

## Syntax and Naming Conventions
### Content Structure
[CSS value definition syntax](https://developer.mozilla.org/en-US/docs/Web/CSS/Value_definition_syntax) is used to to define the content structure of functional patterns.

### Text Style Definitions
Text style definitions are given in the following format:  
`<font-name> @ <font-size>/<line-height>[/<letter-spacing>]?, [<text-transform>,]? <colour>`  
eg. `GT Eesti Display Medium` @ `14px`/`20px`, `shark`

### Image Names
[BEM methodology](http://getbem.com/) is used for naming images in this documentation, where the section of the pattern definition is "block" level.  
eg. `visual__alignment.jpg`, `variation__context.jpg`
