# Design System Course

Projects tend to grow over time, and, occasionally, some pieces of a project can be useful elsewhere in other projects. `For example`, Jest, being a generic testing tool, gave birth to many packages, one of them is jest-snapshot that is now used in other projects like snapguidist and chai-jest-snapshot.

**Yarn Workspaces** is a feature that `allows users to install dependencies from multiple package.json` files in subfolders of a single root package.json file, all in one go.

Making Workspaces native to Yarn enables faster, lighter installation by `preventing package duplication` across Workspaces. Yarn can also create `symlinks` between Workspaces that depend on each other, and will ensure the `consistency and correctness` of all directories.

## Monorepos

Those who have `tried splitting a project into multiple packages` know how hard it is to make changes across multiple packages at one time. To make the process easier, some big projects adopted a `monorepo` approach, or multi-package repositories, which reduces the burden of writing code across packages.

Several projects used every day by JavaScript developers are managed as monorepos: Babel, React, Jest, Vue, Angular.

However, separating pieces of projects into their own folders is sometimes not enough. `Testing, managing dependencies, and publishing multiple packages` quickly gets complicated and many such projects adopt tools such as Lerna to make working with monorepos easier.
