# NOrMAL 

> NOrMAL: Accurate Nucleosome Positioning using a Modified Gaussian Mixture Model

## Installation

Clone the repo and then compile the binary
```sh
git clone https://github.com/antonpolishko/NOrMAL.git
cd NOrMAL
make
```

## Usage

To check whether everything is properly working

```sh
make test 
```

Provide configuration file. The exapmle "config.txt" is self explanatory

The sample of input data is provided in "DATA/" folder.

To run 

```sh
./NOrMAL <config.txt> <forward reads> <reverse reads> <results>
```

## License

MIT © [Anton Polishko](http://cs.ucr.edu/~polishka/)
