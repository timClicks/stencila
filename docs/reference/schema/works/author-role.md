# Author Role

**An author and their role.**

**`@id`**: `stencila:AuthorRole`

## Properties

The `AuthorRole` type has these properties:

| Name           | Aliases                          | `@id`                                            | Type                                                                                                                   | Description                                                                | Inherited from                                                                                   |
| -------------- | -------------------------------- | ------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------ |
| `id`           | -                                | [`schema:id`](https://schema.org/id)             | [`String`](https://github.com/stencila/stencila/blob/main/docs/reference/schema/data/string.md)                        | The identifier for this item.                                              | [`Entity`](https://github.com/stencila/stencila/blob/main/docs/reference/schema/other/entity.md) |
| `author`       | -                                | [`schema:author`](https://schema.org/author)     | [`AuthorRoleAuthor`](https://github.com/stencila/stencila/blob/main/docs/reference/schema/works/author-role-author.md) | The entity acting as an author.                                            | -                                                                                                |
| `roleName`     | `role-name`, `role_name`         | [`schema:roleName`](https://schema.org/roleName) | [`AuthorRoleName`](https://github.com/stencila/stencila/blob/main/docs/reference/schema/works/author-role-name.md)     | The role played by the author.                                             | -                                                                                                |
| `format`       | -                                | `stencila:format`                                | [`String`](https://github.com/stencila/stencila/blob/main/docs/reference/schema/data/string.md)                        | The format that the author used to perform the role. e.g. Markdown, Python | -                                                                                                |
| `lastModified` | `last-modified`, `last_modified` | `stencila:lastModified`                          | [`Timestamp`](https://github.com/stencila/stencila/blob/main/docs/reference/schema/data/timestamp.md)                  | Timestamp of most recent modification, by the author, in the role.         | -                                                                                                |

## Related

The `AuthorRole` type is related to these types:

- Parents: [`Role`](https://github.com/stencila/stencila/blob/main/docs/reference/schema/other/role.md)
- Children: none

## Formats

The `AuthorRole` type can be encoded (serialized) to, and/or decoded (deserialized) from, these formats:

| Format                                                                                               | Encoding     | Decoding   | Status              | Notes |
| ---------------------------------------------------------------------------------------------------- | ------------ | ---------- | ------------------- | ----- |
| [DOM HTML](https://github.com/stencila/stencila/blob/main/docs/reference/formats/dom.html.md)        | 🟢 No loss    |            | 🔶 Beta              |       |
| [HTML](https://github.com/stencila/stencila/blob/main/docs/reference/formats/html.md)                | 🔷 Low loss   |            | 🚧 Under development |       |
| [JATS](https://github.com/stencila/stencila/blob/main/docs/reference/formats/jats.md)                |              |            | 🚧 Under development |       |
| [Markdown](https://github.com/stencila/stencila/blob/main/docs/reference/formats/md.md)              | ⚠️ High loss |            | 🔶 Beta              |       |
| [Stencila Markdown](https://github.com/stencila/stencila/blob/main/docs/reference/formats/smd.md)    | ⚠️ High loss |            | 🔶 Beta              |       |
| [Quarto Markdown](https://github.com/stencila/stencila/blob/main/docs/reference/formats/qmd.md)      | ⚠️ High loss |            | 🔶 Beta              |       |
| [MyST Markdown](https://github.com/stencila/stencila/blob/main/docs/reference/formats/myst.md)       | ⚠️ High loss |            | 🔶 Beta              |       |
| [LLM Markdown](https://github.com/stencila/stencila/blob/main/docs/reference/formats/llmd.md)        | ⚠️ High loss |            | 🔶 Beta              |       |
| [LaTeX](https://github.com/stencila/stencila/blob/main/docs/reference/formats/latex.md)              | 🔷 Low loss   | 🔷 Low loss | 🚧 Under development |       |
| [PDF](https://github.com/stencila/stencila/blob/main/docs/reference/formats/pdf.md)                  | 🔷 Low loss   |            | 🚧 Under development |       |
| [Plain text](https://github.com/stencila/stencila/blob/main/docs/reference/formats/text.md)          | ⚠️ High loss |            | 🔶 Beta              |       |
| [IPYNB](https://github.com/stencila/stencila/blob/main/docs/reference/formats/ipynb.md)              | 🔷 Low loss   | 🔷 Low loss | 🚧 Under development |       |
| [Microsoft Word DOCX](https://github.com/stencila/stencila/blob/main/docs/reference/formats/docx.md) | 🔷 Low loss   | 🔷 Low loss | 🚧 Under development |       |
| [OpenDocument ODT](https://github.com/stencila/stencila/blob/main/docs/reference/formats/odt.md)     | 🔷 Low loss   | 🔷 Low loss | 🚧 Under development |       |
| [JSON](https://github.com/stencila/stencila/blob/main/docs/reference/formats/json.md)                | 🟢 No loss    | 🟢 No loss  | 🟢 Stable            |       |
| [JSON+Zip](https://github.com/stencila/stencila/blob/main/docs/reference/formats/json.zip.md)        | 🟢 No loss    | 🟢 No loss  | 🟢 Stable            |       |
| [JSON5](https://github.com/stencila/stencila/blob/main/docs/reference/formats/json5.md)              | 🟢 No loss    | 🟢 No loss  | 🟢 Stable            |       |
| [JSON-LD](https://github.com/stencila/stencila/blob/main/docs/reference/formats/jsonld.md)           | 🟢 No loss    | 🟢 No loss  | 🔶 Beta              |       |
| [CBOR](https://github.com/stencila/stencila/blob/main/docs/reference/formats/cbor.md)                | 🟢 No loss    | 🟢 No loss  | 🟢 Stable            |       |
| [CBOR+Zstandard](https://github.com/stencila/stencila/blob/main/docs/reference/formats/cbor.zstd.md) | 🟢 No loss    | 🟢 No loss  | 🟢 Stable            |       |
| [YAML](https://github.com/stencila/stencila/blob/main/docs/reference/formats/yaml.md)                | 🟢 No loss    | 🟢 No loss  | 🟢 Stable            |       |
| [Lexical JSON](https://github.com/stencila/stencila/blob/main/docs/reference/formats/lexical.md)     | 🔷 Low loss   | 🔷 Low loss | ⚠️ Alpha            |       |
| [Koenig JSON](https://github.com/stencila/stencila/blob/main/docs/reference/formats/koenig.md)       | 🔷 Low loss   | 🔷 Low loss | ⚠️ Alpha            |       |
| [Pandoc AST](https://github.com/stencila/stencila/blob/main/docs/reference/formats/pandoc.md)        | 🔷 Low loss   | 🔷 Low loss | 🚧 Under development |       |
| [Directory](https://github.com/stencila/stencila/blob/main/docs/reference/formats/directory.md)      |              |            | 🚧 Under development |       |
| [Stencila Web Bundle](https://github.com/stencila/stencila/blob/main/docs/reference/formats/swb.md)  |              |            | ⚠️ Alpha            |       |
| [Debug](https://github.com/stencila/stencila/blob/main/docs/reference/formats/debug.md)              | 🔷 Low loss   |            | 🟢 Stable            |       |

## Bindings

The `AuthorRole` type is represented in these bindings:

- [JSON-LD](https://stencila.org/AuthorRole.jsonld)
- [JSON Schema](https://stencila.org/AuthorRole.schema.json)
- Python class [`AuthorRole`](https://github.com/stencila/stencila/blob/main/python/python/stencila/types/author_role.py)
- Rust struct [`AuthorRole`](https://github.com/stencila/stencila/blob/main/rust/schema/src/types/author_role.rs)
- TypeScript class [`AuthorRole`](https://github.com/stencila/stencila/blob/main/ts/src/types/AuthorRole.ts)

## Source

This documentation was generated from [`AuthorRole.yaml`](https://github.com/stencila/stencila/blob/main/schema/AuthorRole.yaml) by [`docs_type.rs`](https://github.com/stencila/stencila/blob/main/rust/schema-gen/src/docs_type.rs).
