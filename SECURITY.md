# Security Policy

## Supported Versions

As this is a template repository, we only provide security updates for the latest version. If you've forked this repository, we recommend keeping your fork up to date with the upstream repository.

## Reporting a Vulnerability

If you discover a security vulnerability in this template, please report it to us through coordinated disclosure.

**Please do not report security vulnerabilities through public GitHub issues.**

Instead, please report them by emailing [INSERT EMAIL ADDRESS] or by using GitHub's private vulnerability reporting feature if available.

Please include the following information in your report:

- Description of the vulnerability
- Steps to reproduce the vulnerability
- Potential impact of the vulnerability
- Any possible mitigations you've identified

## Security Considerations

When using this template, please be aware of the following security considerations:

1. **Environment Variables**: Never commit your `.env` file or any API keys to version control. The `.env.example` file is provided as a template only.

2. **Authentication Secrets**: The `AUTH_SECRET` should be a strong, randomly generated secret. Never use the default value in production.

3. **AI Provider Keys**: API keys for AI providers should be kept secure and rotated regularly.

4. **Database Security**: When using Vercel Postgres or any database, ensure proper access controls are in place.

5. **File Uploads**: When using Vercel Blob or any file storage, be aware of file type restrictions and size limits.

## Best Practices

- Regularly update dependencies to get the latest security patches
- Use environment variables for all secrets and configuration
- Implement proper authentication and authorization checks
- Validate and sanitize all user inputs
- Use HTTPS in production
- Regularly audit your deployed application for security issues

## Acknowledgements

We appreciate the security research community and welcome responsible disclosure of security vulnerabilities. We strive to acknowledge all legitimate reports and fix verified issues as quickly as possible.