# Seedwork 0.7.0

Seedwork v0.7.0

An AI-assisted 3D world-building kit by Adam S. Barnett.

Seedwork helps you create game worlds without starting from scratch. It includes a terrain editor, model-building tools, reusable assets, weather and seasons, a playable preview, and project saving and export.

The package contains the source code, supporting libraries, assets, examples, tests, and instructions. Use it yourself or work with an AI assistant.

Why use it?

Seedwork gives the AI a working foundation and reusable tools instead of rebuilding an engine for every project. You can focus on your setting and gameplay, then improve the world through small, tested changes.

Use with ChatGPT

Upload the ZIP to a conversation that supports project files, then send:

Read START_HERE_CHATGPT.md and AGENTS.md in the attached package. Help me build a game using Seedwork's existing tools. My idea is: describe the setting, camera, and what the player does. Start with a small playable version and return the updated project with instructions. Preserve existing features and clearly identify anything you could not test.

Uploading the ZIP does not install a plug-in or connect the assistant to your computer. If it cannot open the archive, extract it locally and provide the instructions and relevant files.

Run locally

Install Node.js 22 or newer and use a desktop browser with WebGL support. Extract the package, open a terminal inside the seedwork folder, and run:

node server.mjs

Open the local address printed in the terminal. Keep the terminal running while using the editor.

No npm installation, Python, account, or paid API is required for the bundled tools. Node.js and the browser are installed separately.

Build and improve

Generate terrain, place objects, create models, and choose environmental conditions. Use Play world to explore and Save world + assets to preserve a portable project.

Ask the assistant for specific changes, then inspect and test each version. Your game's objectives, enemies, and other rules still need implementation.

Do not share the .seedwork folder; it contains local credentials and user data.

Current scope

This version uses Three.js r140 and procedural artwork. It includes basic water, not the separate advanced coastal-water integration. It does not contain an AI model or automatically produce a finished game.

Commercial use and credit

For new Seedwork-specific work in this release to which Adam S. Barnett controls the applicable rights, permission is granted to anyone, free of charge, to use, copy, modify, merge, publish, distribute, sublicense and sell that work, including in commercial products, with no royalty or Seedwork usage fee. It is provided as-is, without warranty. Project credit is appreciated, not a new mandatory credit requirement.

Earlier Seedwork contributions and Three.js retain their existing notices. Preserve required notices. Credits are recorded in THIRD_PARTY.md and ATTRIBUTION.json. Assets and plug-ins added later retain their own terms.
Run `node scripts/test.mjs` and `node seedwork.mjs verify`. To produce another source ZIP after reviewed edits, run `node scripts/release.mjs`. GitHub workflows test the package and create a **draft** release only through an explicit workflow dispatch. No repository has been created or published by this ZIP. See [docs/GITHUB_RELEASE.md](docs/GITHUB_RELEASE.md), [CHANGELOG.md](CHANGELOG.md), [SECURITY.md](SECURITY.md), and [ATTRIBUTION.json](ATTRIBUTION.json).
