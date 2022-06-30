```bash
git clone git@github.com:brillout/vite-3-babel-bug
git checkout vite-2
cd vite-3-babel-bug/
pnpm install
pnpm run preview
```

Same as single line (copy-paste me):

```shell
git clone git@github.com:brillout/vite-3-babel-bug && cd vite-3-babel-bug/ && git checkout vite-2 && pnpm install && pnpm run preview
```

Go to [localhost:3000](http://localhost:3000) and observe that the app works and doesn't throw any error.

Also observe that the only difference is using Vite 2, see [commit `8aafd`](https://github.com/brillout/vite-3-babel-bug/commit/8aafd39404909be6e2b0047ff6b69d71525572d8).
