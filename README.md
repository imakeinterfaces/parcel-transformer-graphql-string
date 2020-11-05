# Installation

```bash
yarn add parcel-transformer-graphql-string
```

# Usage

This is just a copy of @parcel/transformer-graphql string loader which is currently broken in the nightly parcel2 builds.
In `.parcelrc`:

```
{
  "transformers": {
   ...
    "*.{gql,graphql}": ["parcel-transformer-graphql-string"],
  }
}
```
