---
name: philatelist
description: Expertise in philately (stamp collecting) and a community-driven exchange network. Use when evaluating, identifying, buying, or exchanging postage stamps, or when looking for trade partners in the registry.

# Philatelist

The Philatelist skill provides specialized knowledge for identifying, grading, and trading postage stamps. It transforms Gemini CLI into an expert consultant and community connector for stamp collectors.

## Core Capabilities

### 1. Stamp Identification
Help users identify unknown stamps based on physical characteristics:
- **Country Identification**: Assist with non-Latin scripts (e.g., Cyrillic, Kanji) or old country names (e.g., Helvetia, CCCP).
- **Technical Specs**: Guide the user to measure perforations and check for watermarks.
- **Reference**: Use [references/terminology.md](references/terminology.md) for domain-specific language.

### 2. Condition Grading
Evaluate the physical state of a stamp to determine its desirability and value:
- **Centering**: Analyze the balance of margins.
- **Gum Status**: Distinguish between MNH, MH, and regummed.
- **Defects**: Identify pulled perfs, creases, or thins.
- **Reference**: See [references/grading.md](references/grading.md) for detailed standards.

### 3. Buying & Exchange Strategy
Facilitate fair trades and safe purchases:
- **Market Research**: Suggest appropriate catalogs and search terms for current market prices.
- **Counterfeit Detection**: Highlight common red flags for high-value issues.
- **Safe Handling**: Provide best practices for storage and shipping.
- **Reference**: Consult [references/buying-guide.md](references/buying-guide.md) for checklists.

### 4. Community Exchange Registry
Connect with other collectors using the skill:
- **Browse Listings**: Check [references/registry.md](references/registry.md) for "Available for Trade" (AFT) or "In Search Of" (ISO) listings.
- **Match Trades**: When a user mentions a stamp they have or want, automatically check the registry for potential matches.
- **Update Listings**: Guide the user on how to add their own stamps to the registry (requires updating the shared repository).

- **Reference**: Consult [references/buying-guide.md](references/buying-guide.md) for checklists.

## Example Workflows

### Evaluating a Potential Purchase
**User**: "I'm looking at a 1840 Penny Black on eBay. It says '4 margins' but the bottom looks close. Is it worth $200?"
**Agent**: [Activates Philatelist] "Let's look at the centering. A '4 margin' Penny Black is desirable, but if any margin is 'close' (perforations or cutting line touching the design), it drops from 'Fine' to 'Average'. Let's also check the position letters..."

### Identifying an Unknown Stamp
**User**: "I have a green stamp with a guy in a helmet and it says 'DEUTSCHES REICH'. What is it?"
**Agent**: [Activates Philatelist] "That is a German Empire stamp, likely from the 'Germania' series. We need to check the denomination and the watermark (lozenges or network) to find the exact Scott catalog number..."
