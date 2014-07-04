# SCXcodeMiniMap

ORIGIN: https://github.com/stefanceriu/SCXcodeMiniMap

## Notes

 For my needs...
  * Increased DefaultZoomLevel and DefaultShadowLevel to 0.2f
  * Changed width calculation "editorTextView.bounds.size.width * kDefaultZoomLevel" to (editorContainerView.bounds.size.width < 900?0:280) 
    This way - if the code frame.width is smaller than 900, this minimap will not show up. Otherwise - 280 pixels wide.