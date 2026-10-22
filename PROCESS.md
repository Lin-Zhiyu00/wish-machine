# Development Process

## Concept
I wanted to make a gentle, simple interactive page where users can type and send wishes. The idea is to create a relaxing little moment.

## Planning
1. Design the basic page layout: input box, two buttons, display area.
2. Plan the interaction rule: reject empty input, show warning text.
3. Plan animation: wish text floats up and disappears.
4. Prepare random warm messages to show after sending a wish.

## Implementation steps
1. Write HTML structure for the page.
2. Add CSS for background, colours, layout and animation.
3. Write JavaScript:
   - Read text from the input box
   - Check if input is empty
   - Create floating text element
   - Show random message
   - Reset function to clear screen
4. Test the page:
   - Test normal input
   - Test empty click (error case)
   - Test reset button
5. Adjust colour and animation speed for better visual effect.

## Problems & solutions
- Problem: When users send empty text, the animation still runs.
  Solution: Add an `if` check to stop the function and show a reminder.
- Problem: Floating text position was messy.
  Solution: Use random horizontal position within the container.

## Reflection
The finished project meets the basic interactive requirements. In future I could add sound effects, nicer particle styles and limit the maximum length of input text.
