## Reflection

### 1. What part of the code was most confusing and why?
The part that tripped me up a bit was the setInterval() function and how it keeps running automatically. I didn’t fully get how the loop knew when to stop until I looked closer and saw that clearInterval() is used after a certain number of cycles. Once I understood that, it made more sense how timing is controlled.

### 2. How does the animation help visualize asynchronous behavior?
The animation keeps updating the screen while the rest of the page stays normal. It helped me understand that JavaScript can run things in the background (like changing emojis) without freezing the page. That made async logic feel more real.

### 3. What did you change or improve, and what effect did it have?
I added a background color change that switches every few cycles to make it more visually interesting. I also added a little confetti emoji celebration at the end to make it feel like a reward. It made the animation more fun and helped it stand out more from the original version.
