## Changelog

- **Replaced** deprecated `ThemeData.errorColor`  
  → Now uses `Theme.of(context).colorScheme.error`.

- **Updated** deprecated `TextTheme.bodyText1`  
  → Now uses `Theme.of(context).textTheme.bodyLarge`.

- **Published** as a new package: **`giphy_picker_plus`**  
  → Ensures compatibility with Flutter 3.x and above.  
  → Allows others to use without manual patching.

---

> ✅ **Recommendation:**  
> Switch to this package if you are using Flutter 3.x or later.

## 3.0.3
* Forked from giphy_picker version 3.0.1.
* Applied compatibility fixes for Flutter 3.7+:

Replaced deprecated ThemeData.errorColor with Theme.of(context).colorScheme.error.

Updated deprecated TextTheme.bodyText1 to Theme.of(context).textTheme.bodyLarge.

Published as a new package (giphy_picker_plus) on pub.dev to maintain compatibility and allow others to use without manual patching.

✅ Recommend switching to this package if using Flutter 3.x or later.

## 3.0.2
* Adds appBarBuilder for customizing AppBar in search and preview pages
* Fixes linter warnings
* Updates http dependency

## 3.0.1
* Improves documentation

## 3.0.0
* **Backwards incompatible rewrite**
* Performance improvements and bugfixes
* New customization builders

## 2.0.0
* Stable null safety

## 2.0.0-nullsafety.0
* Migrates to null safety

## 1.0.8
* Adds giphy preview type (by diegoveloper)
* Improved preview image fallback selection (by diegoveloper)

## 1.0.7
* Adds GiphyDecorator for improved picker customization (by diegoveloper)

## 1.0.6
* Removes obsolete giphy api key from documentation

## 1.0.5
* Adds Giphy sticker support
* Removes giphy_client dependency

## 1.0.4
* Default search text now GIPHY compliant
* Removes unneeded assets

## 1.0.3
* Adds optional showPreviewPage
* Adds searchtext localization

## 1.0.2
* Fixes fullscreen gif preview
* Improves error handling
* Fixes use of deprecated APIs

## 1.0.1
* Fixes popping too many pages on gif selection

## 1.0.0
* Minor notification bug fix
* Upgrades dependencies

## 0.0.2
* Fixes example reference

## 0.0.1
* Initial release

