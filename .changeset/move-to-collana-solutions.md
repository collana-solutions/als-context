---
"@collana-solutions/als-context": patch
---

The package is now published as `@collana-solutions/als-context`. The API is unchanged, and the new name starts at 3.2.0 with the same code as the last `@neolution-ch/als-context` release. To migrate, replace the old package with the new one:

```shell
npm uninstall @neolution-ch/als-context
npm install @collana-solutions/als-context
```

Then change every `import` and `require` of `@neolution-ch/als-context` to `@collana-solutions/als-context`, including the webpack `IgnorePlugin` pattern if you use one:

```js
config.plugins.push(new IgnorePlugin(/^(@collana-solutions\/als-context)$/));
```

`@neolution-ch/als-context` gets deprecated and receives no further releases.
