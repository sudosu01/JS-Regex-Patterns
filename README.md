# JS-Regex-Patterns
This is a curated list of JavaScript regex patterns to identify common types of secrets and credentials in source code.
Useful for building linters, scanners, CI/CD checkers, or for educational purposes.

# What's Included?
- API Keys (AWS, Stripe, Slack)
- Auth tokens (JWT, Bearer, Basic)
- Private keys
- Email addresses
- Phone numbers
- DB URLs

#Example
{
  "AWS Key": /AKIA[0-9A-Z]{16}/i,
  "JWT": /ey[A-Za-z0-9\-_=]+\.[A-Za-z0-9\-_=]+\.[A-Za-z0-9\-_.+/=]*/i
};
