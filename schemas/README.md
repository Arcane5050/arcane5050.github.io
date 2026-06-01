## How to use schemas
Using schemas is simple!
At the top of your JSON file, add `"$schema": "https://example.com"`, so your JSON file should now look like:
```json
{
    "$schema": "https://example.com",
    ...
}
```
Schemas provide autocompletion, and basic error highlighting.
## Reloading schemas
When a schema is updated, your Code Editor may not automatically reload the schema.
### VSCode
In your VSCode settings, go to "Extensions > JSON" and disable and re-enable "Schema Download". This should reload all of your schemas.
## All of my schemas
[terrain_texture.json](https://arcane5050.github.io/schemas/terrain_texture_schema.json)
[Recipe Schema](https://arcane5050.github.io/schemas/recipe_schema.json)