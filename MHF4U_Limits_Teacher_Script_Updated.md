# MHF4U: Limits — Comprehensive Teacher Script

**Course:** Grade 12 Advanced Functions (Ontario Curriculum MHF4U)  
**Topic:** Jensen Math Lesson 4 / Worksheet 4 — Limits (rates of change is optional extension material)  
**Materials Referenced:** `L4s++limits.pdf`, `L4t++limits.pdf`, `hw4s++limits.pdf`, `hw4t++limits.pdf`

> **Teaching plan for today:** The supplied Jensen PDFs focus on limits. Teach Slides 1–23 as the main lesson, then use Slides 34–35 to consolidate the limit decision process and finish with Slide 36. Slide 33 is an optional challenge. Slides 24–32 are an optional rates-of-change extension: the lesson PDF briefly connects limits to secant/tangent slopes, but the detailed difference-quotient, tangent-line, and velocity examples in those slides are extra material rather than worked examples from the four supplied PDFs. Skip that block if the priority is completing the limits lesson and Worksheet 4.

> **Source alignment:** Lesson 4 covers Archimedes’ method of exhaustion, numerical estimation, one-sided and two-sided limit existence, graph-based jump and infinite limits, horizontal asymptotes, the removable discontinuity example, and algebraic limits. Worksheet 4 covers direct substitution, factoring (including difference of squares, trinomials, cubes and GCF), a numerical table, and graph-reading questions. The interactive slide deck adds recap prompts but should not replace students’ written working.

---

## Slide 1: Title Slide
- **Slide Objective:** Set a focused, academic tone and orient the student to the bridge between Advanced Functions and Calculus.
- **Teacher Script:** "Welcome. Today our focus is limits in Grade 12 Advanced Functions, following Jensen Math Lesson 4 and Worksheet 4. We will interpret what a limit means, read limits from graphs, test one-sided behaviour, and evaluate algebraic limits. We will work carefully through the supplied examples and worksheet-style questions. If time remains, there is an optional connection to rates of change at the end."
- **Check-in Question:** "Have you seen the limit notation—the letters 'l-i-m'—in your class yet, or is this your first time seeing it formally written?"
- **Anticipated Response:** Student will indicate whether they have seen the notation or if it is entirely new.
- **Next Step:** "Either way, today you will master both the visual meaning and the exact algebra."

---

## Slide 2: Curriculum Learning Roadmap
- **Slide Objective:** Prioritize the three limit strands in the supplied Jensen lesson and worksheet, while clearly labelling rates of change as optional.
- **Teacher Script:** "Our main lesson has three parts. First, we will build the idea of a limit, including Archimedes’ method of exhaustion, one-sided notation, and the criteria for a two-sided limit to exist. Second, we will read limits from graphs, including jumps and asymptotes. Third, we will evaluate limits algebraically using direct substitution and factoring. If we finish the worksheet material and have time, we can preview rates of change as an optional extension."

---

## Slide 3: What is a Limit?
- **Slide Objective:** Define the intuitive concept and introduce formal limit notation.
- **Teacher Script:** "Let's begin with the formal definition. When you see $\lim_{x \to a} f(x) = L$, it reads: 'The limit of $f(x)$ as $x$ approaches $a$ equals $L$.' Notice the word *approaches*. A limit does not ask: 'What is the function equal to when you plug in $a$?' It asks: 'As $x$ gets closer and closer to $a$ from nearby numbers, what $y$-value does the function approach?'"
- **Question for Student:** "Why do you think it is so important that a limit only cares about what happens *near* $a$, rather than *at* $a$?"
- **Expected Student Response:** "Because the function might be undefined or have a hole at that exact point."
- **Affirmation:** "Exactly. A function can have a missing point or an asymptote at $x = a$, yet the limit can still exist as a clear, finite number."

---

## Slide 4: Archimedes' Method of Exhaustion
- **Slide Objective:** Connect the historical origin from Jensen Math Lesson 4 (Page 1) to limit theory.
- **Teacher Script:** "Look at the diagram on this slide. In ancient Greece, Archimedes wanted to prove the area of a circle. He didn't have calculus, so he used the 'method of exhaustion.' He drew a 4-sided square inside the circle. The area of the square was a rough estimate. Then he doubled the sides to an 8-sided octagon. It covered much more of the circle."
- **Question for Student:** "Imagine we keep doubling the number of sides: 16, 32, a thousand, or a 10,000-sided myriagon. Does the polygon ever literally become a circle?"
- **Expected Student Response:** "No, it's always made of straight lines, but it gets practically indistinguishable from a circle."
- **Follow-up:** "Precisely. The circle is the *limiting shape* of the polygon as the number of sides approaches infinity. That is the essence of a limit."

---

## Slide 5: One-Sided Limits
- **Slide Objective:** Introduce directional notation ($x \to a^-$ and $x \to a^+$).
- **Teacher Script:** "On a one-dimensional number line, you can approach any target number $a$ from two directions: from the left or from the right. We denote approaching from the left with a small minus sign in the exponent: $\lim_{x \to a^-} f(x)$. That means $x$ is strictly smaller than $a$. Approaching from the right uses a small plus sign: $\lim_{x \to a^+} f(x)$, meaning $x$ is strictly larger than $a$."
- **Question for Student:** "If $a = 3$, give me two numbers that represent approaching 3 from the left, and two numbers approaching 3 from the right."
- **Expected Student Response:** "From the left: 2.9 and 2.99. From the right: 3.1 and 3.01."

---

## Slide 6: Criteria for Limit Existence
- **Slide Objective:** Formalize the three mandatory conditions for a two-sided limit to exist.
- **Teacher Script:** "Here are the three criteria tested on every exam. For a regular two-sided limit $\lim_{x \to a} f(x)$ to exist, three conditions must be met:
  1. The left-hand limit must exist as a finite real number.
  2. The right-hand limit must exist as a finite real number.
  3. The left-hand limit must equal the right-hand limit."
- **Diagnostic Check:** "If the left-hand limit goes to 5, and the right-hand limit goes to 5, does the limit exist? What if the left goes to 5 and the right goes to -5?"
- **Expected Student Response:** "If both are 5, the limit is 5. If one is 5 and the other is -5, it does not exist (DNE)."

---

## Slide 7: Interactive Check — Numerical Estimation (L4s Example 1)
- **Slide Objective:** Guide the student through completing the table of values for $f(x) = x^2 - 2$ as $x \to 3$.
- **Teacher Script:** "Let's do our first interactive check. On Slide 7, we have the table from Jensen Math Lesson 4, Example 1. Look at the numbers as $x$ approaches 3 from the left: 6.41, 6.9401. As $x$ approaches from the right: 7.61, 7.0601."
- **Prompt:** "Type the limiting value into the input field and hit Verify."
- **When Student Enters 7:** "Correct! Both sides converge toward 7. Therefore, the two-sided limit is 7."

---

## Slide 8: Piecewise Graphs & Jump Discontinuity (L4s Example 2)
- **Slide Objective:** Analyze a graph with a jump discontinuity at $x = 1$.
- **Teacher Script:** "Look at the graph on Slide 8. This is Example 2 from Lesson 4. We have three pieces:
  - For $x < 1$, the function follows the line $y = x - 1$, landing at an open circle at $(1, 0)$.
  - Exactly at $x = 1$, there is an isolated solid dot at $(1, 1)$.
  - For $x > 1$, it follows the curve $y = 2 + \sqrt{x - 1}$, starting from an open circle at $(1, 2)$."
- **Question for Student:** "Trace the line from the left toward $x = 1$. What $y$-value does your finger approach? Now trace from the right. What $y$-value do you approach?"
- **Expected Student Response:** "From the left, it approaches 0. From the right, it approaches 2."

---

## Slide 9: Interactive Check — Jump Discontinuity Limit
- **Slide Objective:** Verify understanding that unequal one-sided limits mean the two-sided limit does not exist.
- **Teacher Script:** "Now, on Slide 9, apply Criterion 3. The left-hand limit is 0. The right-hand limit is 2. What is the two-sided limit as $x \to 1$?"
- **Prompt:** "Type your answer into the box and click Verify."
- **When Student Enters DNE:** "Spot on. Criterion 3 fails because $0 \neq 2$. Notice that the solid dot at $(1, 1)$ has no effect on whether the limit exists. The limit only cares about the path taken from the sides."

---

## Slide 10: Vertical Asymptotes as Infinite Limits (L4s Example 3)
- **Slide Objective:** Explain vertical asymptotes using one-sided limits approaching $\pm\infty$.
- **Teacher Script:** "Look at Slide 10, which graphs $f(x) = \frac{x + 1}{x - 4}$. The denominator is zero at $x = 4$, while the numerator is 5. When a non-zero number is divided by zero, we get a vertical asymptote."
- **Question for Student:** "If we pick $x = 3.999$, what is the sign of the numerator, and what is the sign of the denominator?"
- **Expected Student Response:** "Numerator is positive (around 5), denominator is negative (-0.001). So the quotient is a huge negative number: $-\infty$."
- **Follow-up:** "And at $4.001$, both are positive, giving $+\infty$. Because the two sides blow up to opposite infinities, the two-sided limit does not exist."

---

## Slide 11: Horizontal Asymptotes (Limits at Infinity)
- **Slide Objective:** Formalize horizontal asymptotes as $\lim_{x \to \pm\infty} f(x)$.
- **Teacher Script:** "Now look at the far ends of the graph on Slide 11. As $x$ grows to positive infinity or negative infinity, what does $f(x)$ flatten out toward? It flattens along the line $y = 1$."
- **Connection to Prior Units:** "Remember the leading coefficients rule from Unit 3? For equal degree rational functions, you divide the leading coefficients: $\frac{1x}{1x} = 1$. In limit notation, we write $\lim_{x \to \infty} \frac{x+1}{x-4} = 1$."

---

## Slide 12: Interactive Check — Worksheet 4 Question 4 Analysis
- **Slide Objective:** Solve Question 4 from `hw4s++limits.pdf` ($f(x) = \frac{x^2}{x + 1}$ at $x = -1$).
- **Teacher Script:** "Slide 12 features Question 4 from your homework sheet. The function is $f(x) = \frac{x^2}{x + 1}$. There is a dashed vertical asymptote at $x = -1$."
- **Prompt:** "Answer parts 4(a) and 4(b) in the interactive fields. What is the limit as $x \to -1^+$, and what is the limit as $x \to -1^-$?"
- **Expected Student Responses:** 4(a) is $+\infty$ (or infinity); 4(b) is $-\infty$.
- **Affirmation:** "Excellent. And for 4(c), since one goes up and one goes down, the two-sided limit does not exist."

---

## Slide 13: Interactive Check — Worksheet 4 Question 5 Piecewise Graph
- **Slide Objective:** Solve Question 5 from `hw4s++limits.pdf` ($y = h(x)$).
- **Teacher Script:** "Slide 13 directly matches Question 5 from Worksheet 4. Look at the two critical $x$-values: $-1$ and $3$."
- **Prompt:** "Look at $x = -1$. Follow the line approaching from the right side ($-1^+$). What $y$-value does that open circle sit at? Then look at $x = 3$ from the right ($3^+$). Enter both numbers in the fields."
- **Expected Student Responses:** For $-1^+$, the value is $-2$. For $3^+$, the value is $3$.
- **Discussion:** "Notice that for both $x = -1$ and $x = 3$, the two-sided limits do not exist because the left and right approaches do not meet."

---

## Slide 14: Algebraic Limits — Strategy 1: Direct Substitution
- **Slide Objective:** Teach the golden first rule of evaluating algebraic limits.
- **Teacher Script:** "Now we enter Topic 3: Algebraic Limits. Here is the golden rule: **Always try direct substitution first.** If you substitute $x = a$ and obtain a real, valid number with a non-zero denominator, you are immediately finished."
- **Example Walkthrough:** "Look at Worksheet 4, Question 1(a): $\lim_{x \to 2} \frac{3x}{x^2 + 2}$. Plug in 2: numerator is $3(2) = 6$, denominator is $2^2 + 2 = 6$. $6/6 = 1$. No factoring required."

---

## Slide 15: Interactive Check — Direct Substitution Practice
- **Slide Objective:** Solve Worksheet 4 Questions 1(b) and 1(c).
- **Teacher Script:** "Now practice this yourself on Slide 15.
  - In Check 1 (W4 Q1b): $\lim_{x \to -1} (x^4 + x^3 + x^2)$. Watch your negative signs carefully.
  - In Check 2 (W4 Q1c): $\lim_{x \to 9} (\sqrt{x} + \frac{1}{\sqrt{x}})^2$."
- **Guidance for Student:**
  - For 1(b): $(-1)^4 = 1$, $(-1)^3 = -1$, $(-1)^2 = 1$. $1 - 1 + 1 = 1$.
  - For 1(c): $\sqrt{9} = 3$, so inside the brackets is $3 + \frac{1}{3} = \frac{10}{3}$. Squaring gives $\frac{100}{9}$.
- **Affirmation:** "Both answers verified. Direct substitution is always your fastest tool."

---

## Slide 16: The Indeterminate Form 0 / 0
- **Slide Objective:** Demystify what $0/0$ means mathematically.
- **Teacher Script:** "Now, what happens when direct substitution gives zero in the numerator AND zero in the denominator? This is called the **indeterminate form: $0/0$**.
  It does not mean the limit does not exist, and it does not equal zero or one. It literally means: *'The expression is currently undetermined because there is a common factor of $(x - a)$ canceling itself out.'*"
- **Action Principle:** "Whenever you hit $0/0$, your immediate algebraic goal is: factor numerator, factor denominator, cancel the common bracket, and plug in the number again."

---

## Slide 17: Factoring — Difference of Squares
- **Slide Objective:** Demonstrate resolving $0/0$ with difference of squares (W4 Q2a).
- **Teacher Script:** "Look at Slide 17 for Question 2(a) from Worksheet 4: $\lim_{x \to 2} \frac{4 - x^2}{2 - x}$. Direct substitution gives $\frac{4 - 4}{2 - 2} = \frac{0}{0}$."
- **Step-by-Step Prompt:** "How does $4 - x^2$ factor?"
- **Expected Student Response:** "$(2 - x)(2 + x)$."
- **Follow-up:** "And because $(2 - x)$ cancels from the top and bottom, we are left with $\lim_{x \to 2} (2 + x)$. Substitute $x = 2$, and we get $2 + 2 = 4$. Notice: the graph has a hole at $(2, 4)$, but the limit is $4$."

---

## Slide 18: Interactive Check — Factoring Trinomials (W4 Q2b)
- **Slide Objective:** Solve Question 2(b) from Worksheet 4 using quadratic decomposition.
- **Teacher Script:** "On Slide 18, we have Question 2(b): $\lim_{x \to -1} \frac{2x^2 + 5x + 3}{x + 1}$. Substituting $-1$ yields $0/0$."
- **Prompt:** "Since $x + 1$ is in the denominator causing the zero, $(x + 1)$ must be a factor of the numerator. Factor $2x^2 + 5x + 3$, cancel the common factor, and enter the final limit value."
- **When Student Enters 1:** "Excellent! $(x + 1)(2x + 3)$ canceled with $(x + 1)$, leaving $2x + 3$. Plugging in $-1$ gives $2(-1) + 3 = 1$."

---

## Slide 19: Difference & Sum of Cubes Formulas
- **Slide Objective:** Review sum and difference of cubes formulas required for senior algebraic limits.
- **Teacher Script:** "Slide 19 introduces a classic algebraic tool tested in MHF4U: factoring cubes.
  - Difference of cubes: $a^3 - b^3 = (a - b)(a^2 + ab + b^2)$.
  - Sum of cubes: $a^3 + b^3 = (a + b)(a^2 - ab + b^2)$."
- **Mnemonic:** "Remember the acronym SOAP for the signs: **S**ame sign as the original, **O**pposite sign, and **A**lways **P**ositive at the end. Also notice: the middle term is just $ab$, NOT $2ab$."

---

## Slide 20: Interactive Check — Difference of Cubes (W4 Q2c)
- **Slide Objective:** Solve Question 2(c) from Worksheet 4: $\lim_{x \to 3} \frac{x^3 - 27}{x - 3}$.
- **Teacher Script:** "Slide 20 tests Question 2(c). Direct substitution of $x = 3$ gives $\frac{27 - 27}{3 - 3} = \frac{0}{0}$."
- **Prompt:** "Use the difference of cubes formula on $x^3 - 27$, cancel the $(x - 3)$, and evaluate the remaining quadratic. Type your result in the box."
- **When Student Enters 27:** "Outstanding! $(x - 3)(x^2 + 3x + 9)$ cancels to $x^2 + 3x + 9$. At $x = 3$, we have $3^2 + 3(3) + 9 = 9 + 9 + 9 = 27$."

---

## Slide 21: Trap Alert — 0 in Numerator Only
- **Slide Objective:** Highlight the crucial distinction between $0/0$ and $0/k$ using W4 Questions 2(d) and 2(e).
- **Teacher Script:** "Look closely at Slide 21. This is a common trap on Ontario exams.
  Look at Question 2(d): $\lim_{x \to 4} \frac{16 - x^2}{x^3 + 64}$.
  Students often see $16 - x^2$ and spend five minutes factoring. But what happens if you substitute $x = 4$ into the denominator?"
- **Expected Student Response:** "$4^3 + 64 = 64 + 64 = 128$."
- **Emphasis:** "The denominator is 128! The numerator is 0. Zero divided by 128 is simply **0**. There is no indeterminate form here, so no factoring is needed. The exact same thing happens in Question 2(e): $\frac{0}{2} = 0$."

---

## Slide 22: Interactive Check — GCF Factoring (W4 Q2f)
- **Slide Objective:** Solve Question 2(f) from Worksheet 4: $\lim_{x \to -1} \frac{x^2 + x}{x + 1}$.
- **Teacher Script:** "Slide 22 gives Question 2(f). Direct substitution gives $\frac{1 - 1}{-1 + 1} = \frac{0}{0}$."
- **Prompt:** "Take out the greatest common factor in the numerator, cancel, and evaluate."
- **When Student Enters -1:** "Correct. $x(x + 1)/(x + 1) = x$. As $x \to -1$, the limit is $-1$."

---

## Slide 23: Interactive Check — Numerical Table Estimation (W4 Q3)
- **Slide Objective:** Solve Question 3 from Worksheet 4: estimating $\lim_{x \to 2} \frac{x - 2}{x^2 - x - 2}$ numerically and algebraically.
- **Teacher Script:** "Slide 23 presents Question 3. Look at the quotient values in the bottom row: from the left, $0.3448, 0.3344, 0.3334$; from the right, $0.3226, 0.3322, 0.3332$."
- **Prompt:** "What exact common fraction does $0.3333...$ represent? Enter it as a fraction."
- **When Student Enters 1/3:** "Great job! And algebraically: $x^2 - x - 2 = (x - 2)(x + 1)$. Canceling $(x - 2)$ leaves $\frac{1}{x + 1}$, which at $x = 2$ gives $\frac{1}{2 + 1} = \frac{1}{3}$."

---

## Slide 24: Topic 4: Rates of Change — Secants vs Tangents *(Optional Extension)*
- **Teaching note:** This slide begins extra extension material, not a required worked example from the four supplied Jensen PDFs. Skip Slides 24–32 if today’s goal is to focus on limits and finish Worksheet 4.
- **Slide Objective:** Briefly connect the limit concept to average and instantaneous rates of change.
- **Teacher Script:** "Now we enter Topic 4: Rates of Change. This is your official step into Calculus.
  In earlier math, you learned the Average Rate of Change (AROC). AROC requires an interval between *two* points. On a graph, drawing a line between two points creates a **Secant Line** that cuts through the curve.
  In the real world, your car's speedometer doesn't show an average over the last hour; it shows your speed at that exact, frozen second. That is the **Instantaneous Rate of Change (IROC)**, represented by a **Tangent Line** that touches the curve at exactly one point."

---

## Slide 25: The Secant-to-Tangent Limit Process
- **Slide Objective:** Visualize how a secant line becomes a tangent line as $h \to 0$.
- **Teacher Script:** "Look at the diagram on Slide 25. Point $P$ sits at $(a, f(a))$. Point $Q$ sits a distance $h$ away, at $(a + h, f(a + h))$. The slope of the secant line is $\frac{f(a + h) - f(a)}{h}$."
- **Question for Student:** "What happens to point $Q$ as we make that step $h$ smaller and smaller, heading toward zero?"
- **Expected Student Response:** "Point $Q$ slides down the curve until it overlaps with point $P$."
- **Affirmation:** "Exactly! And as it overlaps, the secant line rotates until it becomes the tangent line. The slope of the tangent line is the limit of the secant slopes as $h \to 0$."

---

## Slide 26: The Newton Difference Quotient
- **Slide Objective:** Introduce the definition of the derivative formally.
- **Teacher Script:** "This brings us to the most famous formula in calculus: the Newton Difference Quotient:
  $$m_{\text{tan}} = \lim_{h \to 0} \frac{f(a + h) - f(a)}{h}$$
  Notice what happens if you substitute $h = 0$ directly: $\frac{f(a) - f(a)}{0} = \frac{0}{0}$. It is always an indeterminate form! That is why we studied algebraic limits first."

---

## Slide 27: Worked Example: Difference Quotient Execution
- **Slide Objective:** Walk through calculating the tangent slope of $f(x) = x^2$ at $x = 3$.
- **Teacher Script:** "Let's walk through the steps on Slide 27:
  1. We set up the quotient with $a = 3$: $\lim_{h \to 0} \frac{(3 + h)^2 - 3^2}{h}$.
  2. Expand $(3 + h)^2$: $9 + 6h + h^2$.
  3. Subtract 9: the constant terms cancel, leaving $6h + h^2$.
  4. Factor out $h$: $h(6 + h)/h = 6 + h$.
  5. Finally, evaluate the limit as $h \to 0$: $6 + 0 = 6$.
  The exact slope of the tangent line at $x = 3$ is 6."

---

## Slide 28: Interactive Check — Active Difference Quotient Solving
- **Slide Objective:** Student solves for the tangent slope of $g(x) = x^2 + 2x$ at $x = 1$.
- **Teacher Script:** "Now it's your turn on Slide 28. Find the instantaneous rate of change of $g(x) = x^2 + 2x$ at $x = 1$."
- **Guidance:** "Calculate $g(1) = 3$. Then expand $g(1 + h) = (1 + h)^2 + 2(1 + h)$. Subtract 3, divide by $h$, and take the limit as $h \to 0$."
- **When Student Enters 4:** "Brilliant work! The terms cancel down to $h + 4$, giving an exact slope of 4."

---

## Slide 29: Numerical Estimation of IROC ($h = 0.001$)
- **Slide Objective:** Explain how to approximate IROC when equations cannot easily be factored or when specified on a test.
- **Teacher Script:** "On Slide 29, we examine the following-interval approximation method: $[f(a + 0.001) - f(a)] / 0.001$. This is widely used across Ontario exams when working with rational or trigonometric functions."
- **Walkthrough:** "For $f(x) = 1/x$ at $x = 2$, we evaluate $f(2.001) \approx 0.49975$ and subtract $0.5$. Dividing by $0.001$ yields approximately $-0.25$, which is $-\frac{1}{4}$."

---

## Slide 30: Physical Application: Instantaneous Velocity
- **Slide Objective:** Connect rates of change to position, velocity, and gravity.
- **Teacher Script:** "Slide 30 connects this math directly to physics. If $s(t)$ represents the position of an object, then:
  - The average rate of change is average velocity.
  - The instantaneous rate of change is instantaneous velocity—the reading on a radar gun."
- **Sign Meaning:** "A positive velocity means the object is traveling upward or forward; negative means downward or backward; zero means it has reached its apex or turning point."

---

## Slide 31: Interactive Check — Instantaneous Velocity Problem
- **Slide Objective:** Solve an instantaneous velocity word problem: $s(t) = -4.9t^2 + 20t + 2$ at $t = 2$.
- **Teacher Script:** "On Slide 31, a projectile has height $s(t) = -4.9t^2 + 20t + 2$. Calculate its instantaneous velocity at $t = 2$ seconds."
- **Prompt:** "Use the limit or derivative rule to find the velocity in m/s."
- **When Student Enters 0.4:** "Spot on! $-9.8(2) + 20 = -19.6 + 20 = 0.4\text{ m/s}$. Since it is slightly positive, the projectile is just a fraction of a second away from reaching its maximum peak."

---

## Slide 32: Equation of the Tangent Line
- **Slide Objective:** Teach the complete three-step method for finding tangent line equations in $y = mx + b$ or point-slope form.
- **Teacher Script:** "Look at Slide 32. Tests often ask for the complete equation of the tangent line.
  Remember the three steps:
  1. Find the slope $m$ using the limit of the difference quotient.
  2. Find the point $(a, f(a))$ by plugging $a$ into the original function.
  3. Use $y - y_1 = m(x - x_1)$ to write the equation of the line."

---

## Slide 33: Interactive Synthesis — Challenge Limit *(Optional Challenge)*
- **Teaching note:** This synthesis problem is an extra challenge beyond the supplied Worksheet 4 questions. Use it only after the core worksheet questions are complete.
- **Slide Objective:** Synthesize difference of cubes and difference of squares in a single problem.
- **Teacher Script:** "Slide 33 contains a synthesis challenge:
  $$\lim_{x \to 2} \frac{x^3 - 8}{x^2 - 4}$$
  Direct substitution gives $0/0$."
- **Prompt:** "Factor the difference of cubes on top and the difference of squares on the bottom. Cancel the common $(x - 2)$ bracket and enter the final value."
- **When Student Enters 3:** "Superb algebra! $(x^2 + 2x + 4)/(x + 2)$ gives $12 / 4 = 3$."

---

## Slide 34: Ontario Exam Diagnostic Checklist
- **Slide Objective:** Review the four most common grading pitfalls on limits and rates of change exams.
- **Teacher Script:** "Before we conclude, look at the four red warning boxes on Slide 34:
  1. Never drop the $\lim_{x \to a}$ notation until you actually plug the number in. Teachers deduct communication marks for this on every test.
  2. Don't confuse $0/0$ with $0/k$. $0/k$ is done; $0/0$ needs factoring.
  3. Never average one-sided limits if they disagree—the answer is DNE.
  4. On difference of cubes, remember there is no '2' in the middle term: it is $ab$, not $2ab$."

---

## Slide 35: Comprehensive Limits Reference Map
- **Slide Objective:** Provide a unified decision algorithm for any limit problem.
- **Teacher Script:** "Slide 35 gives you a clean decision table. Whenever you are given any limit problem:
  - First, plug in the value.
  - If you get a real number, that is your answer.
  - If you get $0/\text{number}$, it is 0.
  - If you get $\text{number}/0$, investigate the vertical asymptote from the left and right.
  - If you get $0/0$, factor and cancel."

---

## Slide 36: Module Completion & Final Reflection
- **Slide Objective:** Conclude the session with confidence and review next steps.
- **Teacher Script:** "Good work today. You interpreted limits from tables and graphs, compared left- and right-hand behaviour, analysed asymptotes, and evaluated algebraic limits using substitution and factoring. Before we finish, explain which substitution result tells you to stop, which result requires one-sided analysis, and which result requires factoring. If we used the optional extension, we also previewed how limits connect to rates of change."
- **Closing Question:** "How do you feel about handling the $0/0$ indeterminate form versus an asymptote now?"
- **Expected Student Response:** Student reflects on the clarity between a hole (cancelable factor) and an asymptote (division by zero without common factor).