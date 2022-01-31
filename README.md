<div align="center">
	<span style="font-weight: bold"> English | <a href=README_CN.md> 中文 </a> </span>
</div>

## SGSI-build-action

Don't build directly in this warehouse, please fork this warehouse first, and then go to your own warehouse to build!

## Instructions:
```

1. Fork this warehouse
2. Edit Config.env:
     ROM_URL: link for your download
     ZIP_NAME: The name of the package downloaded for you
     OS_TYPE: The type of rom you want to run
     BUILD_TYPE: The type you need to build (ab|a)
     REPACK_NAME: The name of the package you need to pack
3. After modification, click Start commit -> Actions tab -> Star -> SGSI-Build
```

 
## Output result
Download the results in [Release](../../releases)
Files larger than 2G will be automatically uploaded using sub-volume compression
If the upload result is sub-volume compression, download all sub-volumes and merge them with the following command:
```

cat upload/*> SGSI.zip‌‌
```

## Links
Android R Version: [Action-SGSI-build](https://github.com/XayahSuSuSu/Action-SGSI-build)
