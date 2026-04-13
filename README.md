# Terms-Simplified

Understand Terms & Conditions in under 60 seconds.

## Problem
Users accept Terms & Conditions blindly due to complexity and length, leading to uninformed decisions and hidden risks.

This product reduces decision friction by summarizing legal text into actionable insights in under 60 seconds.

## Users
- Consumers
- Non-legal users
- Busy professionals

## Solution
An AI-powered tool that converts complex legal text into simple, easy-to-read summaries for a 12-year-old reading level.

## Key Features
- 60-second readable summaries
- Simple language output
- Verdict system (Safe / Caution / Risky)
- File Upload Support
- Estimated reading time
- Multiple language support

## Example Output
<img width="887" height="851" alt="image" src="https://github.com/user-attachments/assets/e1395ce6-ceaa-43b2-85ee-4c1c00ab5730" />


## Error Handling
- Unsupported file types are rejected
- Empty or unreadable files are flagged
- File size limits applied

## Success Metrics
- Reading time < 60 seconds
- Readability level (grade 6–8)
- User comprehension
- % of users identifying risks
- Reduction in blind acceptance

## Product Decisions
- Structured output instead of plain summary to improve scannability
- Focused on risks to help users make decisions quickly
- Limited output length to ensure usability
- Multi language support to ensure wider audience coverage

## Limitations
- May miss nuanced legal clauses
- Depends on input quality
- Supported formats include PDF (.pdf) and Word (.doc, .docx) only
- Will not work in situations where copy-pasting terms is not possible eg: mobile application scenarios.

## Data Handling
- Uploaded files are processed in real-time and are not stored.
- This ensures user privacy and reduces data security risks.

## Future Improvements
- Chrome extension
- URL input (auto-fetch T&C)
- Highlight risky clauses in original text
