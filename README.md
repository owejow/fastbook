[English](./README.md) / [Spanish](./README_es.md) / [Korean](./README_ko.md) / [Chinese](./README_zh.md) / [Bengali](./README_bn.md) / [Indonesian](./README_id.md) / [Italian](./README_it.md) / [Portuguese](./README_pt.md) / [Vietnamese](./README_vn.md) / [Japanese](./README_ja.md)

# The fastai book

These notebooks cover an introduction to deep learning, [fastai](https://docs.fast.ai/), and [PyTorch](https://pytorch.org/). fastai is a layered API for deep learning; for more information, see [the fastai paper](https://www.mdpi.com/2078-2489/11/2/108). Everything in this repo is copyright Jeremy Howard and Sylvain Gugger, 2020 onwards. A selection of chapters is available to [read online here](https://fastai.github.io/fastbook2e/).

The notebooks in this repo are used for [a MOOC](https://course.fast.ai) and form the basis of [this book](https://www.amazon.com/Deep-Learning-Coders-fastai-PyTorch/dp/1492045527), which is currently available for purchase. It does not have the same GPL restrictions that are on this repository.

The code in the notebooks and python `.py` files is covered by the GPL v3 license; see the LICENSE file for details. The remainder (including all markdown cells in the notebooks and other prose) is not licensed for any redistribution or change of format or medium, other than making copies of the notebooks or forking this repo for your own private use. No commercial or broadcast use is allowed. We are making these materials freely available to help you learn deep learning, so please respect our copyright and these restrictions.

If you see someone hosting a copy of these materials somewhere else, please let them know that their actions are not allowed and may lead to legal action. Moreover, they would be hurting the community because we're not likely to release additional materials in this way if people ignore our copyright.

## Running Fastbook in Poetry Environment

0. ensure that [devenv](https://devenv.sh/getting-started/) is installed on your system.

1. clone the repository:

```bash

    # via https:
    git clone https://github.com/owejow/fastbook.git

    # or via ssh:
    #         git clone git@github.com:owejow/fastbook.git

```

2. enter into a shell that contains poetry and related dependencies:

```bash
    devenv shell
```

3. Start jupyter-lab and explore the notebooks

```bash
    poetry run jupyter-lab
```

NOTE: If you are running the notebooks locally please comment out the
"! [ -e /content ] && pip install -Uqq fastbook" at the top of the file.

## Contributions

If you make any pull requests to this repo, then you are assigning copyright of that work to Jeremy Howard and Sylvain Gugger. (Additionally, if you are making small edits to spelling or text, please specify the name of the file and a very brief description of what you're fixing. It's difficult for reviewers to know which corrections have already been made. Thank you.)

## Citations

If you wish to cite the book, you may use the following:

```
@book{howard2020deep,
title={Deep Learning for Coders with Fastai and Pytorch: AI Applications Without a PhD},
author={Howard, J. and Gugger, S.},
isbn={9781492045526},
url={https://books.google.no/books?id=xd6LxgEACAAJ},
year={2020},
publisher={O'Reilly Media, Incorporated}
}
```
