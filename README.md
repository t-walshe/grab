<div align="center">
    <a href="https://github.com/t-walshe/grab/blob/main/LICENSE"><img src="https://img.shields.io/github/license/t-walshe/grab" alt="License"></a>
    <a href="https://walshe.tech/"><img src="https://img.shields.io/badge/website-walshe.tech-blue" alt="Website"></a>
    <a href="https://github.com/t-walshe/grab/releases"><img alt="GitHub release" src="https://img.shields.io/github/release/t-walshe/grab"></a>   
</div>

<h3 align="center">
  <div style="display:flex;flex-direction:row;">
    <img src="https://github.com/t-walshe/grab/blob/main/assets/logo.png" alt="grab logo" width=100px>
    <p>grab - AI-Powered Email Management</p>
  </div>
</h3>

`grab` your emails and use AI agents to automatically organize, analyze, and action! The library offers:

📧 **Email integrations**: currently Gmail is supported, with more services planned.

🌐 **Model-agnostic**: grab supports OpenAI models, and will in future support local or API-based models through an [LiteLLM](https://www.litellm.ai/) integration.

🔒 **On-device storage**: Built-in support for [SQLite](https://www.sqlite.org/) keeps your data local.

📙 **Export compatibility**: Take your insights forward with [Obsidian](https://obsidian.md/).

> [!NOTE]
> We'll soon have a [launch blog post](https://walshe.tech/) to learn more about `grab`!

## Installation guide
1. **Installing UV**: Our python package and project manager of choice is [UV](https://docs.astral.sh/uv/), it should be installed to your global environment using:

```bash
python3 -m pip install uv
```

2. **Clone repo**: Clone locally using:

```bash
git clone https://github.com/t-walshe/grab.git
```

3. **Set up environment**: UV can be used to automatically set up a virtual environment in the top-level directory (`grab/`) using:

```bash
uv venv
uv sync
```

4. **Install in editable mode**: For package development, you can install an editable version using:

```bash
uv pip install --pip-reinstall --no-deps -e .
```




