# sentinel5p_view
sentinel-5p 読む用のスクリプト

## 対象データ　
sentinel 5p high resolution 


## 環境構築
### miniconda で仮想環境を作成します。 
```
conda create -n s5p xarray netcdf4 matplotlib cartopy gdal
```
これで完了

###　実行
conda activate s5p 

### sデータ容量が大きいので、gdal で必要な領域を切り出し

### 
