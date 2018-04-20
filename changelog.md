# 1.0.1

-   Fix issue with `init` command missing after installation.
-   Fix issue with missing templates after installation.


# 1.0.2

-   Add `slug` placeholder.
-   Process placeholders in `.yml`, `.txt`, and `.md` files, not just `foliant.yml`.
-   Templates: basic: Add `Dockerfile`, `docker-compose.yml`, `requirements.txt`, and `README.md`.


# 1.0.3

-   Upon creation, relative path to the created project directory is returned instead of an absolute one.
-   Templates: basic: Foliant docs related content removed from README.md.
-   Templates: basic: `foliantcontrib.mkdocs` added to requirements.txt.


# 1.0.4

-   Replace placeholders in file and directory names.
-   Process *.py files.
-   User Template strings instead of format strings for safer substitutions.
-   Update for Foliant 1.0.4: Pass logger to spinner.
-   Require Foliant 1.0.4.
