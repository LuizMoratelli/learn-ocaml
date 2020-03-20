# Learn OCaml

## Install

```shell
yarn global add esy pesy

# setup
esy

# build
esy dune build --watch

# run
esy x ReasonNativeBoilerplateApp.exe
// or
esy '{#self.target_dir}/default/executable/ReasonNativeBoilerplateApp.exe'
//or
esy x dune exec ReasonNativeBoilerplateApp.exe
```
