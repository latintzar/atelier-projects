# Atelier Neyra projects

Atelier Projects is an agent skill for discovering, trying and building on Peter Neyra’s public work.

Ask your coding agent to find an appropriate project, open its working demo or help you run and adapt its source. The skill includes a public project index and links to each project's own documentation and service setup.

[Portfolio](https://atelierneyra.com) · [Software](https://atelierneyra.com/software/) · [Hardware](https://atelierneyra.com/hardware/) · [Web Experiences](https://atelierneyra.com/web-experiences/) · [Demos](https://preview.atelierneyra.com) · [Documentation](https://docs.atelierneyra.com)

## Explore a project

Choose the work by what it does, open its actual app or download, then read its product tour before deciding what to run or adapt. These tours show a complete journey, product areas and the source behind them:

| Project | Experience and source tour |
| --- | --- |
| Rocoto | [Incoming orders, packing sheets and QR-linked weight review](https://github.com/latintzar/ai-native-erp/blob/main/docs/product-tour.md) |
| Harness | [Business conversations, tools and generative UI](https://github.com/latintzar/harness/blob/main/docs/product-tour.md) |
| Farm-to-restaurant route planner | [Compare basket presets and calculate a VROOM route](https://github.com/latintzar/farm-to-restaurant-route-planner/blob/main/docs/product-tour.md) |
| Leo.casa | [Edit a quote, discuss the job and review milestones](https://github.com/latintzar/renovation-marketplace/blob/main/docs/product-tour.md) |
| DisDat.dev | [Spoken browser feedback to a grounded coding task](https://github.com/latintzar/disdat/blob/main/docs/product-tour.md) |
| Social Recipes | [Shared Reel to structured recipe and video](https://github.com/latintzar/social-recipes-kit/blob/main/docs/product-tour.md) |
| Vitrina Local | [Recipe discovery to a local-shop basket](https://github.com/latintzar/vitrina-local/blob/main/docs/product-tour.md) |
| Hermes Caller | [Call to transcript and debrief](https://github.com/latintzar/hermes-caller/blob/main/docs/product-tour.md) |
| Messier ’57 | [Play a groove and inspect the instrument](https://github.com/latintzar/messier57-instrument/blob/main/docs/product-tour.md) |

Browse [all project guides](https://docs.atelierneyra.com/) for the complete collection.

## Add the skill

Run this from your project with Node.js 22.20 or later:

```sh
npx skills add latintzar/atelier-projects --skill atelier-projects
```

Choose your agent when prompted. To select Codex directly:

```sh
npx skills add latintzar/atelier-projects --skill atelier-projects -a codex
```

The [Vercel Skills CLI](https://github.com/vercel-labs/skills) supports Codex, Claude Code, Cursor and other agents. It installs to the current project by default; add `-g` for your user account. You can inspect the [skill](skills/atelier-projects/SKILL.md) before installing.

In Codex, you can also ask its installer:

```text
$skill-installer install the skill at https://github.com/latintzar/atelier-projects/tree/main/skills/atelier-projects
```

## Try it

```text
Use $atelier-projects to find the route planner and help me run it for my region.
```

```text
Which Atelier project can turn a shared Instagram recipe Reel into structured ingredients?
```

```text
Show me how Harness separates a business vertical from the shared agent runtime.
```

The skill uses ordinary web and repository tools available to your agent. It links to current public records and includes a dated fallback index. Each project's repository remains authoritative for its code, licence, setup and reached stage.

## Included work

The index covers 17 software projects, nine hardware/design cases and the Economist text case. Public source, build records, hosted samples and portfolio cases are identified separately. It includes Rocoto, Harness, DisDat.dev, Leo.casa, the VROOM route planner, Vitrina Local, Social Recipes, Hermes Caller, geospatial projects and Panel Speakers.

Projects that use external services have their own configuration and account requirements. The skill helps your agent find those guides and use your credentials privately.

## Update

```sh
npx skills update atelier-projects
```

[Index provenance](SOURCES.md) · [MIT licence](LICENSE)

[made by atelier neyra](https://atelierneyra.com)
