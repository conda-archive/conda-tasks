# conda-tasks

> **This project has been merged into
> [conda-workspaces](https://github.com/conda-incubator/conda-workspaces)
> and is no longer maintained.**
>
> All task runner functionality is now available via `conda task` in
> conda-workspaces. Install it with:
>
> ```bash
> conda install -c conda-forge conda-workspaces
> ```

---

conda-tasks was a conda plugin that brought pixi-style task running to
conda. It supported task dependencies, Jinja2 templates, output caching,
per-platform overrides, and multiple manifest formats.

The task system has been integrated into conda-workspaces as the
`conda task` subcommand, combining workspace management and task
execution in a single plugin.

## License

BSD 3-Clause. See [LICENSE](LICENSE).
