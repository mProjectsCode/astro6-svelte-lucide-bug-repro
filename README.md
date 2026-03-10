When running the dev server, everything works fine.

When running the build, observe the error below:

```
12:03:51   ├─ /index.html12:03:51 [ERROR] Error [ERR_MODULE_NOT_FOUND]: Cannot find module '/.../src/astro-6-lucide-repro/node_modules/lucide-svelte/dist/icons/index' imported from /.../src/astro-6-lucide-repro/node_modules/lucide-svelte/dist/lucide-svelte.js
    at finalizeResolution (node:internal/modules/esm/resolve:274:11)
    at moduleResolve (node:internal/modules/esm/resolve:864:10)
    at defaultResolve (node:internal/modules/esm/resolve:990:11)
    at #cachedDefaultResolve (node:internal/modules/esm/loader:749:20)
    at ModuleLoader.resolve (node:internal/modules/esm/loader:726:38)
    at ModuleLoader.getModuleJobForImport (node:internal/modules/esm/loader:312:38)
    at #link (node:internal/modules/esm/module_job:208:49)
12:03:51 [ERROR] [build] Caught error rendering /: Error [ERR_MODULE_NOT_FOUND]: Cannot find module '/.../src/astro-6-lucide-repro/node_modules/lucide-svelte/dist/icons/index' imported from /.../src/astro-6-lucide-repro/node_modules/lucide-svelte/dist/lucide-svelte.js
Cannot find module '/.../src/astro-6-lucide-repro/node_modules/lucide-svelte/dist/icons/index' imported from /.../src/astro-6-lucide-repro/node_modules/lucide-svelte/dist/lucide-svelte.js
  Stack trace:
    at finalizeResolution (node:internal/modules/esm/resolve:274:11)
    at defaultResolve (node:internal/modules/esm/resolve:990:11)
    at ModuleLoader.resolve (node:internal/modules/esm/loader:726:38)
    at #link (node:internal/modules/esm/module_job:208:49)
```
