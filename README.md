# Convolution_Operation
Computer Architecture Assignment

## 1. Description:

This MIPS assembly program performs a convolution operation on an image matrix using a kernel filter. It reads parameters and matrix data from `input_matrix.txt`, performs the convolution, and writes the result to `output.txt`.

## 2. Key Features:

*   Implements the convolution algorithm with padding and stride.
*   Supports square image and kernel matrices with floating-point values.
*   Includes error handling for file I/O and invalid parameters.

## 3. Input:

`input_matrix.txt`: Specifies matrix dimensions (N, M), padding (p), stride (s), followed by image and kernel matrix data (space-separated floating-point numbers).

## 4. Output:

`output.txt`: Contains the resulting convolution matrix with formatted floating-point numbers.

## 5. Functions:

*   `main`: Program entry point.
*   `read_input`: Reads data from the input file.
*   `process_data`: Parses input and stores parameters.
* `validate_parameter`: Validates input parameters
*   `convolution`: Implements the convolution algorithm.
*   `write_output`: Writes the output matrix to the output file.
*`write_error_to_file`: Handle the printing error message.

## 6. Build and Execution:

1.  Assemble the MIPS code.
2.  Ensure `input_matrix.txt` is in the same directory or provide the full path.
3.  Run the assembled program.

