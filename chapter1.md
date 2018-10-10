---
title: 'Template Chapter 1'
description: 'This is a template chapter.'
---

## An exercise title written in sentence case

```yaml
type: NormalExercise
key: 6d010cc9af
lang: r
xp: 100
skills: 1
```

This is the Context. It should help provide students with the background information needed.
The Instructions that follow should be in bullet point form with clear guidance for what is expected.

`@instructions`
- Complete the code such that boolean_vector contains the three elements: TRUE, FALSE and TRUE (in that order).3

`@hint`
- Here is the hint for this setup problem. 
- It should get students 50% of the way to the correct answer.
- So don't provide the answer, but don't just reiterate the instructions.
- Typically one hint per instruction is a sensible amount.

`@pre_exercise_code`
```{r}
# Load datasets and packages here.
```

`@sample_code`
```{r}
numeric_vector <- c(, , )
character_vector <- c(" ", " ", " ")

# Complete the code for boolean_vector
boolean_vector <- c(TRUE, FALSE, TRUE)
```

`@solution`
```{r}
numeric_vector <- c(1, 10, 49)
character_vector <- c("a", "b", "c")

# Complete the code for boolean_vector
boolean_vector <- c(TRUE, FALSE, TRUE)
```

`@sct`
```{r}
# Update this to something more informative.
success_msg("Some praise! Then reinforce a learning objective from the exercise.")
```
