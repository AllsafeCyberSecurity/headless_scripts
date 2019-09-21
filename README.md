# Headless Scripts

Headless Scripts for Ghidra's Headless Analyzer written in Python.


## disassembler

`disassembler.py` disassembles all the functions recognized by Ghidra, and writes them into file.

### Usage

```shell
$ analyzeHeadless <PROJECT_PATH> <PROJECT_NAME> -process <TARGET_FILENAME> -scriptPath <PATH_TO_YOUR_SCRIPT> -postScript disassembler.py <OUTPUT_FILEPATH>

```

## decompiler

`decompiler.py` decompiles all the functions recognized by Ghidra, and writes them into file.

### Usage

```shell
$ analyzeHeadless <PROJECT_PATH> <PROJECT_NAME> -process <TARGET_FILENAME> -scriptPath <PATH_TO_YOUR_SCRIPT> -postScript decompiler.py <OUTPUT_FILEPATH>
```