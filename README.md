1) You would fit your automated tests within a Github action that runs whenever code is pushed. This provides immediate feedback to developers, helping catch issues early in the development cycle, preventing them from being merged into the production branch.

2) No, E2E tests are designed to verify full user interactions are behaving correctly. They aren't intended to test the outputs isolated, internal functions.



