+++
order = 4
subject = "law"
tags = ["law", "lsat", "logic", "quantifiers"]
+++

# LSAT — Quantifiers and Formal Logic

## 4.1 Why Quantifiers Matter

Q: Why does mastering "some", "most", and "all" separate good LR scores from great ones?
A: A large fraction of harder LR questions hinge on the difference between "all", "most", and "some". Mistaking "most students pass" for "all students pass" produces predictable wrong answers that the LSAT explicitly tests. Top scorers diagram these explicitly.

## 4.2 "All" / "Every"

C: "All As are Bs" translates to the conditional [A → B].

Q: What does "all" tell you and what does it not tell you?
A: "All As are Bs" tells you every A is also a B. It does not tell you that all Bs are As, nor that there even exist any As. The category may be empty and the statement still vacuously true.

## 4.3 "Some"

Q: What does "some" mean on the LSAT?
A: "Some" means "at least one" — anywhere from one to all. It does not mean "some but not all". This wider meaning lets the test set traps where "some" is true even when "all" is also true.

C: On the LSAT, "some" means [at least one], including possibly all.

## 4.4 "Most"

C: On the LSAT, "most" means [more than half] — not merely "many" or "a majority of those discussed".

Q: Why does "most students pass" fail if exactly 50% of students pass?
A: "Most" requires strictly more than half. Exactly 50% is not more than half, so the claim is false.

## 4.5 The "Some" Inference Rule

Q: What can you validly infer when "all As are Bs" and "all As are Cs"?
A: You can infer "some Bs are Cs". Because every A is both a B and a C, the As themselves are members of both categories — provided at least one A exists. On the LSAT, "all" statements usually presuppose existence.

C: From "All As are Bs" and "All As are Cs", you can infer [some Bs are Cs].

## 4.6 The "Most" Inference Rule

Q: What can you validly infer when "most As are Bs" and "most As are Cs"?
A: You can infer "some Bs are Cs". Since more than half of As are Bs and more than half are Cs, the two majorities must overlap by basic counting — at least one A is both B and C.

C: From "Most As are Bs" and "Most As are Cs", you can infer [some Bs are Cs].

## 4.7 Chaining "All" with "Most"

Q: From "All As are Bs" and "Most Bs are Cs", what follows?
A: Nothing follows about As and Cs. The "most Bs that are Cs" might exclude all the As. Mistakenly chaining all → most → some is a classic LSAT trap.

C: From "All As are Bs" and "Most Bs are Cs", you can validly conclude [nothing] about A and C.

## 4.8 Chaining "Most" with "All"

Q: From "Most As are Bs" and "All Bs are Cs", what follows?
A: You can infer "Most As are Cs". The all-statement applies to every B, and most As are Bs, so most As must inherit C-ness.

C: From "Most As are Bs" and "All Bs are Cs", you can infer [most As are Cs].

## 4.9 Negating Quantifiers

Q: What is the negation of "All As are Bs"?
A: The negation is "Some A is not a B" — a single counterexample suffices. To deny a universal you only need one exception.

C: The negation of "All As are Bs" is [some A is not a B].

Q: What is the negation of "Some As are Bs"?
A: The negation is "No As are Bs" — equivalently, "all As are not-Bs". To deny existence, you must rule out the entire category.

C: The negation of "Some As are Bs" is [no As are Bs].

Q: What is the negation of "Most As are Bs"?
A: The negation is "At most half of As are Bs" — equivalently, "Most As are not Bs" or exactly 50%. Many test-takers wrongly negate "most" as "no", losing easy points.

## 4.10 "Some Are Not"

Q: What is the relationship between "Some As are Bs" and "Some As are not Bs"?
A: They are compatible — both can be true at once if the As split between B and not-B. Neither implies the other. Recognizing this prevents a common false-inference trap.

## 4.11 Combining Quantified and Conditional Statements

P: How do you handle a stimulus mixing conditionals with "most" and "some"?
S: Apply IPEE.

**IDENTIFY** — A passage with one or more "all/most/some" statements alongside if-then claims.

**PLAN** — Diagram each statement separately. Use → for "all", ←m→ for "most" (with the m showing direction), and ←s→ for "some".

**EXECUTE** — Look for shared terms. Apply the chaining rules: all + all = some; most + most (same source) = some; most + all (downstream) = most. Anything else is invalid.

**EVALUATE** — Check the answer choices against your inferred relationships. Eliminate any choice that requires a chain not on your list.

## 4.12 Existence Assumptions

Q: When does a universal statement on the LSAT presuppose existence?
A: In ordinary LSAT usage, "all As are Bs" usually presupposes that at least one A exists, which is what makes the all-all-some inference valid. In strict formal logic this assumption is dropped, but the LSAT follows the colloquial reading.
