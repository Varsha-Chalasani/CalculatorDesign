# Division

Scenario: Division by '0' when operand '1' is any number

Given : Calculator charged and turned on

When : Put in first number, put in '/' sign, put in '0', press '='.

Then : Displayed undefined.

Scenario: Divide '0' by any number

Given : Calculator charged and turned on

When : Put in '0', put in '/' sign, put in second number, press '='.

Then : '0' resulted.

Scenario:Sign rules for operands

Given : Calculator charged and turned on

When : put in first number with sign, put in '/' sign, put in second number with sign, press '='.

Then : Normal division done, plus sign counter maintained. If even, positive number. 
If odd, negative number. Result displayed.

Scenario:

Given : Calculator charged and turned on

When : Put in first number, put in '/' sign, put in second number, press '='.

Then : Result displayed.

Scenario: Division when both operands are '0'

Given : Calculator charged and turned on

When : Put in '0', put in '/' sign, put in '0', press '='.

Then : displayed undefined.

Scenario: Recurring decimal case

Given : Calculator charged and turned on

When : Put in first number, put in '/' sign, put in second number, press '='.

Then : If recurring, cap down to two decimal places.

Scenario: Multiple times "/" is pressed

Given : Calculator charged and turned on

When : Put in first number, put in '/' sign multiple times, put in second number, press '='.

Then : '/' sign is overwritten by itself multiple times. Result displayed.

Scenario: Interleaving of multiple operators

Given : Calculator charged and turned on

When : Put in first number, put in '/' sign, put in other operators, put in second number, press '='.

Then : Operators are buffered, last one used. The result displayed.

Scenario: When operand 2 is not present

Given : Calculator charged and turned on

When : Put in first number, put in '/' sign, press '='.

Then : Error displayed.

Scenario:Division of multiple numbers 

Given : Calculator charged and turned on

When : Put in first number, put in '/' sign, put in second number, so on, press '='.

Then : Division done left to right, results buffered at each stage. Final result displayed.
