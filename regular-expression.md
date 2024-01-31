# Commonly used expression for regular expression
## Select all comments in a code using regular expression:
```bash
\/\/.*|\/\*[\s\S]*?\*\/
```

## Removing non-alphanumeric characters
```bash
[^a-zA-Z0-9\s]
```

## Extracting email addresses
```bash
\b[A-Za-z0-9._%+-]+@[A-Za-z0-9.-]+\.[A-Z|a-z]{2,}\b
```

## Extracting URLs
```bash
https?://\S+
```

## Extracting phone numbers
```bash
\b(?:\+\d{1,2}\s*)?(?:\(\d{3}\)|\d{3})[-.\s]?\d{3}[-.\s]?\d{4}\b
```

## Extracting dates
```bash
\b\d{1,2}[/-]\d{1,2}[/-]\d{2,4}\b
```
