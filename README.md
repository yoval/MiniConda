重装MiniConda后使用

`conda install --yes --file requirements.txt`



导出

`conda env export > freeze.yml`

导入

` conda env create -f freeze.yml`