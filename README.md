

## Requirements

- tensorflow-gpu (or tensorflow)
- keras
- nupmy
- scikit-image
- argparse
- imageio
- matplotlib (optional)
- GDAL >= 2.2 (optional)


## Using the Network

```
 python s2_tiles_supres.py /path/to/S2A_MSIL1C_20161230T074322_N0204_R092_T37NCE_20161230T075722.SAFE/MTD_MSIL1C.xml /path/to/output_file.tif --roi_x_y "100,100,2000,2000"
```


## Used Sentinel-2 tiles

The Sentinel-2 tiles used for training and testing and fine-tuning are listed in data folder:


They can be downloaded from the [Copernicus Open Access Hub](https://scihub.copernicus.eu/dhus/).

