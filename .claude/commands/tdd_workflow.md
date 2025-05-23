Test-driven development for: $ARGUMENTS

1. WRITE TESTS FIRST
   - Write comprehensive tests for $ARGUMENTS
   - Cover expected inputs/outputs
   - Include edge cases
   - DO NOT create mock implementations

2. VERIFY TESTS FAIL
   - Run tests and confirm they fail
   - DO NOT write implementation code yet

3. COMMIT TESTS
   - git add test files
   - git commit -m "Add tests for $ARGUMENTS"

4. IMPLEMENT TO PASS
   - Write minimal code to pass tests
   - DO NOT modify the tests
   - Iterate until all tests pass
   - Use subagents to verify not overfitting

5. COMMIT IMPLEMENTATION
   - git add implementation
   - git commit -m "Implement $ARGUMENTS"