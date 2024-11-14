java cMATH6005/6182 Assignment 1
MATH6005: Worth 20%
MATH6182: Worth 20%
Submission date: 18th November, 2024
Rules
• You must work on your own on this assignment with no help from others or GenAI.
• You must submit a single Jupyter notebook file as a submission.
• Clearly indicate your name and student number on the code. Save the file with your student
number, e.g student number.ipynb
• Ensure that your code is clean, well-structured, and free of errors. Non-functioning codes will be
penalized.
Problem 1 (40 marks)
The electricity consumption in a household is modeled as follows:
U(t) = (B + C(t) + f(A, t)) × F(t)
where B represents the minimum base usage independent of other factors, C(t) is the dynamic electricity
consumption based on the daily temperature, defined as C(t) = −κ · T[t], with κ with κ being a constant
and T[t] the temperature (◦C) on day t, f(A, t) models the electricity consumption based on the number of
occupants A, defined as f(A, t) = A · (uM + UE + Uof f ), where uM is the occupant usage during morning
peak hours (6am–9am), uE is the usage during evening peak hours (6pm - 10pm) and uof f is the usage at
off-peak hours and F(t) is the daily adjustment factor, set as 1.2 on weekdays and 0.8 on weekends. Given
the following parameters
B = 50kW h; k = 0.1, A = 5, uM = 1.5kW h, uE = 2.0kW h and uof f = 0.5kW h
1. Simulate a random dataset for daily temperature T[t] over 28 days, with a mean of 20◦C and a standard
deviation of 10◦C. Take the first day to be a Monday.
2. Calculate and print the daily electricity consumption for each of the 28 days.
3. Use matplotlib to plot a graph of electricity consumption over the 28-day period.
4. Analyze the average electricity usage by days of the week and produce a bar chart of the results.
5. Compare electricity consumption between weekdays and weekends, and discuss any noticeable differ ences.
Probl代 写MATH6005、Python
代做程序编程语言em 2 (20 marks)
The iterative formula for finding the roots of an equation is given by
xk+1 = xk −
f(xk)
10f
′(xk)
−
f
′
(xk)
600f
′′(xk)
,
where f
′
(x) is the first derivative of f(x) and f
′′(x) is the second derivative of f(x). The function to be
solved is:
f(x) = 2x
2 + 3 sin(x) − 4 exp(0.5x) + ln(x).
Starting with k = 1, the initial guess initial guess x1 = 2.0 and stopping criterion |xk+1 − xk| < 10−6
,
1. Find the roots of the equation f(x) = 0 using the formula provided.
2. Report the number of iterations required for the method to converge to a solution.
3. Plot the graph of |xk+1 − xk| against the number of iterations.
4. Using different starting points, analyze the performance of the method. Identify at least one starting
point where the method fails to converge and explain the behavior observed.
Problem 3 (40 marks)
The formula for calculating the probability of rainfall in a city is given by:
P(rain) = 1
1 + exp(−(a · tmax + b · tmin + c · af − d · sun)),
where tmax is the mean monthly maximum temperature, tmin is the mean monthly minimum temperature,
af is the number of air frost days recorded in the month, sun is the total sunshine duration (in hours), and
a,b,c,d are coefficients representing the impact of each variable on the probability of rainfall, with values
a = 0.05, b = 0.04, c = 0.03 and d = 0.02, respectively. Using the provided weather data.csv dataset,
perform the following tasks:
1. Calculate the average probability of rainfall in London, Manchester and Southampton for the year
2020.
2. Identify the city with the highest probability of rainfall in 2023.
3. Plot a bar chart showing the monthly rainfall probability trends in Southampton for the year 2022.
4. Plot the graph of Liverpool’s average annual rainfall probability between 2020 and 2023.

         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
