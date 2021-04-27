# SGSI-build-action

**不要直接在此仓库跑包，跑包请fork此仓库到然后去你自己的GitHub里再跑 ！**  
**Don't build directly in this warehouse, please fork this warehouse first, and then go to your own warehouse to build!**

## 使用方法:
```
1. fork此仓库
2. 编辑SGSI_Build.yml:
     ROM_URL: 为你的下载连接 
     ZIP_NAME: 为你下载的包名 
     OS_TYPE: 为你要跑的rom类型  
     BUILD_TYPE: 为你需要build的类型(ab|a-only) 
     REPACK_NAME: 为你需要打包的包名
3. 修改完毕后依次点击Start commit -> Actions选项卡 -> Star -> SGSI-Build
```
 
## 输出结果
如果将rom上传至Release下载 请修改yml的 upload_action-gh-release: 'false' -> 'true' 
每次构建成功后山除掉 自动上传的的版本否则下次将会上传失败
结果在[Release](../../releases)下载

如果将rom上传至WeTransfer下载 清修改yml的 upload_WeTransfer: 'false' -> 'true'
上传好后的下载链接，留意输出结果 Download Link:
