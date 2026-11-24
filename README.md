# Bedrock AI plugins for Claude

Free tools for owners of small and mid-sized businesses, from [Bedrock AI](https://bedrockai.xyz).

## Opportunity Audit

Find the three jobs most worth taking off your plate.

Tap through six quick questions about your week (about two minutes). You get the three jobs most worth handing off, what you said that points to each one, what changes once it's sorted, and which to do first. Then, if you want them set up, you can book a free 15-minute call with Bedrock AI.

No sign-up, and it never asks for your email.

### Install in Claude Code

```
/plugin marketplace add rmbuildit/bedrock-ai-plugins
/plugin install opportunity-audit@bedrock-ai
```

Then ask something like "Where could my business save time each week?"

The plugin connects to the audit server at `https://audit.bedrockai.xyz/mcp` to show the tap-to-answer panel. If the connection is switched off or the panel can't show, it asks five short questions in chat instead.

### Use it in Claude or ChatGPT without the plugin

Add `https://audit.bedrockai.xyz/mcp` as a custom connector in Claude, or as an app in ChatGPT developer mode.

## Privacy and terms

- Privacy policy: https://bedrockai.xyz/privacy-audit/
- Terms: https://bedrockai.xyz/terms-audit/
- Contact: hello@bedrockai.xyz

The audit doesn't store your answers.

## Licence

MIT. See [LICENSE](LICENSE).
