# Container images for toolbx

Container images to use with [toolbx](https://containertoolbx.org/)
([GitHub](https://github.com/containers/toolbox)).

## Available distributions and usage

- Fedora: See the official images (default in toolbx)

- CentOS (Stream):
  - c9s: `stream9`
  ```
  $ toolbox create --image quay.io/toolbx-images/centos-toolbox:stream9
  $ toolbox enter centos-toolbox-stream9
  ```

- Ubuntu:
  - `22.04`
  ```
  $ toolbox create --image quay.io/toolbx-images/ubuntu-toolbox:22.04
  $ toolbox enter ubuntu-toolbox-22.04
  ```
