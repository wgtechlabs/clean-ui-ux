# Clean UI/UX

![Clean UI/UX banner](https://ghrb.waren.build/render/banner?header=Clean+UI%2FUX&subheader=Clean+interfaces.+Clear+decisions.+Purposeful+motion.&bg=101418-34404D&color=FFFFFF&subheadercolor=D9E0E8&headerfont=Inter&subheaderfont=Inter&support=true&watermarkpos=bottom-right)

<!-- Created with [GitHub Repo Banner](https://github.com/warengonzaga/github-repo-banner). -->

One Codex plugin for designing and improving interfaces with clear visual direction, usable interactions, accessibility, and purposeful motion.

## ✨ Features

- Establishes product-specific visual direction and coherent interface systems.
- Improves hierarchy, responsive behavior, content, and interaction states.
- Considers keyboard use, focus, contrast, touch targets, and reduced motion.
- Uses animation to communicate state, guide attention, or add deliberate delight.
- Bundles one self-contained skill with no runtime dependency on its inspiration projects.

## 🚀 Getting Started

You need Codex with plugin support and access to this GitHub repository.

Register the marketplace:

```sh
codex plugin marketplace add wgtechlabs/clean-ui-ux
```

Restart Codex, open the Plugins Directory, select **Clean UI/UX**, and install the plugin. Start a new chat before using it.

The repository is private until its visibility is changed. GitHub access is required to add its marketplace.

## 📖 Usage

Ask Codex to design or improve an interface, for example:

- “Use Clean UI/UX to redesign this settings page for mobile.”
- “Review this checkout flow for usability, accessibility, and motion.”
- “Add a purposeful loading transition and respect reduced-motion settings.”

Motion guidance is for interface interactions and transitions. It does not specialize in standalone motion graphics.

## 🛠️ Development

The plugin contains a portable `plugin.json`, a repository marketplace entry, and the bundled skill at `skills/clean-ui-ux/SKILL.md`. It has no runtime code or dependency installation.

Check both manifests as JSON with:

```sh
python -m json.tool plugin.json
python -m json.tool .agents/plugins/marketplace.json
```

Review the skill instructions and verify that the plugin name, marketplace entry, and skill name remain `clean-ui-ux`.

## 🤝 Contributing

Follow [Clean Workflow](https://github.com/wgtechlabs/clean-flow): create feature branches from `dev`, target pull requests to `dev`, and squash-merge after review and required checks. Promote stable `dev` to `main` with a release pull request and merge commit.

Use [Clean Commit](https://github.com/wgtechlabs/clean-commit) for commit messages. Repository-specific instructions are in [AGENTS.md](AGENTS.md).

## 🐛 Issues & Support

Report bugs or request improvements in [GitHub Issues](https://github.com/wgtechlabs/clean-ui-ux/issues).

## 📄 License

No license has been specified yet.

## 👥 Authors & Contributors

Maintained by [WG Technology Labs](https://github.com/wgtechlabs).

### References

This guidance draws on ideas from the following public resources: [Taste Skill](https://github.com/Leonxlnx/taste-skill), [UI UX Pro Max](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill), and [Design Motion Principles](https://github.com/kylezantos/design-motion-principles).
