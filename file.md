# 文件
## 说明
```azure
文件上传的流程
前端先获取阿里云oss临时的token，调用下面接口
https://shineapi.xiaoyuanchao.xyz/doc.html#/v1/%E6%96%87%E4%BB%B6/sts
然后上传文件到阿里云oss，然后调用下面接口提交oss文件信息，接口会返回文件的ID
https://shineapi.xiaoyuanchao.xyz/doc.html#/v1/%E6%96%87%E4%BB%B6/submitOssFile
文件的ID在其他接口中会用到
阿里云文档
https://help.aliyun.com/document_detail/32077.html
https://help.aliyun.com/document_detail/111268.html
```

## 文件列表
```azure
https://shineapi.xiaoyuanchao.xyz/doc.html#/v1/%E6%96%87%E4%BB%B6/filePage
```

## 删除文件
```azure
https://shineapi.xiaoyuanchao.xyz/doc.html#/v1/%E6%96%87%E4%BB%B6/delFile
```

## 更新文件信息
```azure
https://shineapi.xiaoyuanchao.xyz/doc.html#/v1/%E6%96%87%E4%BB%B6/updateFileInfo
```
