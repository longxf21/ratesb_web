# ratesb_web: Rate Law Analysis for SBML and Antimony Models

`ratesb_web` is the python backend support for ratesb. To use ratesb in python, please install [ratesb_python](https://github.com/sys-bio/ratesb_python).

## Installation

To install `ratesb_web`, execute the following command in your terminal:

```bash
pip install ratesb_web
```

## Versions

0.1.0: initial release, prepared for integration with RateSB

## Development

Once a new version of `ratesb_python` is released, copy and paste all codes, then delete the get parameter methods for analyzer, instead read from the input json string that represents all reactions of the model. The custom classifier path is replaced by a json string of the custom classifier.

## License

`ratesb_web` is licensed under the MIT license. Please see the LICENSE file for more information.

## Contact

For additional queries, please contact Longxuan Fan at longxuan@usc.edu.

We hope ratesb_python assists you effectively in your model rate law analysis!
