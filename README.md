# jsPsych Word Maze Task (Custom Version)

A jsPsych-based Word Maze Task designed to measure incremental sentence processing.  
Developed for a bilingualism and cognitive control experiment.

## Features

- Sentence-by-sentence word maze presentation
- Each trial presents a target word and a distractor
- Randomized left/right positioning of correct words
- Supports ambiguous and unambiguous sentence conditions

## Usage Example

```javascript
    const sentences = [ 
      {
        sentence_id: "amb1",
        condition:"ambiguous",
        target: "Put the frog on the napkin onto the box.",
        distractor: "xxx run some hope above his year until any." 
      },

// Custom script handles left/right positioning and timing

