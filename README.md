# prezto-oc

[OpenShift
CLI](https://docs.openshift.com/container-platform/4.5/cli_reference/openshift_cli/getting-started-cli.html)
module for the [Prezto](https://github.com/sorin-ionescu/prezto) Zsh
configuration framework.

## Installation

1. Set the module directory using `:prezto:load:pmodule-dirs` setting in `~/.zpreztorc`:
    ```
    zstyle ':prezto:load' pmodule-dirs $HOME/.zprezto-contrib
    ```

2. Clone this repository:
    ```
    git clone https://github.com/prezto-contributions/prezto-oc.git ~/.zprezto-contrib/oc
    ```

3. Add the module to the Prezto modules to load in your `~/.zpreztorc`:
    ```
    zstyle ':prezto:load' pmodule \
      oc
    ```

## Aliases

- `oca` is an alias for `oc apply`
- `ocA` is an alias for `oc attach`
- `ocaf` is an alias for `oc apply -f`
- `ocaF` is an alias for `oc apply -R -f`
- `ocC` is an alias for `oc config`
- `occ` is an alias for `oc create`
- `ocD` is an alias for `oc delete`
- `ocd` is an alias for `oc describe`
- `oce` is an alias for `oc edit`
- `ocg` is an alias for `oc get`
- `ocl` is an alias for `oc logs`
- `ocp` is an alias for `oc port-forward`
- `ocP` is an alias for `oc proxy`
- `ocr` is an alias for `oc run`
- `ocx` is an alias for `oc exec`
- `ocX` is an alias for `oc expose`
