Here is the corrected and improved version of your `README.md` file:

```markdown
# MCP Client

## How to Run

1. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

2. If needed, upgrade the `anthropic` package:
   ```bash
   pip install --upgrade anthropic
   ```

3. Set the `CLAUDE_API_KEY` environment variable:
   ```bash
   export CLAUDE_API_KEY=<your_api_key>
   ```

4. Start the server:
   ```bash
   python mcp_server.py
   ```
   
5.then can ask a question by running:

   ```bash
   python ask_claude.py "--your question--"
   ```
