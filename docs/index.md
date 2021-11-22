# Welcome to MkDocs

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

Test 5

## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.

!!! note
    On a few known hosts (specifically GitHub, Bitbucket and GitLab), the
    `edit_uri` is derived from the 'repo_url' and does not need to be set
    manually. Simply defining a `repo_url` will automatically populate the
    `edit_uri` configs setting.

    For example, for a GitHub- or GitLab-hosted repository, the `edit_uri`
    would be automatically set as `edit/master/docs/` (Note the `edit` path
    and `master` branch).

    For a Bitbucket-hosted repository, the equivalent `edit_uri` would be
    automatically set as `src/default/docs/` (note the `src` path and `default`
    branch).

    To use a different URI than the default (for example a different branch),
    simply set the `edit_uri` to your desired string. If you do not want any
    "edit URL link" displayed on your pages, then set `edit_uri` to an empty
    string to disable the automatic setting.

!!! warning
    On GitHub and GitLab, the default "edit" path (`edit/master/docs/`) opens
    the page in the online editor. This functionality requires that the user
    have and be logged in to a GitHub/GitLab account. Otherwise, the user will
    be redirected to a login/signup page. Alternatively, use the "blob" path
    (`blob/master/docs/`) to open a read-only view, which supports anonymous
    access.