# 1.0.10

- Add Makefile to the base template

# 1.0.9

- Add template download from got repository

# 1.0.8

-   Add comment to Dockerfile with option to use Foliant full image.
-   Remove slugs from docker-compose. Now the service is always named `foliant`.

# 1.0.7

-   Provide compatibility with Foliant 1.0.8.

# 1.0.6

-   Provide compatibility with Foliant 1.0.7.

# 1.0.5

-   Require Foliant 1.0.5 with prompt_toolkit^2.0.0.

# 1.0.4

-   Replace placeholders in file and directory names.
-   Process *.py files.
-   User Template strings instead of format strings for safer substitutions.
-   Update for Foliant 1.0.4: Pass logger to spinner.
-   Require Foliant 1.0.4.

# 1.0.3

-   Upon creation, relative path to the created project directory is returned instead of an absolute one.
-   Templates: basic: Foliant docs related content removed from README.md.
-   Templates: basic: `foliantcontrib.mkdocs` added to requirements.txt.

# 1.0.2

-   Add `slug` placeholder.
-   Process placeholders in `.yml`, `.txt`, and `.md` files, not just `foliant.yml`.
-   Templates: basic: Add `Dockerfile`, `docker-compose.yml`, `requirements.txt`, and `README.md`.

# 1.0.1

-   Fix issue with `init` command missing after installation.
-   Fix issue with missing templates after installation.
