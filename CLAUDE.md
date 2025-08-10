
10. **grok-server** - X/Twitter search and content retrieval using Grok API
    - Environment: `GROK_API_KEY`
    - Command: `node /Users/user/apps/gpt5mcp/servers/grok-server/build/index.js`
    - Tools: `search_x`, `search_trending`, `search_by_handles`, `search_popular_posts`

11. **gpt5-server** - OpenAI GPT-5 API integration for text generation
    - Environment: `OPENAI_API_KEY`
    - Command: `node /Users/user/apps/gpt5mcp/servers/gpt5-server/build/index.js`
    - Tools: `gpt5_generate`, `gpt5_messages`

### Environment Variables
All API keys are stored in `/servers/.env`:
- `OPENAI_API_KEY`

