# Contributing

Two rules:

1. **One notebook, one PR.** If you're improving notebook 3 (CNN) and also fixing
   a typo in notebook 1 (Bag of Words), please open two PRs.
2. **Keep the requirements file synchronized.** Any new top-level import must be
   pinned in `requirements.txt`.

## Local development

```bash
pip install -r requirements.txt
jupyter lab .
```

## Reporting issues

Please use the bug report template in `.github/ISSUE_TEMPLATE/`. Include the
PyTorch version, the notebook number, and the exact cell that fails.
