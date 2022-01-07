---
title: Taxonomic Stat
coverWidth: 1920
coverHeight: 1080
date: 2022-01-01
tags: [Code, Bioinformatics]
cover: https://benben-miao.gitee.io/image-cloud/GitHub/taxonomic-stat.png
---

<!-- <div style="background-color: #eeeeee; width: 120px; padding:5px 20px; border-radius: 3px;">Read More</div> -->
<!-- more -->

## 
### Source Code Repository
<div class="card">
  <a href="https://github.com/benben-miao/taxonomic-stat" style="text-shadow: 1px 1px 3px #888;">https://github.com/benben-miao/taxonomic-stat</a>
</div>

<img src="https://benben-miao.gitee.io/image-cloud/GitHub/taxonomic-stat.png"></img>

## 
### 1.Run with conda or python environment
#### 1.1 Create a conda environment
```bash
# Install python & pip for environment
conda create -n taxonomic-stat python=3.9
conda activate taxonomic-stat

# Install modules with pip for reducing execute file
pip install pandas
pip install numpy
pip install openpyxl
pip install xlrd
```
#### 1.2 Runing the taxonomic-stat.py python script
```bash
# The input file of `example.xlsx` is neccecary
python taxonomic-stat.py example.xlsx
```
## 
### 2. For users without conda or python environment
#### 2.1 Compile a execution program
```bash
# Don't forget to activate the environment
conda activate taxonomic-stat

# Install pyinstaller module
pip install pyinstaller

# Compile the python script
pyinstaller -F taxonomic-stat.py
```
#### 2.2 Run the executable file
```bash
# Execute the exe file after compiling by yourself or download from the release
./taxonomic-stat.exe example.xlsx

# The result file should be `example_result.xlsx` or `_result.xlsx`
```