### This is Go(Golang) SDK for Aliyun OSS ###
---

## How to Install ##
* `go get github.com/gogap/Aliyun-OSS-Go-SDK/oss`

---

## SDK Version ##
* <strong>Ver. 4.3 (Released on 150911)</strong>

---

## Golang Version ##
* <strong>Golang 1.4</strong>

---

## OSS API ##
* <strong>Date: 2015.07.10</strong>

---

## Godoc ##
* <http://godoc.org/github.com/gogap/Aliyun-OSS-Go-SDK/oss>

---

## SDK History ##

### Ver. 4.3 (20150911) ###
* <strong>Change STSSecurityToken's request to AssumeRole;
* Consummate the signature's function to fix some bugs;
* Update files and test's files.(by zhaokai&rainsight)</strong>

### Ver. 4.2 (20150826) ###
* Consummate STSSecurityToken to support multiple statements;
* Consummate the signature's function to fix some bugs.(by zhaokai&rainsight)

### Ver. 4.1 (20150722) ###
* Handle GetSecurityToken's error.(by zhaokai&rainsight)

### Ver. 4.0 (20150717) ###
* Add all new consts(OSSHeader&STS);
* Add UserProperty, SecurityToken, TempPrefix, TempDelimiter into tpyes.Client of Ver. 3.5;
* Change common.DoRequest&model.bucket.BucketList to adapt all new STSTempClient's requests;
* Add GetSecurityToken&SetSTSCondition of Ver. 3.5;
* Add AppendObject of Ver. 3.5;
* Add InitiateTempClient of Ver. 3.5;
* New functions' examples can be found in oss_test.go;
* Realize all methods of official OSS-API(20150710).

### Ver. 3.5 (20150623) ###
* Rename variables to easily understand(cutLength, startPoint, endPoint to chunkSize, start, end).(by topikachu)

### Ver. 3.4 (20150528) ###
* Add Chinese annotations of Ver. 3.3;
* Add some errors' returns of Ver. 3.3;
* Add new endpoint(USWest1);
* Delete PutObjectWeb&UploadPartWeb of Ver. 3.2;
* Add CleanBucket of Ver. 3.3.

### Ver. 3.3 (20150517) ###
* Change web service(PostObject) of Ver. 3.2.

### Ver. 3.2 (20150515) ###
* Add web service(PutObjectWeb&UploadPartWeb) of Ver. 3.1.

### Ver. 3.1 (20150424) ###
* Delete remaining Println of Ver. 3.0.

### Ver. 3.0 (20150424) ###
* Delete many Println of Ver. 2.3.

### Ver. 2.3 (20150421) ###
* Fix func BucketReferer&GetService of Ver. 2.2.

### Ver. 2.2 (20150420) ###
* Delete some println of Ver. 2.1.

### Ver. 2.1 (20150413) ###
* Small changes of Ver. 2.0.

### Ver. 2.0 (20150402)
* Package Go files of Ver. 1.1;  
* Add package common, consts, model, types;  
* Add file oss_convert.go;  
* Simplify some functions of package oss.

### Ver. 1.1 (20150331) ###
* Small changes of Ver. 1.0;  
* Rewrite the readme.md.

### Ver. 1.0 (20150330) ###
* Original version;
* Realize all methods of official OSS-API(20150319).

---

## OSS Documents ##
* <http://docs.aliyun.com/#/oss>  
