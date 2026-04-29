IMPORTANT: Ensure you've thoroughly reviewed the [AGENTS.md](AGENTS.md) file before beginning any work.

## Personal Notes

- Forked for learning purposes and local experimentation
- Remember to keep API keys out of version control (use `.env` file)
- Prefer running experiments in a dedicated virtualenv (`python -m venv .venv`)
- Useful alias: `alias fcc='python main.py'` for quick CLI access
- Use `pip install -r requirements.txt` after pulling upstream changes to stay in sync
- Default model: prefer `claude-3-5-haiku` for quick tests (cheaper), switch to `claude-3-5-sonnet` for real tasks

## Local Dev Tips

- Run `git fetch upstream && git merge upstream/main` periodically to pull in upstream fixes
- Keep a `scratch/` directory (gitignored) for throwaway test scripts
- If hitting rate limits, add a short `--delay 2` flag between requests when batch testing
