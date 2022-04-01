List all files on OpenTopography AWS for this dataset

```aws s3 ls s3://raster/SRTM_GL3/ --recursive --endpoint-url https://opentopography.s3.sdsc.edu --no-sign-request```

Download file:

```aws s3 cp s3://raster/SRTM_GL3/ . --recursive --endpoint-url https://opentopography.s3.sdsc.edu --no-sign-request```
- the bit that starts with s3://raster/ is what we're copying, the . can be changed for where we want the files to be saved to.