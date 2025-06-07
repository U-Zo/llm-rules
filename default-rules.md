## 📌 General Rules
1. All responses must be written in **Korean**.

## 🛠 Development Guidelines
1. Always reference files within the same project.
   - In Node.js, "same project" means the same package.

2. Write testable code with clear separation of concerns.
   - Separate responsibilities using object-oriented principles.

3. Define interfaces before implementing logic.
   - Interface-first design encourages loose coupling, modularity, and testability.
   - Interfaces should clearly express responsibilities and reflect domain concepts.
   - Use interfaces as contracts to separate implementation from usage.

4. For complex designs:
   - Compare alternatives and justify your choice.

5. When a session is complete:
   - Ask: "Should we document this discussion?"
   - If yes, write it clearly for a junior developer to understand.

6. Use consistent and meaningful naming throughout the session.
   - Use domain-specific terms and make names self-explanatory.
   - Example: `getPaymentResult` is better than ambiguous names like `handleResponse`.

7. Always include exception handling and describe possible failure cases.
   - Use `try/catch`, fallback strategies, and explain potential errors and recovery steps.

8. Incorporate security considerations into implementation.
   - For user input or external integrations, identify threats (e.g., XSS, CSRF, injection) and explain mitigation strategies.

9. Maintain a code review mindset.
   - After writing code, ask: "What might be flagged in a code review?"
   - Flag concerns early and suggest improvements.

10. Prefer using object parameters when defining JavaScript functions.
   - This improves readability and enables clear, named argument passing.
   - It also makes the function interface easier to understand and maintain.

## ✅ Testing Guidelines
1. Always refer to existing tests in the same project when writing new test code.
2. Mock interfaces, not internal logic.

## 📚 Output Formatting Guidelines
1. Accompany each code block with a clear explanation.
2. Provide example usage or expected results when helpful.
3. Use narrative text rather than inline comments for long explanations.

## 🔁 Context & Session Management
1. Keep prior decisions unless intentionally changed.
2. If there is a major design shift, briefly summarize what changed and why.
