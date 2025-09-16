# Cossette Fonts

Cossette is a design agency with a team of individual talents that innovate day in and day out, across Canada and in Chicago.
Cosette has a global footprint, thanks to the reach of their parent agencies, Plus Company, and of course, their flagship clients.
Plus Company provides a full suite of integrated marketing communications services worldwide.

They developed these fonts internally and connected with the Google Fonts team to publish them under the [openfontlicense.org](https://openfontlicense.org)

## Building the fonts

Fonts are built using the gftools builder, which is a python based font builder.

To install the dependencies and build the fonts, do the following in this directory:

```
python3 -m venv venv
gftools builder sources/config-texte.yaml
gftools builder sources/config-titre.yaml
```

You should now have a `/fonts` directory containing different font binaries for both families.
