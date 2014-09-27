compress: jsrle4.min.js

jsrle4.min.js: jsrle4.js
	echo "/* from: https://github.com/michals/jsrle4/ */" > $@
	echo "/*jslint bitwise: true, plusplus: true, white: true*/" >> $@
	echo "/*global Uint8ClampedArray, ArrayBuffer, Uint8Array, Uint32Array*/" >> $@
	yui-compressor --preserve-semi $< >> $@
