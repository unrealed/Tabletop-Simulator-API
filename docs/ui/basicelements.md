These are display-type elements for the UI. They cannot send information to any Lua scripts.

Each element has its own attributes specific to its type that work in addition to the [common attributes](attributes#common-attributes).

##Element Summary

Element Name | Description | &nbsp;
-- | -- | --
`#!xml <Text></Text>` | Adds basic text. | [<span class="i"></span>](#text)
`#!xml <ProgressBar></ProgressBar>` | Displays a progress bar which can be updated dynamically via script. | [<span class="i"></span>](#progressbar)

---

##Element Details

###Text

Adds basic text.

Attribute Name&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Description&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Type / Options&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Default Value&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
-- | -- | -- | --
alignment | | <ul><li>UpperLeft</li><li>UpperCenter</li><li>UpperRight</li><li>MiddleLeft</li><li>MiddleCenter</li><li>MiddleRight</li><li>LowerLeft</li><li>LowerCenter</li><li>LowerRight</li></ul> | MiddleCenter
color | | [<span class="tag xmlco"></span>](attributes#attribute-types) | `#323232`
fontStyle | | <ul><li>Normal</li><li>Bold</li><li>Italic</li><li>BoldItalic</li></ul> | `Normal`
fontSize | | float | `14`
resizeTextForBestFit | Resize text to fit? | [<span class="tag boo"></span>](attributes#attribute-types) | `false`
resizeTextMinSize | Minimum font size | float | `10`
resizeTextMaxSize | Maximum font size | float | `40`
horizontalOverflow | | <ul><li>Wrap</li><li>Overflow</li></ul> | `Overflow`
verticalOverflow | | <ul><li>Truncate</li><li>Overflow</li></ul> | `Truncate`

---


###ProgressBar

Displays a progress bar which can be updated dynamically via script.

Attribute Name&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Description&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Type / Options&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Default Value&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
-- | -- | -- | --
image | Background Image | (path to image) | *(none)*
color | Background Color | [<span class="tag xmlco"></span>](attributes#attribute-types) | `#FFFFFF`
fillImageColor | Fill Color | [<span class="tag xmlco"></span>](attributes#attribute-types) | `#FFFFFF`
percentage | Percentage to Display | float | `0`
showPercentageText | Is the percentage text displayed? | [<span class="tag boo"></span>](attributes#attribute-types) | `true`
percentageTextFormat | Format to use for the percentage text | string | `0.00`
textColor | Percentage Text Color | [<span class="tag xmlco"></span>](attributes#attribute-types) | `#000000`
textShadow | Percentage Text Shadow Color | [<span class="tag xmlco"></span>](attributes#attribute-types) | *(none)*
textOutline | Percentage Text Outline Color  | [<span class="tag xmlco"></span>](attributes#attribute-types) | *(none)*
textAlignment | Percentage Text Alignment | <ul><li>UpperLeft</li><li>UpperCenter</li><li>UpperRight</li><li>MiddleLeft</li><li>MiddleCenter</li><li>MiddleRight</li><li>LowerLeft</li><li>LowerCenter</li><li>LowerRight</li></ul> | `MiddleCenter`

---
