# CSS-only Emoji Animation #

[Demo](https://merncraft.github.io/mood)

This animation uses an `@counter-style` at-rule to create a custom counter style from Unicode emoji symbols.

The @keyframe animation changes the value of a `counter` property at each step, to iterate throught the set of emojis.

The smiley emojis are shown as `content` for an `::after` pseudo-element.