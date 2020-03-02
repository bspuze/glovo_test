# Definition
At employees.html the following client requirement has been implemented:
- The possibility to see the city of origin of the selected employees in a list.

# Task
Define and implement the tests you think are necessary for the technology you prefer.


# Solution

Test #1:
Scenario: this can be parametrized.
GIVEN the user is visiting the website "file:///media/bogdan/Data/glovo/ui-test-assessment/employees.html"
WHEN he tries to view the location for "Nancy"
THEN he will be able to see "Nancy is from Seattle"

GIVEN the user is visiting the website "file:///media/bogdan/Data/glovo/ui-test-assessment/employees.html"
WHEN he tries to view the location for ["Nancy", "Anne", "Janet"]
THEN he will be able to see that "Nancy is from Seattle"
AND he will be able to see that "Anne is from London"
AND he will be able to see that "Janet is from Kirkland"

GIVEN the user is visiting the website "file:///media/bogdan/Data/glovo/ui-test-assessment/employees.html"
WHEN he tries to view the location for []
THEN he will be able to see an empty result




