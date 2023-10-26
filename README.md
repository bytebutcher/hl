# hl

Highlight specific words or terms in your text output with colors

## Description

The highlight tool takes in a stream of text and highlights specified words/terms in colors you choose. 
Whether you're analyzing logs, reading through lengthy outputs, or just want to make certain words stand out, highlight has you covered.

## Features

* Highlight multiple terms at once.
* Choose custom colors for each term.
* Pipe outputs from other commands directly.


## Usage

To use the highlight tool:

```
echo "Your text here" | hl --red term1 --blue term2 term3 --green term4
```

## Arguments

* ```--color term```: Color and term combination. Supported colors are red, blue, green, etc. Example: --red important

You can specify multiple terms for the same color, just space separate them:

```
--blue term1 term2
```

## Installation

```
git clone https://github.com/bytebutcher/hl
cd hl
chmod +x hl
cp hl /usr/bin/
```

## Contributing

If you'd like to contribute to the development of highlight, please fork the repo, make your changes, and submit a pull request.

## License

This project is licensed under the GPLv3 License.
