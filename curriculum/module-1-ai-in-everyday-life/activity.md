# Activity: Train the Robot

**Time:** 15 minutes · **Groups of 4** · **No devices needed**

Students play the role of a machine learning model. They learn a hidden pattern from labeled examples, then get tested on new ones, including cases their "training data" never covered.

## Setup

Print and cut these cards. Each group gets the **Training set** first, then the **Test set**.

The hidden rule (don't tell students): **"A fruit is APPROVED if it's red or yellow."**

### Training set (label shown on card)

| Card | Label |
|---|---|
| Red apple | ✅ APPROVED |
| Banana (yellow) | ✅ APPROVED |
| Strawberry (red) | ✅ APPROVED |
| Lemon (yellow) | ✅ APPROVED |
| Lime (green) | ❌ REJECTED |
| Blueberries (blue) | ❌ REJECTED |
| Green grapes | ❌ REJECTED |
| Cherry (red) | ✅ APPROVED |

### Test set (no labels; students predict)

| Card | Correct answer | Why it's interesting |
|---|---|---|
| Red bell pepper | ✅ | Not a "fruit" students expect, but it follows the pattern |
| Green apple | ❌ | Same fruit as a training example, different color. Trips up groups who learned "apples = yes" |
| Pineapple (yellow inside, brown/green outside) | ? | Ambiguous! The model was never shown this case |
| Purple grapes | ❌ | Never saw purple |
| Golden kiwi (brown outside, yellow inside) | ? | Ambiguous |
| Watermelon (green outside, red inside) | ? | Ambiguous |

## Steps

1. **Train (4 min):** Groups study the Training set and write down the rule they think the "robot" learned.
2. **Test (4 min):** Groups label each Test card ✅ or ❌ and record confidence (sure / unsure).
3. **Reveal (2 min):** Share the hidden rule. Score each group.
4. **Debrief (5 min):** Ask:
   - Which groups learned a *wrong* rule that still matched the training data? (e.g., "round = yes") This is how real AI picks up the wrong pattern.
   - What happened with pineapple and watermelon? **The training data never showed the robot what to do with mixed colors.** Real AI faces this constantly.
   - If this were a face-recognition AI and the training photos only included some kinds of faces, who would it get wrong?
   - How could we make the robot better? (More and more varied examples; human checks; let it say "I'm not sure.")

## Key takeaways to say out loud

- AI learns patterns from examples, not understanding.
- It can learn the wrong pattern and still look right on the examples it saw.
- Missing examples = mistakes for the people or cases left out.
- That's why humans need to check AI, and why diverse people need to help build it. **That could be you.**

## Extension (older students)
Give one group a training set with no yellow fruit at all, and compare results. Discuss: whose job is it to make sure the training data is fair?
