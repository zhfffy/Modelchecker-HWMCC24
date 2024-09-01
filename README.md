# Modelchecker-HWMCC24
Model Checker Submissions for Hardware Model Checking Competition 2024

This repository contains the Modelchecker tool, developed for the "Bit-level with mandatory safety certificates" track of the 2024 Hardware Model Checking Competition (HWMMC).

## Usage

To use Modelchecker, run the following command in the project directory:

```bash
./modelchecker <aiger_path>
```

For unsafe circuits, Modelchecker will output a a witness to the standard output and display the program's runtime. 
For safe circuits, Modelchecker will output "0" along with the runtime. Additionally, it will generate the circuit's certificate in both AIG and AAG formats in the current working directory, named `certificate.aig` and `certificate.aag` respectively.