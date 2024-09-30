# riscv-assembler

[![kcelebi](https://circleci.com/gh/kcelebi/riscv-assembler.svg?style=svg)](https://circleci.com/gh/kcelebi/riscv-assembler)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

![example](references/mdimg.png)
# documentation
This package contains tools and functions that can convert **RISC-V Assembly code to machine code**. The whole process is implemented using Python purely for understandability, less so for efficiency in computation. These tools can be used to **convert given lines of code or [whole files](#convert) to machine code**. For conversion, output file types are binary, text files, and printing to console. The supported instruction types are **R, I, S, SB, U, and UJ**. Almost all standard instructions are supported, most pseudo instructions are also supported.

Risc-V Instruction Set Specifications: [RISC-V Instruction Set Specifications — riscv-isa-pages documentation (msyksphinz-self.github.io)](https://msyksphinz-self.github.io/riscv-isadoc/html/index.html)

# installation

## **build**

```bash
python setup.py bdist_wheel
```

## **install**

```python
pip install dist/<package_name_xxx>.whl
```

