# Contributing to OpenAIAO

Thank you for your interest in contributing to the OpenAIAO Specification! Follow these guidelines to ensure a smooth collaboration.

## How to Contribute
### 1. Fork the Repository
- Click the **Fork** button at the top-right of the repository.
- Clone your fork locally:
  ```sh
  git clone https://github.com/YOUR-USERNAME/openaiao-specification.git
  cd openaiao-specification
  ```

### 2. Create a New Branch
- Use descriptive branch names:
  ```sh
  git checkout -b feature-new-endpoint
  ```

### 3. Make Your Changes
- Ensure your modifications align with the OpenAIAO principles.
- Run validation checks (if applicable):
  ```sh
  npm run validate  # Example script for JSON schema validation
  ```

### 4. Commit & Push
- Follow commit message conventions:
  ```sh
  git commit -m "feat: Added new AI endpoint for businesses"
  git push origin feature-new-endpoint
  ```

### 5. Open a Pull Request
- Go to the main repository and click **New Pull Request**.
- Fill out the PR template and submit for review.

## Guidelines
- Follow JSON-LD and Schema.org standards where applicable.
- Ensure backward compatibility when modifying the specification.
- Discuss major changes in GitHub Discussions before implementation.

## Code of Conduct
By contributing, you agree to uphold our [Code of Conduct](CODE_OF_CONDUCT.md).

---
Thank you for helping to improve OpenAIAO!
