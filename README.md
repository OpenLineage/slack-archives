# OpenLineage Slack Archive

Browse the archive at https://openlineage.github.io/slack-archives/.

## Acknowledgements

HTML generated by [slack-export-viewer](https://github.com/hfaran/slack-export-viewer).

## Requirements

Requirements of slack-export-viewer and Python<=3.9.

## Instructions

Generate an export at [openlineage.slack.com/services/export](https://openlineage.slack.com/services/export).

Generate the HTML locally using this [fork](https://github.com/merobi-hub/slack-export-viewer/tree/html/add-output) of slack-export-viewer:

```sh
python3 app.py -z /Absolute/path/to/export.zip --html-only
```

Open a PR here to replace the existing HTML with the newly generated HTML.