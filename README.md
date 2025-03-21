# PRotect: AI-Powered Pull Request Security Review  

PRotect is an automated security review system for GitHub Pull Requests (PRs). It consists of:  
1. **PRotect Chrome Extension** – A browser extension that analyzes PRs for security vulnerabilities, highlighting issues directly in the UI.  
2. **PRotect Probot** – A GitHub bot that automatically reviews PRs, comments on vulnerable code, and enforces security policies.  
3. **Code Testing Repository** – A repository containing test cases and vulnerable code samples for evaluating PRotect's capabilities.  

## Features  

### PRotect Chrome Extension  
- Scans PRs for vulnerabilities such as SQL injection, XSS, and insecure coding patterns.  
- Identifies vulnerable lines of code and provides explanations.  
- Displays security scores and risk levels in an intuitive interface.  

### PRotect Probot  
- Analyzes PRs automatically and assigns a security score.  
- If the security score is below 40, the PR is automatically closed.  
- Adds inline comments on vulnerable lines, guiding developers on security improvements.  

## How It Works  
1. A developer opens a PR.  
2. PRotect scans the PR for security risks.  
3. If vulnerabilities are found:  
   - The **Chrome Extension** highlights them in the PR interface and provides explanations.  
   - The **Probot** places inline comments on affected lines and may close the PR if the score is too low.  

## Repositories  
- **[PRotect Chrome Extension](https://github.com/PYRAG-PRotect/Extension_v_2)** – The browser extension for reviewing PRs.  
- **[PRotect Probot](https://github.com/PYRAG-PRotect/Probot)** – The GitHub bot for automated security enforcement.  
- **[Code Testing](https://github.com/PYRAG-PRotect/Code_For_Testing)** – A repository containing sample PRs with known vulnerabilities for testing PRotect.  

## Contributing  
We welcome contributions to improve PRotect. If you're interested, check out the respective repository’s `CONTRIBUTING.md` for guidelines.  

## Contact  
For issues or feature requests, open a GitHub issue in the relevant repository.  
