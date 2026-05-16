**A6**

1. Which two classes does your CNN confuse most?
*my model gets confused the most on two classes, ie, shirt with t-shirt and t-shirt with shirt.

2. Why do you think that’s happening (from the images, not the model)?
*In the images, some important qualities that distingish a shirt from a t-shirt, like the collar, buttons, etc, are not clearly visible as the images are very blurred.

3. If you had to fix this for production, what would you try? (More data? Bigger images? Colour
photos?)
*I would use bigger images with higher resolution to increase the image quality. Using colored images will also help to highlight the important distinguishing features of each clothing item.


---


**Task B6**

Where does your persona break most reliably?
 Would adding more details to the system prompt help?
 Or is the model just too small? When would you reach for GPT-4 / Claude instead?

My persona breaks most reliably when handling technical, factual, or coding-related questions.
In these situations, the dragon-warrior voice disappears and becomes plain, generic language.
This is clearly seen in answers like Python loops and factual questions about events.
The model also tends to hallucinate incorrect facts, which weakens reliability further.
Creative and emotional prompts, however, maintain strong character consistency.

Adding more detail to the system prompt may help slightly but won’t fully fix the issue.
In some cases, a longer prompt may even confuse the model or reduce focus.
The core problem is the model struggling to balance persona with accuracy.
It can either stay in character or be factual, but not consistently both.
For real-world use, stronger models like GPT-4 or Claude are better choices.


---

