# goeslang-r
Go package for dealing with GOES-R data

I'm going to start with the cloud height data, it's cached on S3 for faster/cheaper access.

`aws s3 cp s3://noaa-goes16/ABI-L2-ACHAC/2020/176/22/OR_ABI-L2-ACHAC-M6_G16_s20201762206171_e20201762208543_c20201762210385.nc . --no-sign-request`