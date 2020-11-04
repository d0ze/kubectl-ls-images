# kubectl-ls-images

_Simple script to list images running in a k8s cluster_

## Installation

- clone this repository and run ``cp cmd/kubectl-ls-images /usr/local/bin
``

## Usage
    ```
    kubectl ls images {...kubectl args}
    Output:
         - {number of tag 's running copies}  {tag}
         - ...
    ```