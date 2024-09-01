# Schemas

A collection of schema files for data interchange within the organization.

| Id                         | Description                                                                                         | Status       | Versions                                                                                                                                                 | Comment                           |
| -------------------------- | --------------------------------------------------------------------------------------------------- | ------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------- |
| common.jexpr               | The JSON Expression macro language                                                                  | STABLE       | [v1](https://schemas.cute.engineering/stable/common.jexpr.v1) [latest](https://schemas.cute.engineering/latest/common.jexpr)                             |                                   |
| common.uti                 | A representation of a Uniform Type Identifier repository                                            | DEV          | [v1](https://schemas.cute.engineering/stable/common.uti.v1) [latest](https://schemas.cute.engineering/latest/common.uti)                                 |                                   |
| booboot.config             | A representation of a configuration file for [booboot](https://github.com/cute-engineering/booboot) | DEV          | [v1](https://schemas.cute.engineering/stable/booboot.config.v1) [latest](https://schemas.cute.engineering/latest/booboot.config)                         |                                   |
| osdk.manifest.component    | A representation of a component manifest for OSDK                                                   | ⚠️ DEPRECATED | [v1](https://schemas.cute.engineering/stable/osdk.manifest.component.v1) [latest](https://schemas.cute.engineering/latest/osdk.manifest.component)       | Use cutekit based schemas instead |
| osdk.manifest.target       | A representation of a target manifest for OSDK                                                      | ⚠️ DEPRECATED | [v1](https://schemas.cute.engineering/stable/osdk.manifest.target.v1) [latest](https://schemas.cute.engineering/latest/osdk.manifest.target)             | Use cutekit based schemas instead |
| osdk.manifest.project      | A representation of a project manifest for OSDK                                                     | ⚠️ DEPRECATED | [v1](https://schemas.cute.engineering/stable/osdk.manifest.project.v1) [latest](https://schemas.cute.engineering/latest/osdk.manifest.project)           | Use cutekit based schemas instead |
| cutekit.manifest.component | A representation of a component manifest for [cutekit](https://github.com/cute-engineering/cutekit) | STABLE       | [v1](https://schemas.cute.engineering/stable/cutekit.manifest.component.v1) [latest](https://schemas.cute.engineering/latest/cutekit.manifest.component) |                                   |
| cutekit.manifest.target    | A representation of a target manifest for [cutekit](https://github.com/cute-engineering/cutekit)    | STABLE       | [v1](https://schemas.cute.engineering/stable/cutekit.manifest.target.v1) [latest](https://schemas.cute.engineering/latest/cutekit.manifest.target)       |                                   |
| cutekit.manifest.project   | A representation of a project manifest for [cutekit](https://github.com/cute-engineering/cutekit)   | STABLE       | [v1](https://schemas.cute.engineering/stable/cutekit.manifest.project.v1) [latest](https://schemas.cute.engineering/latest/cutekit.manifest.project)     |                                   |

## Legend

- **id**: The unique identifier of the schema
- **description**: A short description of the schema
- **status**: The status of the schema (stable, wip, deprecated)
- **versions**: The available versions of the schema
- **comment**: Additional information about the schema

## Status
 - **stable**: The schema is stable and will not change in a breaking way.
 - **wip**: The schema is work in progress and may change in a breaking way.
 - **deprecated**: The schema is deprecated and should not be used anymore.

