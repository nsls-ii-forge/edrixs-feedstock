About edrixs
============

Home: https://github.com/NSLS-II/edrixs

Package license: BSD-3-Clause

Feedstock license: [BSD-3-Clause](https://github.com/nsls-ii-forge/edrixs-feedstock/blob/master/LICENSE.txt)

Summary: An open source toolkit for simulating RIXS spectra based on ED

Current build status
====================


<table>
    
  <tr>
    <td>Azure</td>
    <td>
      <details>
        <summary>
          <a href="https://dev.azure.com/nsls2forge/nsls2forge/_build/latest?definitionId=172&branchName=master">
            <img src="https://dev.azure.com/nsls2forge/nsls2forge/_apis/build/status/edrixs-feedstock?branchName=master">
          </a>
        </summary>
        <table>
          <thead><tr><th>Variant</th><th>Status</th></tr></thead>
          <tbody><tr>
              <td>linux_64_python3.7</td>
              <td>
                <a href="https://dev.azure.com/nsls2forge/nsls2forge/_build/latest?definitionId=172&branchName=master">
                  <img src="https://dev.azure.com/nsls2forge/nsls2forge/_apis/build/status/edrixs-feedstock?branchName=master&jobName=linux&configuration=linux_64_python3.7" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_64_python3.8</td>
              <td>
                <a href="https://dev.azure.com/nsls2forge/nsls2forge/_build/latest?definitionId=172&branchName=master">
                  <img src="https://dev.azure.com/nsls2forge/nsls2forge/_apis/build/status/edrixs-feedstock?branchName=master&jobName=linux&configuration=linux_64_python3.8" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_64_python3.9</td>
              <td>
                <a href="https://dev.azure.com/nsls2forge/nsls2forge/_build/latest?definitionId=172&branchName=master">
                  <img src="https://dev.azure.com/nsls2forge/nsls2forge/_apis/build/status/edrixs-feedstock?branchName=master&jobName=linux&configuration=linux_64_python3.9" alt="variant">
                </a>
              </td>
            </tr>
          </tbody>
        </table>
      </details>
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-edrixs-green.svg)](https://anaconda.org/nsls2forge/edrixs) | [![Conda Downloads](https://img.shields.io/conda/dn/nsls2forge/edrixs.svg)](https://anaconda.org/nsls2forge/edrixs) | [![Conda Version](https://img.shields.io/conda/vn/nsls2forge/edrixs.svg)](https://anaconda.org/nsls2forge/edrixs) | [![Conda Platforms](https://img.shields.io/conda/pn/nsls2forge/edrixs.svg)](https://anaconda.org/nsls2forge/edrixs) |

Installing edrixs
=================

Installing `edrixs` from the `nsls2forge` channel can be achieved by adding `nsls2forge` to your channels with:

```
conda config --add channels nsls2forge
```

Once the `nsls2forge` channel has been enabled, `edrixs` can be installed with:

```
conda install edrixs
```

It is possible to list all of the versions of `edrixs` available on your platform with:

```
conda search edrixs --channel nsls2forge
```




Updating edrixs-feedstock
=========================

If you would like to improve the edrixs recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`nsls2forge` channel, whereupon the built conda packages will be available for
everybody to install and use from the `nsls2forge` channel.
Note that all branches in the nsls-ii-forge/edrixs-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================


