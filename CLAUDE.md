Observe the following rules when contributing to this repository:

* Before committing, run `./maintainers/format.sh` to detect/fix any formatting issues. If you've only touched C++ files, run `run ./maintainers/format.sh clang-format` since it's a lot faster.

* Use "Assisted-by:" instead of "Co-Authored-By:" for the Claude trailer in commits.

* Do not create PRs unless prompted. Create PRs using `gh pr create --repo DeterminateSystems/nix-src --base main`, observing `.github/PULL_REQUEST_TEMPLATE.md`.

* The code base uses C++23, so C++23 features (e.g. deducing-this lambdas) can be used freely.
