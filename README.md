# coderabbit

Central [CodeRabbit](https://coderabbit.ai) configuration for the
skillsgateway organization
([central configuration](https://docs.coderabbit.ai/configuration/central-configuration)).

`.coderabbit.yaml` at the root of this repository applies to every repository
in the organization that has no `.coderabbit.yaml` of its own.

A repository that needs its own rules (path filters, path instructions,
guideline files) adds a small `.coderabbit.yaml` with `inheritance: true` and
only those settings. Scalars there win, objects merge key by key, lists
combine, and `path_instructions` match by path
([inheritance and merging](https://docs.coderabbit.ai/configuration/inheritance-and-merging)).

A change here changes code review for every repository in the organization.
