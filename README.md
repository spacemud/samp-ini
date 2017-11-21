# kvfile

Key-Value File Reader/Writer

---

## Installation

Add to your `pawn.json`:

```json
{
    "dependencies": [
        "Southclaws/samp-kvfile"
    ]
}
```

Include in source:

```pawn
#include <kvfile>
```

## Tests

You can run tests with `sampctl`:

```pawn
sampctl project run
```

If you're on OSX, you can use a container runtime:

```pawn
sampctl project run --container
```