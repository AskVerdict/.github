<div align="center">

# AskVerdict AI

**Multi-agent AI debate engine. Get AI-powered verdicts on any question.**

[Website](https://askverdict.ai) | [Documentation](https://askverdict.ai/docs) | [Get API Key](https://askverdict.ai/settings/api)

</div>

## What We Build

AskVerdict AI is a multi-agent debate engine that pits multiple AI personas against each other to analyze questions from every angle. Instead of a single biased answer, you get structured debates with evidence, cross-examination, and synthesized verdicts with confidence scores.

**Try it now:**

```bash
npx @askverdict/cli "Should I use PostgreSQL or MongoDB for my SaaS?"
```

## Open Source Packages

| Package | Description | npm |
|---------|-------------|-----|
| [`@askverdict/sdk`](https://github.com/askverdict/askverdict/tree/main/packages/sdk) | TypeScript API client | [![npm](https://img.shields.io/npm/v/@askverdict/sdk)](https://www.npmjs.com/package/@askverdict/sdk) |
| [`@askverdict/cli`](https://github.com/askverdict/askverdict/tree/main/packages/cli) | Command-line interface | [![npm](https://img.shields.io/npm/v/@askverdict/cli)](https://www.npmjs.com/package/@askverdict/cli) |
| [`@askverdict/types`](https://github.com/askverdict/askverdict/tree/main/packages/types) | Shared TypeScript types | [![npm](https://img.shields.io/npm/v/@askverdict/types)](https://www.npmjs.com/package/@askverdict/types) |

## How It Works

1. **Ask a question** - Any decision, comparison, or open-ended question
2. **AI agents debate** - Multiple specialized personas argue different sides with evidence
3. **Cross-examination** - Agents challenge each other's claims and reasoning
4. **Verdict** - A synthesized recommendation with confidence scores and dissenting views

## Quick Start (SDK)

```typescript
import { AskVerdictClient } from '@askverdict/sdk';

const client = new AskVerdictClient({ apiKey: 'your-api-key' });

const { verdict } = await client.createVerdict({
  question: 'React vs Vue for a new startup project?',
  mode: 'balanced',
});

console.log(verdict.verdict.recommendation);
```

## Links

- **Website**: [askverdict.ai](https://askverdict.ai)
- **Source**: [github.com/askverdict/askverdict](https://github.com/askverdict/askverdict)
- **npm**: [@askverdict](https://www.npmjs.com/org/askverdict)
- **Discord**: [![Discord](https://img.shields.io/discord/829168897080557579?style=flat-square&logo=discord&logoColor=white&label=discord&color=5865F2)](https://discord.gg/Ar5pcaZB99)

Join the GLINR | GLINCKER Discord to talk with the team building AskVerdict.

![GLINR Discord banner](https://discord.com/api/guilds/829168897080557579/widget.png?style=banner2)

---

<div align="center">

Built with care by the AskVerdict team.

MIT Licensed

</div>
