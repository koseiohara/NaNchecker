# NaNchecker

Developer : Kosei Ohara  
Environment : ifort 19.1.3.304 20200925

This module just checks wether the input scalar or array has NaN.  
IEEE_IS_NAN from IEEE_ARITHMETIC is wrapped  

## Argument
The argument is a scalar or an array.  
If it is an array, its dimension must be between 1 and 3.  
This is available for single and double precision real.  
If scalar, output is .TRUE. when the value is NaN.  
If array, output is .TRUE. when one of the element is NaN.

