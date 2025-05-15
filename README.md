##    to install
`pip install totex --user`

## example
`python
datafr: pandas.DataFrame
totex.tabtex.convertFromData(
    "./path/to/save/", "table_id", "table caption",
    ["material", "$Z$", "$I$", "$I/I_{air}$", "$\\mu$", "$\\Delta\\mu$"], # latex headers set, if need latex-symbol mods
    datafr.to_records(index=False)
)
`
