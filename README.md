# GetLicense

<p align="center">📖 Easily choose and get a license for your software</p>

```
usage: getlicense [-h] [-L] [-l] [-n] [-c]
                  [--organization ORGANIZATION] [-o OUTPUT]
                  [--project PROJECT] [--year YEAR]
                  [license_name]

Easily choose and get a license for your software

positional arguments:
  license_name          Name of license template to fetch (e.g.,
                        mit, gpl3 and etc.)

options:
  -h, --help            show this help message and exit
  -L, --list-cached-templates
                        List cached license templates
  -l, --list-templates  List available license templates
  -n, --no-cache        Don't cache the license template file when
                        downloaded
  -c, --offline         Get the cached license template instead of
                        downloading
  --organization ORGANIZATION
                        The name of the organization or individual
                        who holds the copyright to the software
  -o, --output OUTPUT   Where to write the license template content
                        to
  --project PROJECT     The name of the software project
  --year YEAR           The year of the software's copyright
```

## Features

1. **License Retrieval:**

   * Retrieves license templates by name (e.g., mit, gpl3).
   * Lists available license templates from an online repository.

2. **Customization:**

   * Automatically fills in organization, project, and year fields in the license.
   * Prompts for missing details interactively if not provided through command-line arguments.
   * Allows setting a custom output file name with the --output option.

3. **Caching:**

   * Stores downloaded license templates locally for faster reuse.
   * Can retrieve license templates in offline mode using cached versions.
   * Supports skipping caching entirely with a command-line flag.
   * Lists all locally cached license templates.

## Installation

- You either install it from `pypi` using `pip`:

```bash
pip install getlicense
```

- Or directly install it from `github` using `pip`:

```bash
pip install git+https://github.com/ashkanfeyzollahi/getlicense.git
```

- Or even build it from source!
