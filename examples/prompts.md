# Example prompts for the WordPress MCP server

These work as written in Claude, ChatGPT, Cursor, Codex, Gemini CLI and the other clients listed in the README. Anything that changes the account comes back as an approval first.

## Read and report

- Ask Sprites which WordPress pages lost position in the last 28 days and why.
- With Sprites, cluster our blog by intent and tell me which posts cannibalise each other.

## Change, create and launch

- With Sprites, write a post on "wordpress speed optimization" and draft it in WordPress.
- Use Sprites to rewrite the meta title and description on our /pricing page.
- Have Sprites add an FAQ section with schema to the three posts that get AI Overview impressions.

## Tips

- Name the campaign, ad set or page in full. Sprites receives only the request, not the earlier chat.
- Say the period ("last 30 days", "this quarter"); your client passes today's date so it resolves correctly.
- Working on several businesses? Say "switch to <business name>" first (`choose_business`).
- To compare channels, ask about them in one request, for example "compare Google and Meta CPA last month".
