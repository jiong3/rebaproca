# Resistance Band Progression Calculator

Calculate possible combinations of resistance bands to achieve a range of target weights.



Created by OpenAI o3-mini using the following prompt:

>Create a website called "Resistance Band Progression Calculator". Everything should be contained in a single html file, including javascript and css.
>The user can provide the following inputs:
>"band weights" (default: "8,12,18,22,28,64"): a text input where the user can input a comma separated list of numbers (int or float)
>"two sets" (default: false): a checkbox which indicates that each provided band weight can be used twice if true, only once if false
>"doubled" (default: false): a check box which indicates that each band weight should be doubled to calculated the target weight
>"target range min" (default: 5) text input where the user can provide the minimum of the desired target weight range
>"target range max" (default: 100)  text input where the user can provide the minimum of the desired target weight range
>
>The algorithm should calculate for each integer in the target range a list of band weights, under the restrictions according to the options mentioned above. The sum of the band weights should be exactly the same or as close as possible to the target.
>Example: band weights [1, 2, 3,] target range: [5, 7] --> targets: [5, 6, 7] achievable sums: [5, 6, 6]
>
>The output should be:
>A diagram plotting the target range on the x-axis and the achievable sum of band weights on the y-axis.
>A table with three columns and one row for each integer in the target range:
>1. the values in the target range
>2. the achievable sum of band weights
>3. the list of band weights used to calculated the achievable sum
