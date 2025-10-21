# API

Define modules for uncertainty calculations.

### *class* unc.LabUnc(number: float, uncertainty: float = 0.0)

Bases: `object`

Representation of a floating point lab value with an uncertainty.

#### *static* combine(a: float, b: float) → float

Combine two uncertainties.

Args:
: a: float
  b: float

returns:
: float

#### *property* max *: float*

Return the maximum value given the uncertainty.

#### *property* min *: float*

Return the minimum value given the uncertainty.

#### *property* ndigits *: int*

Return the number of digits to round to.

#### rounding_rule *= 1.0*

This is the number to round at for display, lab rule is 1, particle physics uses
3.54

### *class* unc.StdUnc(number: float, uncertainty: float = 0.0)

Bases: [`LabUnc`](#unc.LabUnc)

Representation of a floating point standard value with an uncertainty.

#### *static* combine(a: float, b: float) → float

Combine two uncertainties.

Args:
: a: float
  b: float

returns:
: float
