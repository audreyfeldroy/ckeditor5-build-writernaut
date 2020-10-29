ckeditor5-build-writernaut
========================================

Writernaut.com uses this custom CKEditor 5 build.

## Local Development

Fork this, then:

```
git clone git@github.com:yourusername/ckeditor5-build-writernaut.git
cd ckeditor5-build-writernaut
npm link
```

From your project:

```
npm link ckeditor5-build-writernaut
```

Then come back to this package directory and build it:

```
npm run build
```

To import it:

```
import WriternautEditor from "ckeditor5-build-writernaut";
```

To release a new package version:

```
np
```