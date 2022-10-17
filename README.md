# IIIF Downloader

> A simple utility for downloading images from IIIF servers, adapted to work with Didomena's IIIF API.

NB Didomena is the research data repository of the EHESS (https://didomena.ehess.fr/).

## Installation

```bash
pip install iiif_downloader
```

## Usage

```bash
from iiif_downloader import Manifest

Manifest(url='https://didomena.ehess.fr/concern/data_sets/vx021f392/manifest.json').save_images()
```
