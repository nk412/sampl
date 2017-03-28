# sampl

Generate a random sample of piped input data.

## Requirements
- Python 2.6 onwards, including Python 3
- No external packages required, pure Python

## Quickstart

    $ cat dataset.txt | sampl -v > sample.txt

    Sample ratio : 0.1
    Input lines  : 1000
    Output lines : 94

### Options

##### `--size`, `-s`
lets you define the sample size. Defaults to 0.1

##### `--verbose`, `-v`
shows you stats on lines processed and output on STDERR

##### `--random-seed`, `-r`
allows you to specify a seed for the RNG for reproducible results
