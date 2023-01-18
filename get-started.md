```bash
aws s3api create-bucket --bucket hpcpack-2019-157673489008 --region ap-southeast-2 \
--create-bucket-configuration LocationConstraint=ap-southeast-2
```

```bash
aws s3api create-bucket --bucket hpcpack-output-2019-157673489008 --region ap-southeast-2 \
--create-bucket-configuration LocationConstraint=ap-southeast-2
```

```bash
aws s3 cp HPCPack.zip s3://hpcpack-2019-157673489008
aws s3 cp ScriptsForComputeNode2019.zip s3://hpcpack-2019-157673489008
aws s3 cp ScriptsForHeadNode2019.zip s3://hpcpack-2019-157673489008
```