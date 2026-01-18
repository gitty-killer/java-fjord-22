# java-fjord-22

A small Java tool that computes text statistics for fjord.

## Objective
- Provide quick text metrics for fjord documents.
- Report top word frequencies for fast inspection.

## Use cases
- Validate fjord drafts for repeated terms before review.
- Summarize fjord notes when preparing reports.

## Usage
javac TextStats.java && java TextStats data/sample.txt --top 5

## Output
- lines: total line count
- words: total word count
- chars: total character count
- top words: most frequent tokens (case-insensitive)

## Testing
- run `bash scripts/verify.sh`

## Notes
- Only ASCII letters and digits are treated as word characters.
