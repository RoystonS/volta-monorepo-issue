This repo demonstrates an issue with Volta 0.9.1 whereby it doesn't
walk up the directory hierarchy looking for package information: it appears
instead to stop at the first `package.json` it finds.

This is extremely problematic for monorepos.
