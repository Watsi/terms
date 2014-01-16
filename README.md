# Terms

The canonical source for Watsi's legal documents for the platform.

## Changes

All changes should be made in this repository.
There are notes in the corresponding files on what to pay attention to,
but workflow will be explained here.

1.  Local changes: Make any changes here.
1.  Copy whole blocks from the corresponding files in this repo to the corresponding block
    sections in the platform. You may have to use `h4` tags in the markdown for the revision
    links.

    You can match sections by looking at the comments in corresponding files.
    In `foo.md` in this repo the `[//]: HEADER` block.
    will get copied to the platform's `foo.html.slim` in the `// HEADER` block
1.  Update the `WATSI_PRIVACY_COMMIT_SHA` and `WATSI_TERMS_COMMIT_SHA` `ENV` variables
    to the latest SHA (7 characters is fine).
1.  Update the `WATSI_PRIVACY_COMMIT_ANCHOR` and `WATSI_TERMS_COMMIT_ANCHOR` `ENV` variables
    to the latest, which you can get from inspecting the commit details page.
