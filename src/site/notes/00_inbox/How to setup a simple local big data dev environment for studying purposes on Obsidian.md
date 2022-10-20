---
{"dg-publish":true,"dg-permalink":"How to setup a simple local big data dev environment for studying purposes on Obsidian","permalink":"/How to setup a simple local big data dev environment for studying purposes on Obsidian/","dgHomeLink":true,"dgPassFrontmatter":false,"dgShowBacklinks":true,"dgShowLocalGraph":true}
---


<style>
.container {font-family: sans-serif; text-align: center;}
.button-wrapper button {z-index: 1;height: 40px; width: 100px; margin: 10px;padding: 5px;}
.excalidraw .App-menu_top .buttonList { display: flex;}
.excalidraw-wrapper { height: 800px; margin: 50px; position: relative;}
:root[dir="ltr"] .excalidraw .layer-ui__wrapper .zen-mode-transition.App-menu_bottom--transition-left {transform: none;}
</style><script src="https://unpkg.com/react@17/umd/react.production.min.js"></script><script src="https://unpkg.com/react-dom@17/umd/react-dom.production.min.js"></script><script type="text/javascript" src="https://unpkg.com/@excalidraw/excalidraw@0.12.0/dist/excalidraw.production.min.js"></script><div id="Drawing_2022-10-17_1848.17.excalidraw.md1"></div><script>(function(){const InitialData={"type":"excalidraw","version":2,"source":"https://excalidraw.com","elements":[{"id":"gVUvPWvKdHOZoLG3IKkgV","type":"image","x":58.793670997190986,"y":76.91449869791666,"width":179.87886235955062,"height":93.38710937500004,"angle":0,"strokeColor":"transparent","backgroundColor":"transparent","fillStyle":"hachure","strokeWidth":1,"strokeStyle":"solid","roughness":1,"opacity":100,"groupIds":[],"strokeSharpness":"round","seed":817942645,"version":739,"versionNonce":1372439669,"isDeleted":false,"boundElements":null,"updated":1666061417136,"link":null,"locked":false,"status":"pending","fileId":"6bd43211ee82ddbe4467b10ee1b3568c8a099284","scale":[1,1]},{"id":"4_eMwMrxykcOYpG8V2BP3","type":"image","x":-214.3671875,"y":-61.265625,"width":156.890625,"height":156.890625,"angle":0,"strokeColor":"transparent","backgroundColor":"transparent","fillStyle":"hachure","strokeWidth":1,"strokeStyle":"solid","roughness":1,"opacity":100,"groupIds":[],"strokeSharpness":"round","seed":1704413109,"version":554,"versionNonce":121248085,"isDeleted":false,"boundElements":null,"updated":1666061426869,"link":null,"locked":false,"status":"pending","fileId":"eb89aaf315e760f4f8c2e78a1fed2d226ca1d21a","scale":[1,1]},{"id":"Y1i0auWU","type":"text","x":-44.18359375,"y":-73.12890625,"width":85,"height":170,"angle":0,"strokeColor":"#495057","backgroundColor":"transparent","fillStyle":"hachure","strokeWidth":1,"strokeStyle":"solid","roughness":1,"opacity":100,"groupIds":[],"strokeSharpness":"sharp","seed":104860597,"version":551,"versionNonce":1356847099,"isDeleted":false,"boundElements":null,"updated":1666061668072,"link":null,"locked":false,"text":"+","rawText":"+","fontSize":142.07062499999998,"fontFamily":3,"textAlign":"left","verticalAlign":"top","baseline":137,"containerId":null,"originalText":"+"},{"id":"FBtxctuh6F9ppgGAqpDow","type":"image","x":69.6814040465494,"y":-65.0546875,"width":158.10339626083373,"height":137.51171875,"angle":0,"strokeColor":"transparent","backgroundColor":"transparent","fillStyle":"hachure","strokeWidth":1,"strokeStyle":"solid","roughness":1,"opacity":100,"groupIds":[],"strokeSharpness":"round","seed":1073615477,"version":490,"versionNonce":1643038203,"isDeleted":false,"boundElements":null,"updated":1666061417136,"link":null,"locked":false,"status":"pending","fileId":"5a4d38162e2d16463f27e35ae6a79e8bd7cf9e6b","scale":[1,1]},{"id":"BQg4BW44LykKuM7WtNWGk","type":"image","x":80.88153967696627,"y":-201.41796875,"width":135.703125,"height":135.703125,"angle":0,"strokeColor":"transparent","backgroundColor":"transparent","fillStyle":"hachure","strokeWidth":1,"strokeStyle":"solid","roughness":1,"opacity":100,"groupIds":[],"strokeSharpness":"round","seed":713651227,"version":375,"versionNonce":231009077,"isDeleted":false,"boundElements":null,"updated":1666061417136,"link":null,"locked":false,"status":"pending","fileId":"27818bd2e7f082efbd97c0faa5c198d3468a2092","scale":[1,1]},{"id":"bfoYFd37","type":"text","x":257.05859375,"y":-60.47053328804351,"width":77.05859375000001,"height":144.06606657608702,"angle":0,"strokeColor":"#495057","backgroundColor":"transparent","fillStyle":"hachure","strokeWidth":1,"strokeStyle":"solid","roughness":1,"opacity":100,"groupIds":[],"strokeSharpness":"sharp","seed":21707323,"version":173,"versionNonce":2053241691,"isDeleted":false,"boundElements":null,"updated":1666061665399,"link":null,"locked":false,"text":"=","rawText":"=","fontSize":120.61345108695653,"fontFamily":3,"textAlign":"left","verticalAlign":"top","baseline":116.06606657608702,"containerId":null,"originalText":"="},{"id":"hBx7786e","type":"text","x":422.875,"y":-104.4375,"width":161,"height":105,"angle":0,"strokeColor":"#862e9c","backgroundColor":"transparent","fillStyle":"hachure","strokeWidth":1,"strokeStyle":"solid","roughness":1,"opacity":100,"groupIds":[],"strokeSharpness":"sharp","seed":1779335643,"version":248,"versionNonce":1887585883,"isDeleted":false,"boundElements":null,"updated":1666061636158,"link":null,"locked":false,"text":"Fun!","rawText":"Fun!","fontSize":83.33437500000002,"fontFamily":1,"textAlign":"left","verticalAlign":"top","baseline":74,"containerId":null,"originalText":"Fun!"},{"id":"cAA5jNoC","type":"text","x":341.375,"y":0.29296875,"width":324,"height":125,"angle":0,"strokeColor":"#862e9c","backgroundColor":"transparent","fillStyle":"hachure","strokeWidth":1,"strokeStyle":"solid","roughness":1,"opacity":100,"groupIds":[],"strokeSharpness":"sharp","seed":683204219,"version":408,"versionNonce":1655934005,"isDeleted":false,"boundElements":null,"updated":1666061850178,"link":null,"locked":false,"text":"(i.e., simple but powerful local\nnote-taking environment for big\ndata studies with execution and\ninter-connectivity capabilities)\n","rawText":"(i.e., simple but powerful local\nnote-taking environment for big\ndata studies with execution and\ninter-connectivity capabilities)\n","fontSize":20,"fontFamily":1,"textAlign":"center","verticalAlign":"top","baseline":118,"containerId":null,"originalText":"(i.e., simple but powerful local\nnote-taking environment for big\ndata studies with execution and\ninter-connectivity capabilities)\n"}],"appState":{"theme":"light","viewBackgroundColor":"#ffffff","currentItemStrokeColor":"#495057","currentItemBackgroundColor":"transparent","currentItemFillStyle":"hachure","currentItemStrokeWidth":1,"currentItemStrokeStyle":"solid","currentItemRoughness":1,"currentItemOpacity":100,"currentItemFontFamily":1,"currentItemFontSize":20,"currentItemTextAlign":"center","currentItemStrokeSharpness":"sharp","currentItemStartArrowhead":null,"currentItemEndArrowhead":"arrow","currentItemLinearStrokeSharpness":"round","gridSize":null,"colorPalette":{}},"files":{}};InitialData.scrollToContent=true;App=()=>{const e=React.useRef(null),t=React.useRef(null),[n,i]=React.useState({width:void 0,height:void 0});return React.useEffect(()=>{i({width:t.current.getBoundingClientRect().width,height:t.current.getBoundingClientRect().height});const e=()=>{i({width:t.current.getBoundingClientRect().width,height:t.current.getBoundingClientRect().height})};return window.addEventListener("resize",e),()=>window.removeEventListener("resize",e)},[t]),React.createElement(React.Fragment,null,React.createElement("div",{className:"excalidraw-wrapper",ref:t},React.createElement(ExcalidrawLib.Excalidraw,{ref:e,width:n.width,height:n.height,initialData:InitialData,viewModeEnabled:!0,zenModeEnabled:!0,gridModeEnabled:!1})))},excalidrawWrapper=document.getElementById("Drawing_2022-10-17_1848.17.excalidraw.md1");ReactDOM.render(React.createElement(App),excalidrawWrapper);})();</script>

## Intro
Getting started with big data tools is definitely not an easy task. There are a lot of concepts from ... As a data engineer... 

### Apache Spark
If I could advise on which big data tool is worth learning, it would be [[07_work_projects/inbox/Apache Spark|Apache Spark]].   a tool but there is a fairly old that still remains relevant and 

### Minio
Interact the same way you would do with the s3 storage service, from [[AWS|AWS]], through a ==shared API==.

### Delta Lake
Before talking about Delta Lake itself, it is important to give some context on why to use it.

#### Data lakehouse
The modern Big Data Architecture is changing rapidly,... data mesh, data platform,  but something that is trendy since 2020/2021 ... is the Data Lakehouse.

##### ACID transactions
lorem ipsum

## 1. Run local [[Minio|Minio]] instance

> [!NOTE] Note
> A better approach is to run Minio in a container, but for the sake of simplicity and compliance for those who don't wanna deal with Docker, I'm just installing it locally.

Install it through [brew]([https://brew.sh/](https://brew.sh/)):
```shell
brew install minio
```

Run it locally on the port of your preference (e.g., 9090):
```shell
/opt/homebrew/bin/minio server ~/data --console-address :9090
```

(Optional) You can kill the minio server application through Obsidian too:
```shell
pkill minio
```

## 2. Setup [[07_work_projects/inbox/Apache Spark|Apache Spark]] session
1. Set dependencies and settings
2. Create spark session
```python
from pyspark import SparkConf
from pyspark.sql import SparkSession
from pyspark.sql import functions as F

conf = SparkConf().setAll([
        ("spark.jars", "/Users/melo/artifacts/hadoop-aws-3.3.3.jar,/Users/melo/artifacts/aws-java-sdk-bundle-1.11.980.jar,/Users/melo/artifacts/delta-core_2.12-2.1.0.jar,/Users/melo/artifacts/delta-storage-2.1.0.jar"),
		('spark.hadoop.fs.s3a.aws.credentials.provider', 'org.apache.hadoop.fs.s3a.SimpleAWSCredentialsProvider'),
        ('spark.hadoop.fs.s3a.access.key', 'minioadmin'),
        ('spark.hadoop.fs.s3a.secret.key', 'minioadmin'),
        ('spark.hadoop.fs.s3a.impl', 'org.apache.hadoop.fs.s3a.S3AFileSystem'),
        ('spark.hadoop.fs.s3a.endpoint', 'http://0.0.0.0:9000'),
        ('spark.hadoop.fs.s3a.path.style.access', 'true'),
        ('spark.sql.extensions', 'io.delta.sql.DeltaSparkSessionExtension'),
        ('spark.sql.catalog.spark_catalog', 'org.apache.spark.sql.delta.catalog.DeltaCatalog')
])
spark = SparkSession.builder.config(conf=conf).appName("Obsidian PySpark").getOrCreate()
sc = spark.sparkContext
sc.setLogLevel("ERROR")
```

## 3. Testing
### 3.1. Reading local filesystem file
Read a file, make a simple transformation and show it.
```python
test_file = "/Users/bfa/test.txt"
df = spark.read.format("csv").option("delimiter", "\t").load(test_file)
df_modified = df.withColumn("x_column", F.lit("X"))\
	.withColumn("y_column", F.lit("Y"))
df_modified.show()
```

```python
df_modified.count()
```

### 3.2. Reading local [[Minio|Minio]] file
1. Read file from Minio, make some transformations and show it
```python
minio_file = "s3a://lake/raw/AgeDataset-V1.csv"
minio_df = spark.read.format("csv").option("header", True).load(minio_file)
minio_df_modified = minio_df.withColumn("x_column", F.lit("X"))\
	.withColumn("y_column", F.lit("Y"))
minio_df_modified.show()
```

```python
minio_df_modified.count()
```

### 3.3. Handling [[Delta Lake|Delta Lake]] tables
1. Creating delta table
```python
df_modified.write.format("delta").save("s3a://lake/raw/delta_test")
```

2. Reading delta table
```python
delta_df = spark.read.format("delta").load("s3a://lake/raw/delta_test")
delta_df.show()
```