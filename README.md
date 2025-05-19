# Text Analyzer Toolkit

A simple yet powerful text analysis toolkit for Python that provides basic text processing and analysis capabilities.

## Features

- Word and character counting
- Sentence analysis
- Reading time estimation
- Most common words identification
- Text cleaning utilities
- Email and URL extraction

## Installation

```bash
pip install text-analyzer-toolkit
```

## API Reference

### TextAnalyzer
Main class for text analysis.
Methods

- word_count(): Count total words
- character_count(include_spaces=True): Count characters
- sentence_count(): Count sentences
- most_common_words(n=5): Get most frequent words
- average_word_length(): Calculate average word length
- reading_time(wpm=200): Estimate reading time
- get_summary(): Get complete analysis summary


### Utility Functions


- clean_text(text): Clean and normalize text
- count_words(text): Simple word counting
- extract_emails(text): Extract email addresses
- extract_urls(text): Extract URLs

### Development

- Clone the repository
- Install development dependencies: pip install -e .[dev]
- Run tests: pytest
- Format code: black text_analyzer/

### License
MIT License

### Contributing

- Fork the repository
- Create a feature branch
- Make your changes
- Run tests
- Submit a pull request

