---
title: Fish Ratio
coverWidth: 1920
coverHeight: 1080
date: 2022-04-16
tags: Code
cover: https://benben-miao.gitee.io/image-cloud/GitHub/fishratio-terminal.png
---

<!-- <div style="background-color: #eeeeee; width: 120px; padding:5px 20px; border-radius: 3px;">Read More</div> -->
<!-- more -->

<div class="card">
  <a href="https://benben-miao.github.io" style="text-shadow: 1px 1px 3px #888;">https://benben-miao.github.io</a>
</div>

## 
### 1. FishRatio innformation
> **FishRatio:** 本程序基于Python开发属于终端程序，方便科研者统计复杂的物种分类地位数据，超千行的数据及复杂的Excel结构使用Python循环与判断逻辑解决问题更高效和准确。本文详细介绍我开发的FishRatio程序的使用及开发。
\
**FishRatio PYPI:** Calculate the ratio and logarithmic value of species contained in several genus of a family to all species in this family.
\
[**Developer:** benben-miao](https://github.com/benben-miao)
\
[**Github:** https://github.com/benben-miao](https://github.com/benben-miao)
\
[**Source Code:** https://github.com/benben-miao/FishRatio](https://github.com/benben-miao/FishRatio)
\
[**PyPI:** https://pypi.org/project/fishratio/](https://pypi.org/project/fishratio/)

## 
### 2. Install from PyPI using pip
[https://pypi.org/project/fishratio](https://pypi.org/project/fishratio)

```shell
pip install fishratio
```

## 
### 3. fishratio Usage
```bash
fishratio --help
Usage: fishratio [OPTIONS]

     Description:

     Calculate the ratio and logarithmic value of species contained in
     several genus of a family to all species in this family.

     Examples:

     1. Get options and parameters help:

     FishRatio --help

     2. Sample command with all default parameters:

     FishRatio --input input.xlsx     or

     FishRatio --input input.xlsx --ratio true --ln_ratio true --neg_ratio
     true --output output.xlsx

     3. Only calculate (species number of genus) / (species number of
     family):

     FishRatio --input input.xlsx --ratio true --ln_ratio false --neg_ratio
     false --output output.xlsx

Options:
  --input TEXT        Full name (path + name + extension) of input file.
                      default="input.xlsx"

  --ratio BOOLEAN     Formula: (species number of genus) / (species number of
                      family) ratio value. default=True

  --ln_ratio BOOLEAN  Formula: Log(e)(ratio value). default=True
  --neg_mul BOOLEAN   Formula: -(ratio x Log(e)(ratio value)). default=True
  --output TEXT       Full name (path + name + extension) of output file.
                      default="output.xlsx"

  --help              Show this message and exit.
```

## 
### 4. Examples
#### 4.1 Examples folder
`path-to-miniconda: ./miniconda3/lib/site-packages/fishratio/examples/`

```shell
# Sample command with all default parameters:

FishRatio --input input.xlsx
# or
FishRatio --input input.xlsx --ratio true --ln_ratio true --neg_ratio
true --output output.xlsx
```

#### 4.2 input.xlsx

| Family         | Genus           | Species |
|----------------|-----------------|---------|
| Myxinidae      | Eptatretus      | 3       |
| Chimaeridae    | Chimaera        | 1       |
| Chimaeridae    | Hydrolagus      | 1       |
| Scyliorhinidae | Apristurus      | 2       |
| Scyliorhinidae | Atelomycterus   | 1       |
| Scyliorhinidae | Cephaloscyllium | 3       |
| Scyliorhinidae | Galeus          | 1       |
| Scyliorhinidae | Halaelurus      | 1       |
| Scyliorhinidae | Parmaturus      | 1       |

#### 4.3 output.xlsx

| Family         | Genus           | Species | Ratios      | LnRatio      | NegMul      |
|----------------|-----------------|---------|-------------|--------------|-------------|
| Chimaeridae    | Chimaera        | 1       | 0.5         | -0.693147181 | 0.34657359  |
| Chimaeridae    | Hydrolagus      | 1       | 0.5         | -0.693147181 | 0.34657359  |
| Myxinidae      | Eptatretus      | 3       | 1           | 0            | 0           |
| Scyliorhinidae | Apristurus      | 2       | 0.222222222 | -1.504077397 | 0.334239422 |
| Scyliorhinidae | Atelomycterus   | 1       | 0.111111111 | -2.197224577 | 0.244136064 |
| Scyliorhinidae | Cephaloscyllium | 3       | 0.333333333 | -1.098612289 | 0.366204096 |
| Scyliorhinidae | Galeus          | 1       | 0.111111111 | -2.197224577 | 0.244136064 |
| Scyliorhinidae | Halaelurus      | 1       | 0.111111111 | -2.197224577 | 0.244136064 |
| Scyliorhinidae | Parmaturus      | 1       | 0.111111111 | -2.197224577 | 0.244136064 |

## 
### 5. Developement
#### 5.1 Click package
>**Click**: Used for building terminal command interaction.
\
[Click website: https://github.com/pallets/click](https://github.com/pallets/click)

#### 5.2 Setuptools
>**Setuptools**: Used for building Python module.
\
[Setuptools website: https://github.com/pypa/setuptools](https://github.com/pypa/setuptools)
