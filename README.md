### Technical aspects
- Includes a render() function, that conditionally regenerates the view each time the store is updated.
- Includes single-purpose template generation functions.
- Includes event handler functions.
- DOES NOT add additional HTML elements to the boilerplate code's index.html file.
- Renders answer choices in a <form>.
- Uses semantic HTML, along with CSS and jQuery.
- Follows a11y best practices.
- Is fully usable by keyboard.
- Uses responsive design.

### User Stories
- The starting screen has a button that users can click to start the quiz.
- Users are prompted through a series of multiple choice questions that they can answer.
- Users are only prompted with 1 question at a time.
- Users are not be able to skip questions.
- Users can see which question they're on (for instance, "7 out of 10") and their current score ("5 correct, 2 incorrect").
### Upon submitting an answer, users:
- Receive textual feedback about their answer. If they were incorrect, they are told the correct answer.
- Interact with an element to move on.
- Are shown their overall score at the end of the quiz. In other words, how many questions they got right out of the total questions asked.
- Are given the ability to start a new quiz.
