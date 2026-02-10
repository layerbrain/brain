# Brain

Brain is a generally intelligent system that generates and operates software on your computer, backed by powerful machines on the internet.

Generate native software, automate complex workflows, and provision ephemeral cloud machines on demand — all through natural language in your terminal.

![Brain Demo](assets/cli-3.gif)

## Getting Started

### 1. Install

**macOS / Linux:**

```bash
curl -fsSL https://layerbrain.com/cli | sh
```

**Windows:** Coming soon

### 2. Login

Run `brain` and use the `/login` command to authenticate your account.

### 3. Ask Brain to do something

Just type what you want in plain English. Brain can read and write files, run commands, and build software on your machine.

```
> deploy an n8n server for me
```

Brain will provision a machine, set everything up, and deploy it.

Or run a one-off command without entering the interactive session:

```bash
brain -f "deploy an n8n server for me"
```

You can also pipe input directly:

```bash
echo "explain this error" | brain
```

### 4. Work with files

Drag and drop files directly into the terminal, or reference them with `@`:

```
> @main.py add error handling to the API calls
```

### 5. Control permissions

Use `/mode` to set how much autonomy Brain has:

- **Low** — file edits and read-only commands
- **Medium** — reversible commands
- **High** — all commands

### 6. Switch models

Use `/model` to pick a different AI model mid-session.

### 7. Use memory

Brain remembers context across sessions. Use `#` to save something to memory, or `/memory` to view and edit what Brain remembers.

## Reporting Bugs

Use the `/bug` command to report issues directly within Brain, or [file a GitHub issue](https://github.com/layerbrain/brain/issues).

## Data Collection, Usage, and Retention

When you use Brain, we collect usage data including command interactions, session metrics, and feedback submitted via the `/bug` command.

### How We Use Your Data

See our [data usage policy](https://layerbrain.com/policies/data-usage).

### Privacy Safeguards

We implement safeguards to protect your data, including limited retention periods for sensitive information and restricted access to session data. For full details, review our [Terms of Service](https://layerbrain.com/policies/terms-of-service) and [Privacy Policy](https://layerbrain.com/policies/privacy).
