# Multiplication

Scenario: Result overflow

Given : Calculator charged and turned on

When : Put in first number, put in star sign, put in second number, press '='.

Then : Result displayed. The overflow digits are identified, represented to
the power 10.

Scenario: Signs of the numbers.

Given : Calculator charged and turned on

When : put in first number with sign, put in star sign, put in second number
with sign, press '='.

Then : Normal multiplication is done, plus sign counter maintained. If even,
positive number. If odd, negative number. Result displayed.

Scenario:Zero value multiplication

Given : Calculator charged and turned on

When : Put in first number, put in star sign, put in '0', press '='.

Then : The result displayed as 0

Scenario: Multiplication by 1

Given : Calculator charged and turned on

When : Put in first number, put in star sign, put in '1', press '='.

Then : The result displayed as first number.

Scenario:Decimal value multiplication

Given : Calculator charged and turned on

When : Put in first decimal, put in star sign, put in second decimal, press '='.

Then : Multipled as two integers, decimal count maintained, value is corrected.

Scenario: Irrational value multiplication

Given : Calculator charged and turned on

When : Put in first number, put in star sign, put in second number, press '='.

Then : Irration number capped to 2 decimal places. Multiplied as decimals.
Result displayed.

Scenario: Decimal & integer multiplication

Given : Calculator charged and turned on

When :Put in first number, put in star sign, put in second number, press '='.

Then : Decimal counter mainted, multiplied as integers, decimal point updated.
Result displayed.

Scenario: More than two numbers multiplication

Given : Calculator charged and turned on

When : type in first number, type in star, type in second number, type in star sign,
type in third number and so on.

Then : The result displayed.

Scenario: Range of operand exceeds allowed limit

Given : Calculator charged and turned on

When :Put in first number, put in star sign, put in second number, press '='.

Then : Error displayed.

Scenario: Pressing "multiply button" multiple times.

Given : Calculator charged and turned on

When : Put in first number, put in star sign multiple times, put in
second number, press '='.

Then : Star sign is overwritten by itself multiple times. Result displayed.

Scenario:Interleaving operators

Given : Calculator charged and turned on

When :Put in first number, put in star sign, put in other operators,
put in second number, press '='.

Then : Operators are buffered, last one used. The result displayed.
