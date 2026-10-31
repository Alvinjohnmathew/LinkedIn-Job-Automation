# LinkedIn AI Auto Job Applier 🤖


A free, open-source tool that automates job applications on LinkedIn. It runs entirely on
your own computer, using your own LinkedIn account. It finds jobs relevant to you, fills in
the application questions — optionally with AI help — and applies using the resume you
provide. Can apply to 100+ jobs in under an hour.

Nothing is uploaded anywhere: your details stay in local files, and the control panel is
reachable only from your own machine.



## 🚀 Quick start

New here, or not comfortable editing code? Use the built-in control panel. You set
everything up in your web browser and run the tool with a button — no editing Python files,
no terminal commands.

1. **Install Python once.** Get it from https://www.python.org/downloads/ (on Windows, tick
   **"Add Python to PATH"** during install). You also need
   [Google Chrome](https://www.google.com/chrome).
2. **Download this project** (green "Code" button → "Download ZIP", then unzip; or clone it).
3. **Double-click the launcher for your system:**
    - **macOS:** `start.command`
    - **Windows:** `start.bat`
    - **Linux:** `start.sh` (run `./start.sh` in a terminal)

    The first run sets things up automatically (it may take a minute). After that it's quick.
4. Your browser opens the **control panel** automatically (the exact address, e.g.
   `http://127.0.0.1:5000`, is shown in the launcher window). Fill in the tabs —
   **Account, Profile, Search, Filters, Run settings** — and click **Save**.
5. Go to the **Run** tab and click **Start**. A Chrome window opens and begins applying —
   keep it in the foreground. You can watch progress in the log and click **Stop** any time.

Your settings are saved locally in `user_config.json`. If you prefer the classic setup,
editing `config/*.py` by hand still works exactly as before — see


> **Tip for your first run:** set `stop_before_submit = True` in `config/settings.py` to have
> the tool fill in every application and stop at the Review step without submitting, so you
> can see what it would say before you trust it.
> [More on dry runs](docs/config-settings.md#dry-runs-stop_before_submit).

## 📚 Documentation

- **LinkedIn**: https://www.linkedin.com/in/alvinjohnmathew03/
- **Instagram**: https://www.instagram.com/alv_x.n
- **Email**: alvinjohnmathew6@gmail.com

If this tool helped you, please share it with your peers
It is built by one independent
developer.

## 📜 Disclaimer

**This tool runs on your own computer and acts through your own accounts. It is provided
free and open source, with no warranty of any kind. You are responsible for how you use it,
including making sure your use complies with the terms of any website or service you use it
with.** 

