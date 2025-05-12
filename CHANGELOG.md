## 2.0.1

* Added direct tag deletion when cursor is positioned within tag boundaries
* Fixed out-of-range errors when deleting text near adjacent tags
* Improved overlay behavior to automatically hide when cursor enters a tag
* Enhanced cursor position handling for better backspace behavior
* Fixed edge cases with tag boundary detection (added +2 offset for more accurate detection)
* Prevented search activation when cursor is inside existing tags
* Refined search regex pattern to exclude spaces for more precise matching
* Added print debugging for better tag parsing visibility (development feature)
* Improved overall stability when manipulating text around tag boundaries

## 2.0.0

* Improved tag formatting with better nested tag handling
* Added direct tag deletion when cursor is within a tag
* Enhanced default pattern handling with sensible defaults
* Optimized formatted text generation for better performance
* Fixed tag selection and cursor positioning issues
* Improved tag retrieval with optimized implementation

## 0.0.1

* Initial release of input_tagger
* Support for tags with spaces
* Multiple trigger characters (@, #, etc.)
* Customizable tag styles
* Dynamic overlay for tag suggestions
* Easy integration with existing text fields