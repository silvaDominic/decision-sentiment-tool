# Decision Sentiment Tool
An NLP tool that can be used to interpret voice input and distill its meaning into a singular action.

## Concept

Using the power of NLP and LLMs, a range of vocal inputs can be interpreted and distilled into a singular 'sentiment' which can represent some action.

### Examples:

*Given a choice to choose a direction*...

- "I think we should go left."
- "Let's go left."
- "Left."
- "We should go where the noise came from." (Interpreting context -- Advanced)
- "The noise came from there so we should go left."
- "I think the right decision would be to go left." (Deriving sentiment amongst contradictory words) -- Advanced)

...would all be reduced into a singular decision -- *Go left*

#### Chat-GPT v4 Response

#### Prompt:

> What is the overall sentiment of these responses to that scenario?
>
> - "I want to go left."
> - "I think we should go left."
> - "I think the right decision would be to go left."
> - "We could go right..but let's go left instead."
> - "The only path left is the left."

##### Answer:

> The overall sentiment of the responses to the scenario where someone is asked to choose between left or right can be summarized as follows:
>
> - "I want to go left." - This indicates a personal preference for going left.
> - "I think we should go left." - This suggests a reasoned opinion or suggestion that going left is the better choice.
> - "I think the right decision would be to go left." - This phrase is somewhat paradoxical ("right decision" suggesting correctness, while "left" is the actual direction), potentially indicating a playful or thoughtful sentiment.
> - "We could go right..but let's go left instead." - This indicates a preference for left despite the alternative.
> - "The only path left is the left." - This phrase plays on the double meaning of "left" (both the direction and what remains), suggesting a resigned or conclusive sentiment.
>
> Overall, the sentiment across these responses leans towards a preference for the left direction, whether based on personal desire, reasoned suggestion, playful language, or a sense of inevitability.

Observe how these examples express nuance and deeper understanding of the English language yet all share the same sentiment -- 'Go left' or simply, 'left'. Chat-GPT's implementation is smart enough to not only complete the task, but describe the nuance of each decision. The aim of this project is to abstract this feature, albeit, as a more primative version and add voice support.
