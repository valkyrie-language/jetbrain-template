



## Prerequisites

- [Git](): Version control system
- [JetBrains IDEA](): Integrated development environment
- [legion](): Valkyrie project build manager
- [vpm](): Valkyrie package manager


## Project Structure

```yaml
root                 # The mono repo root
  - .github/         # GitHub related config
  - .config/         #
    - .legion/       # legion related config
  - packages/        # The package
    - project1
      - legion.json  # legion package
    - project2
      - package.json # non valkyrie package
  - targets/         # output
  - legions.json     # legion workspace config
```

## Package Structure

```yaml
project1             # The mono repo root
  - .github/         # GitHub related config
  - script/          #
    - main.vk/       # vmp run main
  - library/         # expand macro and ready to release
  - source/          # The package
  - test/
  - legion.json      # legion package config
  - readme.json      # readme for the package
```

