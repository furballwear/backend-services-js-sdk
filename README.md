## Everlive JavaScript SDK

### /min

Folder 'min' contains the minified versions of the scripts used by the SDK. Add this tag to your markup:

	<script src="path/to/everlive.all.min.js"></script>

to use the SDK as one file, or include each file separately:

	<script src="path/to/reqwest.min.js"></script>
	<script src="path/to/underscore.min.js"></script>
	<script src="path/to/rsvp.min.js"></script>
	<script src="path/to/jstz.min.js"></script>
	<script src="path/to/everlive.min.js"></script>
	<script src="path/to/kendo.data.everlive.min.js"></script>

The latter is for the case when some of the libraries are already included before.

### /src
Folder 'src' contains the source code of the libraries. The files may be used in development or for debugging purposes.