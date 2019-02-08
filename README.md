# KiCAD PickNPlace Assistant

This is actually a fork of Gist: pwuertz/kicad_picknplace_assistant.py. I am making this as Gist doesn't have pull request feature, so taking it to a Github repo makes it easier to maintain. 

AKA manual pick-and-place document generator for KiCAD PCB files.

A simple python script that generates pdf files that indicate the position of components on the PCB for every item on the BOM list.
Each BOM line generates one corresponding page.

## Getting Started and Usage

Simply call the script with Python 2.7, and provide the filename of your *.kicad_pcb file.
```
python kicad_picknplace_assistant.py your_file.kicad_pcb
```

### Prerequisites

This script runs on Python 2.7.

Requires matplotlib, numpy etc.

Requires the KiCAD's pcbnew to be installed (it comes with the required Python libraries).


## Authors

* **Peter Würtz** - *Initial work* - [kicad_picknplace_assistant.py](https://gist.github.com/pwuertz/152f15b2dadca9a74039aeab944714af)

## License

## Acknowledgments
Thanks to Peter who shared this awesome piece of code on Gist. My initial commit is simply a bug fix plus some improvements from Simon.

* Peter Würtz (https://gist.github.com/pwuertz/152f15b2dadca9a74039aeab944714af)
* Šimon Fojtů (https://gist.github.com/simonfojtu/6816bf400b2bd32871a23ec8b24ee19d)

