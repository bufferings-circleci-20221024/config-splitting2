# demo05-monorepo1

A more realistic config split than the [demo03-concat-configs](https://github.com/bufferings-circleci-20221024/demo03-concat-configs)

This doesn't just concat files, but understands YAML files and merge them to make a config. So we can create `config.yml` in each modules.

The target config files to be merged are in the `.circleci/configs.txt`

This demo uses this orb: [config-splitting](https://circleci.com/developer/ja/orbs/orb/circle-makotom-orbs/config-splitting)

The reference project for this demo: [circle-select-split-config](https://github.com/circle-makotom/circle-select-split-config)
 
