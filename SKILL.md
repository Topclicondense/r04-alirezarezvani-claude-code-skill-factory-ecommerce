        ---
        name: "r00-alirezarezvani-claude-code-skill-factory--ecommerce"
        description: >
          🛒 E-commerce & Retail skill suite derived from alirezarezvani/claude-code-skill-factory.
          Product catalogue optimisation, conversion rate, customer journey and retail analytics.
          Provides 10 specialised commands for ecommerce, retail, shopify workflows.
        version: "1.0.0"
        domain: ecommerce
        tags: ["ecommerce", "retail", "shopify", "woocommerce", "conversion", "ux"]
        source: "https://github.com/alirezarezvani/claude-code-skill-factory"
        license: MIT
        ---

        # 🛒 E-commerce & Retail Skill Suite

        > Derived from **alirezarezvani/claude-code-skill-factory** · Focus: _skill scaffolding, code agents, slash command generation_

        ## Overview

        This skill provides 10 production-ready commands tailored for
        **E-commerce & Retail** workflows. All commands follow a consistent
        interaction pattern with structured output, progress tracking and
        actionable recommendations.

        ## Available Commands

        - `/product-copy` — Conversion-optimised product title, description and bullet points from spec sheet
- `/price-strategy` — Dynamic pricing recommendation using competitor data and elasticity model
- `/cart-abandonment` — Cart abandonment email sequence with personalisation tokens and timing logic
- `/inventory-forecast` — Demand forecasting report with reorder points and safety stock calculation
- `/cro-audit` — CRO heatmap analysis, funnel drop-off diagnosis and A/B test prioritisation
- `/customer-segment` — RFM segmentation, LTV prediction and targeted campaign briefs
- `/returns-analysis` — Return rate root-cause analysis with product quality and size-guide fixes
- `/review-response` — AI-generated personalised responses to product reviews (positive + negative)
- `/bundle-suggest` — Cross-sell and bundle recommendation engine from order history patterns
- `/marketplace-audit` — Amazon/eBay listing health score, Buy Box eligibility and keyword gap

        ## Interaction Pattern

        Every command follows this structured response format:

        ```
        1. CONTEXT CHECK   — Verify inputs and confirm scope with user
        2. ANALYSIS        — Deep analysis with live progress display
        3. FINDINGS TABLE  — Structured results with severity / priority
        4. RECOMMENDATIONS — Prioritised action list (quick wins first)
        5. NEXT STEPS      — Suggested follow-up commands
        ```

        ## UI Conventions

        | Symbol | Meaning              |
        |--------|----------------------|
        | ✓      | Passed / complete    |
        | ✗      | Failed / critical    |
        | ⚠      | Warning / review     |
        | ⟳      | In progress          |
        | ░      | Pending              |
        | 🔴     | Critical severity    |
        | 🟠     | High severity        |
        | 🟡     | Medium severity      |
        | 🟢     | Low / informational  |

        Progress bars use block characters:
        `[████████░░] 80%`

        ## Quick Start

        ```bash
        # Install this skill
        cp -r . ~/.claude/skills/r00-alirezarezvani-claude-code-skill-factory--ecommerce/

        # In Claude Code
        /read ~/.claude/skills/r00-alirezarezvani-claude-code-skill-factory--ecommerce/SKILL.md
        ```

        Then simply describe your task and Claude will route to the
        appropriate command automatically.
