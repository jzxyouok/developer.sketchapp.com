---
title: MSRulerData
summary: Stores the guides used on its ruler. MSPage and MSArtboardGroup both return their ruler data using <code>horizontalRulerData</code> and <code>verticalRulerData</code>.
rels:
  - MSPage
  - MSArtboardGroup
---

Stores the guides used on its ruler. [MSPage](/reference/class/MSPage/) and [MSArtboardGroup](/reference/class/MSArtboardGroup/) both return their ruler data using `horizontalRulerData` and `verticalRulerData`.

## Methods & Attributes

### addGuideWithValue:(CGFloat)value

Supply an integer value (measured from the origin of the ruler). Adds a new guide at the given value.

### numberOfGuides:

Returns the number of guides on this ruler.

### guideAtIndex:(NSUInteger)index

Returns the integer value of the given guide. The argument is a zero-based index value.

### removeGuideAtIndex:(NSUInteger)index

Remove the guide at the given index.
