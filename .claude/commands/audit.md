1. Run npm audit to check for security issues.

2. If any issues are found, report them to the user — do NOT run npm audit fix (dependencies are pinned to specific compatible versions; bumping them breaks the app).

3. Run npm test to ensure stability.