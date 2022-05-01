# GitHub Actions template for QMK Userspace

### Usage guide:
1. Select "Use this template" to create a copy in your GitHub account.
1. Clone the new repository into your local computer with `git` (or your favourite tool).
1. Create a keymap with [QMK Configurator](https://config.qmk.fm/) and use your GitHub account name as the "Keymap Name". This step is important because the workflow uses your GitHub name in the build process.
1. Export the JSON keymap file and save it into the root folder of the repository.
1. Replace `username.json` in [build.yml](.github/workflows/build.yml) with the JSON file name from the previous step.
1. Keymap layout must remain in the JSON format. Custom settings and source codes can be added into `rules.mk`, `config.h` and `source.c` files if required.
1. Use `git` to commit and push your changes to GitHub for the action workflow to build your QMK firmware.

### References
* [QMK Userspace](https://docs.qmk.fm/#/feature_userspace)
* [GitHub Actions guide](https://docs.github.com/en/actions/learn-github-actions)

