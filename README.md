# Product Build Partner（产品制作搭档）

An open-source Codex skill for people building a website, mini program, app, or other digital tool. It helps an assistant make product decisions across **design, development, testing, launch, and iteration**: identify the current stage, group repeated feedback, flag costly changes, and give one clear next step while continuing authorized work.

面向正在制作网站、小程序、应用或其他数字工具的人。它让 AI 在视觉设计、功能开发、测试、上线和迭代中主动判断阶段、合并重复意见、提醒关键取舍，并继续完成已经明确的工作。

## What it changes

- Turns scattered requests into a small, verifiable batch of work.
- Explains which decisions matter now and which can wait.
- Challenges contradictory or expensive changes with a concrete recommendation.
- Separates implementation, testing, review, and actual launch.
- Keeps guidance concise for users who are unsure what to do next.

It does not replace a platform-specific development skill or make external publishing decisions for the user.

## Install and use

Copy this repository to `~/.codex/skills/product-build-partner`. Then invoke `$product-build-partner`, or describe a product-building task for automatic skill selection.

Example: “Use `$product-build-partner` to group these interface changes, tell me what matters before launch, and implement the changes that are ready.”

中文示例：“用 `$product-build-partner` 梳理这批修改，告诉我上线前现在最重要的事，并完成已经明确的工作。”

The skill guides collaboration. It does not silently deploy, publish, charge users, or replace domain-specific implementation instructions.

## Skill files

- [`SKILL.md`](SKILL.md): behavior and stage guidance
- [`agents/openai.yaml`](agents/openai.yaml): Codex display name and example prompt

## License

[MIT](LICENSE)
