# Generate-exOrgnr

`Generate-exOrgnr` is a PowerShell function that generates Norwegian organization numbers (orgnr) by creating random 8-digit numbers and appending a valid check digit. It also verifies the generated numbers against the Norwegian Business Register API.

## Features

- Generates a specified number of valid Norwegian organization numbers.
- Validates the generated numbers using a check digit algorithm.
- Handles API responses gracefully, providing informative messages for different status codes.

## Installation

To use the `Generate-exOrgnr` function, simply copy the code into your PowerShell environment or save it in a `.ps1` file.

## Usage

You can call the function with the desired number of organization numbers to generate. The default is set to 1.

```powershell
# Generate 3 organization numbers
$results = Generate-exOrgnr -count 3
Write-Output $results
