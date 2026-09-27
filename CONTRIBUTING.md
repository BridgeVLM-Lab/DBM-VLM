# Contributing to DBM-VLM

Thank you for your interest in contributing to DBM-VLM and the DBM-65k benchmark.

We welcome contributions that improve reproducibility, documentation, configuration quality, benchmark usability, and the BridgeVLM research workflow.

## Ways to Contribute

Useful contributions include:

- fixing documentation errors or broken resource links;
- improving installation, inference, training, or evaluation instructions;
- correcting YAML configuration files;
- adding reproducibility notes or environment information;
- reporting bugs or compatibility issues;
- improving benchmark validation workflows;
- improving BridgeVLM documentation;
- proposing maintenance, testing, or release automation improvements.

## Reporting Issues

Before opening an issue, please check whether a similar issue already exists.

When reporting a problem, please include as much of the following information as possible:

1. the affected task or resource, such as `DBM-Con`, `DBM-Comp`, or `DBM-Conseg`;
2. the relevant configuration file or pretrained checkpoint;
3. your operating system;
4. your Python version;
5. relevant package versions, especially Ultralytics when applicable;
6. exact reproduction steps;
7. the expected behavior;
8. the actual behavior;
9. relevant logs or error messages.

For broken dataset or model links, please include the exact resource name and affected URL.

## Pull Requests

Please keep pull requests focused on a single problem or improvement.

Before submitting a pull request:

1. explain clearly what changed and why;
2. verify that edited YAML files remain valid;
3. update documentation when behavior or configuration changes;
4. avoid unrelated formatting or refactoring changes;
5. do not commit large datasets, pretrained model weights, or generated research artifacts directly to the repository;
6. describe how the change was tested or validated.

Large datasets, pretrained model weights, and other research artifacts are hosted through the public resource links documented in the repository.

## Reproducibility

Changes related to experiments, configurations, or benchmark results should include enough information for maintainers and other researchers to reproduce the behavior.

When relevant, please provide:

- configuration file names;
- checkpoint names;
- package versions;
- command-line arguments;
- evaluation settings;
- dataset subset information.

## Documentation Contributions

Documentation improvements are welcome, including:

- clearer setup instructions;
- corrected commands;
- additional inference or evaluation examples;
- explanations of benchmark subsets;
- compatibility notes;
- improved links between GitHub resources, Kaggle resources, and the accompanying research paper.

## Licensing

By submitting a contribution to this repository, you agree that your contribution may be distributed under the repository's Apache License 2.0, unless explicitly stated otherwise and agreed to by the maintainers.

Do not submit code, datasets, model weights, or other material that you do not have the right to redistribute.

## Review Process

Maintainers may request additional reproduction details, documentation, tests, or revisions before merging a contribution.

Technical correctness, reproducibility, clarity, and compatibility with the existing DBM-VLM / DBM-65k project structure will be considered during review.

## Questions

For project questions, reproducibility problems, or contribution discussions, please open a GitHub Issue so that the discussion remains public and searchable.
