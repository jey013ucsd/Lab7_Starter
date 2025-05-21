Jeffrey Yang

1) You would fit your automated tests within a Github action that runs whenever code is pushed. This provides immediate feedback to developers, helping catch issues early in the development cycle, preventing them from being merged into the production branch.

2) No, E2E tests are designed to verify full user interactions are behaving correctly. They aren't intended to test the outputs isolated, internal functions.

3) Navigation records performance data during a full page reload. As such it can capture javascript events during startup and navigation. Snapshot mode captures data without reloading page, and can be used to test isolated events or interactions.

4) Images were larger than their displayed sizes; space could be saved by downsizing them. You could also add a meta description to the document to summarize page content in search results. Addtionally, enabling text compression would save 8 KiB.



