# Frontend Helper

Helper library for working on the frontend in my projects.

> [!CAUTION]
>
> ### This is a personal project
>
> Maintenance, bug fixes, new features, and support will only be provided when/if I feel like it.
> Updates may violate semantic versioning.

## Bundling CSS

1. `cargo install --locked --git https://github.com/parcel-bundler/lightningcss.git --features cli`
1. `lightningcss --bundle --minify --output-file .\src\styles\style.min.css .\src\styles\style.css`
