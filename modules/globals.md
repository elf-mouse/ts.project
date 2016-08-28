## globals.d.ts

We discussed _global_ vs. _file_ modules when covering [projects](modules.md) and recommended using file based modules and not polluting the global namespace.

Nevertheless it is convenient to have _some_ files just with type declarations (for smaller projects preferably one called `globals.d.ts`) in the global namespace to make it easy to have some _types_ just _magically_ available for consumption in _all_ your TypeScript code. For any code that is going to generate _JavaScript_ we still recommend using _file modules_.

`globals.d.ts` is great for adding extensions to `lib.d.ts`.
