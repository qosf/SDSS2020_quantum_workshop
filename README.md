# Introduction to programming quantum computers

This repo contains all the resources for the [Symposium on Data Science and Statistics (SDSS) 2020](https://ww2.amstat.org/meetings/sdss/2020/) workshop on "Introduction to programming quantum computers". The workshop was organized by the [Quantum Open Source Foundation](https://qosf.org) and took place on June 3rd 2020 in a virtual Webex meeting. It was conducted by [Mark Fingerhuth](https://github.com/markf94). We would like to thank the [Rigetti Computing](https://rigetti.com) team and give credit to some of their (previous) employees ([Nikolas Tezak](https://github.com/ntezak) and [Will Zeng](https://github.com/willzeng) specifically) since some of our slides used some of their resources and slides.

## Getting started

For the two Jupyter notebooks to work you need to run your on simulator and compiler instance on your local machine. To do so, please follow the instructions in the Rigetti documentation and install the Forest SDK such that you can run your own `qvm` and `quilc` instances.

Upon successful installation, you should be able to open a new terminal window and run the following two commands:

```
$ qvm --version
$ quilc --version
```

If these commands are successful you need to open two separate (!) terminals. In one of them you run `quilc -S` and in the other one you run `qvm -S`. It's important that you let these two services run whilst you're working on the exercises. These services provide you with a quantum simulator and a quantum compiler.

In order to open the Jupyter notebooks you simply run:

```
$ jupyter notebook
```

in this directory. 

## WARNING

We discourage you from opening the notebooks with Google Collaboratory since you won't be able to run the code. This has to do with the fact that you can NOT run a `quilc` and `qvm` instance on the Google Collaboratory server.
