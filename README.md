# KiCAD PickNPlace Assistant

Manual pick-and-place document generator for KiCAD PCB files.

A simple python script that generates PDF files that indicate the position of components on the PCB for every item on the BOM list.
Each BOM line generates one corresponding page.

For a more advanced, interactive solution see: [InteractiveHtmlBom](https://github.com/openscopeproject/InteractiveHtmlBom)

## Getting Started and Usage

Simply call the script with Python 2.7, and provide the filename of your *.kicad_pcb file.
```
python kicad_picknplace_assistant.py your_file.kicad_pcb
```

### Prerequisites

This script runs on Python 2.7.

Requires matplotlib, numpy etc.

Requires the KiCAD's pcbnew to be installed (it comes with the required Python libraries).

## Acknowledgments

Included modifications from [@simonfojtu](https://github.com/simonfojtu) and [@tohyf](https://github.com/tohyf).
