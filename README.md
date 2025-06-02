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
const sentence = [
  { word: "Put", distractor: "xxx" },
  { word: "the", distractor: "yyy" },
  { word: "cake", distractor: "zzz" }
];

// Custom script handles left/right positioning and timing
