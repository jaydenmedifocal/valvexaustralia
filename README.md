# Valvex Website

Professional valve solutions and process systems website with Shopify integration.

## 🔒 GitHub Security Compliance

This repository follows GitHub's security best practices:

- ✅ **No secrets in code** - All tokens stored in GitHub Secrets
- ✅ **Secret scanning enabled** - Automated detection of exposed secrets
- ✅ **Branch protection** - Code reviews required for main branch
- ✅ **Access controls** - Limited repository access
- ✅ **2FA required** - Two-factor authentication enforced
- ✅ **Audit logging** - All actions logged and monitored

## 🚀 Setup Instructions

### 1. Create GitHub Repository
1. Create a new repository on GitHub
2. Clone the repository locally
3. Copy your website files to the repository

### 2. Configure GitHub Secrets
1. Go to your repository **Settings**
2. Navigate to **Secrets and variables** > **Actions**
3. Click **New repository secret**
4. Name: `SHOPIFY_TOKEN`
5. Value: `[Your Shopify token from your Shopify admin]`
6. Click **Add secret**

### 3. Enable Branch Protection
1. Go to **Settings** > **Branches**
2. Click **Add rule** for `main` branch
3. Enable **Require pull request reviews**
4. Enable **Require status checks**
5. Enable **Restrict pushes that create files**

### 4. Enable Secret Scanning
1. Go to **Settings** > **Security**
2. Enable **Secret scanning**
3. Enable **Push protection**

## 🛡️ Security Features

- **GitHub Secrets** - No tokens in code
- **Secret scanning** - Automated detection
- **Branch protection** - Code review required
- **CSP headers** - XSS protection
- **Token validation** - Format verification
- **Rate limiting** - API abuse prevention
- **Security scanning** - CI/CD pipeline checks

## 📋 Deployment

The website is automatically deployed to GitHub Pages when:
- ✅ Security scan passes
- ✅ All checks pass
- ✅ Code is pushed to main branch

## 🔧 Development

For local development:
1. Set `SHOPIFY_TOKEN` environment variable
2. Run `python -m http.server 8000`
3. Visit `http://localhost:8000/index.html`

## 📞 Support

For security issues, contact the repository maintainers.