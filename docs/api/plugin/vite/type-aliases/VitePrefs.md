# VitePrefs

```ts
type VitePrefs: Prefs & Object;
```

Configures vite plugin behaviour.

## Type declaration

### inject?

```ts
inject?: boolean;
```

Whether to inject imgit client JavaScript module to index HTML; enabled by default.

### skip?

```ts
skip?: (filename) => boolean;
```

Specify condition when document shouldn't be transformed by the vite plugin.

#### Parameters

• **filename**: `string`

#### Returns

`boolean`

## Source

[plugin/vite.ts:4](https://github.com/Elringus/Imgit/blob/157689c/src/plugin/vite.ts#L4)
