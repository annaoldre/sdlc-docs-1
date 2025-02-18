# Test Outputs

NOTE: Update this section to cover the following
- Summary output (count + result codes)
- Describe function (more details for each result code)
- Per-issue detail output in JSON format (can convert to csv)
- Per-issue detail output in HTML format

For each test run, you will be informed if your site passed or failed for each issue that we looked for in that specific test suite.

- A **“pass”** is defined as code DID match the expected pattern/assertion defined in the test.
- A **“failure”** is defined as code DID NOT match the expected pattern/assertion defined in the test. 

```bash
::: START AudioEye SDK CLI :::

Scanning HTML from STDIN

Found 0 accessibility issues

Full Test Results were output to /example/folder/testing-sdk-output.html

::: END AudioEye SDK CLI :::
```

When a failure is returned, we will provide you the following information:
- **Unique issue identifier** – Can be used to track the issue in project management tools.
- **WCAG success criterion (name + number)** – What WCAG criteria was being tested
- **Issue name** – Description of the issue.
- **Issue location** – Where the issue occurred.
- **Fix advice (plain text)** - Explanation of the issue discovered.
- **Fix (code snippet)** - Code example on how to fix the issue.

```bash
::: START AudioEye SDK CLI :::

Scanning HTML from STDIN

Found 3 accessibility issues
   imgTextAlt - count: 3

Full Test Results were output to /example/folder/testing-sdk-output.html

::: END AudioEye SDK CLI :::
```
