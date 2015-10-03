BBEdit Codeless Language Module for Xcode .pbxproj files
==============================

This is a [BBEdit](http://www.barebones.com/products/bbedit/index.html) and
[TextWrangler](http://www.barebones.com/products/textwrangler/) Codeless
Language Module for [Swift](https://developer.apple.com/swift/). It currently supports
Swift 2.0.

* keywords definitions include unicode character support, although some unicode ranges in the language reference are not supported by BBEdit. This includes the higher unicode planes encoding emoji, etc.
* All elements of the standard library are encoded as predefined names.
* Functions are matched and appear in the function popup, but other declarations such as class, protocol, enum, etc are not supported. Nested functions are also not supported.

For more information see the documentation for [Codeless Language Modules](http://www.barebones.com/support/develop/clm.html).

Installation
=============================

  * For BBEdit, copy the swift.plist file to:

		~/Library/Application Support/BBEdit/Language Modules/

	For TextWrangler, copy the swift.plist file to:

		~/Library/Application Support/TextWrangler/Language Modules/

  * Restart BBEdit or TextWrangler.

