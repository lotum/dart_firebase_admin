# Flutter setup action

Vendored from [subosito/flutter-action@v2.7.1](https://github.com/subosito/flutter-action/tree/1e6ee87cb840500837bcd50a667fb28815d8e310) at commit `1e6ee87cb840500837bcd50a667fb28815d8e310`.

`LICENSE` is unchanged. `setup.sh` preserves the upstream setup logic and writes its five outputs to `GITHUB_OUTPUT` instead of the deprecated `::set-output` command. The action metadata retains upstream inputs, outputs and setup steps; its cache dependency uses the maintained `actions/cache@v5` pinned to `caa296126883cff596d87d8935842f9db880ef25` so the entire action satisfies Lotum's SHA-pinning policy.

To update, copy `action.yml`, `setup.sh` and `LICENSE` from a reviewed upstream commit, retain this provenance record, and pin every nested `uses:` entry before committing.
