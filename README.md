Ansible-lint mirror
====================

Mirror of ansible-lint for pre-commit with conda as a language.

For pre-commit: see https://github.com/pre-commit/pre-commit
For ansible-lint: see https://github.com/ansible/ansible-lint

### Using ansible-lint with pre-commit and conda:

Add this to your `.pre-commit-config.yaml`

```yaml
 - repo: https://github.com/Quantco/pre-commit-mirrors-ansible-lint
   rev: ''  # Use the sha / tag you want to point at
   hooks:
     - id: ansible-lint-conda
```

