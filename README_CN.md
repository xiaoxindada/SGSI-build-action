<div align="center">
	<span style="font-weight: bold"> 中文 | <a href=README.md> English </a> </span>
</div>

# SGSI-build-action

**不要直接在此仓库跑包，跑包请fork此仓库到然后去你自己的GitHub里再跑 ！**  
**Don't build directly in this warehouse, please fork this warehouse first, and then go to your own warehouse to build!**

## 使用方法:
```
1. fork此仓库
2. 编辑config.env:
     ROM_URL: 为你的下载连接 
     ZIP_NAME: 为你下载的包名 
     OS_TYPE: 为你要跑的rom类型  
     BUILD_TYPE: 为你需要build的类型(ab|a) 
     REPACK_NAME: 为你需要打包的包名
3. 修改完毕后依次点击Start commit -> Actions选项卡 -> Star -> SGSI-Build
```
 
## 输出结果
结果在[Release](../../releases)下载  
大于2G的文件将自动采用分卷压缩上传  
如果上传结果为分卷压缩，下载所有分区卷，并使用以下命令进行合并:
```
cat upload/* > SGSI.zip
```

## 友情链接
Android R版:[Action-SGSI-build](https://github.com/XayahSuSuSu/Action-SGSI-build)
