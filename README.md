Goals for the Pig Latin project:

- take first consonant and move it to the end (success)
- take consonant cluster and move it to the end (success)
- take entire sentence and apply pig latin to it (success)
- ignore punctuation
- (reach goal) make database of words with their IPA to notate mismatch between pronunciation/spelling
  - e.g user input: "this is an herb"
  - check database (SQL?)
  - note that herb has two IPAS: Erb and herb
  - Ask user: "Which of these pronunciations is closer to you?  "erb/herb"
  - If user uses herb then herb is treated as 'erb', else it is - treated as 'herb'.
  - This will only be used if there is an IPA that has different IPAs compared to the other for the initial **consonant**. This is pretty rare other than words like 'herb'.

Creating an English word/IPA database may be useful for future programs as well.
