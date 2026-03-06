# MedDRA分类汇总  
  <p align="center">
  <img src="../../images/Med表格2展示.png" style="width:70%;"/>
  </p>


该表将按照MedDRA系统器官类别(SOC)、首选术语(PT)分类汇总不同组别及合计组治疗后发生的不良事件(TEAE)，排序方式如下：先按照合计组SOC降序排列；在SOC下，按照合计组的PT频数降序排列，频数相同的 PT，按照 PT 的字母顺序排列。若未上传不良事件编码文件，该表仅呈现以AETERM(不良事件名称)分类汇总的结果。导入数据后，可以在左侧表格相关选项中选择使用的数据集，下拉表格语言，支持中英文作为表格结果的展示语言。**选择基于的分析集**，仅提供选项“安全性分析集(SAF)”，无须选择。同时**分组变量**选项，默认为计划组别，同时可以下拉选择其余分组。界面支持切换分组变量进行分析，其中治疗组别、阶段和队列中的选项来源为项目收集内容，自定义分组来源为用户上传的自定义文件中的分组变量。通过分组变量的筛选，可以呈现不同的结果。下图为用户自定义分组的结果展示。  
  <p align="center">
  <img src="../../images/Med自定义分组.png" style="width:70%;"/>
  </p>


该表格中还提供**TEAE条件筛选**，默认为“总TEAE(无筛选条件)”。支持用户通过下拉框对TEAE的筛选条件进行组合勾选，同时勾选不同组的筛选条件将满足且条件（同时满足），同时勾选同组的筛选条件将满足或条件（满足一个即可）。 下拉选项如下图。  
  <p align="center">
  <img src="../../images/MedTEAE条件筛选.png" style="width:70%;"/>
  </p>  

 若下拉选项选择严重性组（严重不良事件、导致死亡的TEAE），相关性组（与任一药物相关、与单个药物相关）会出现筛选行（如图1），勾选单选框后，该表会基于原汇总表进行截取。当勾选仅**呈现发生率>=XX%的不良事件**单选框时，只保留发生率>=XX%的不良事件PT条目。其中XX可以自行定义，默认值为5。（如图2）  
  <p align="center">
  <img src="../../images/Med条件筛选汇总.png" style="width:70%;"/>
  </p>

  <p align="center">
  <img src="../../images/Med自定义发生率.png" style="width:70%;"/>
  </p>  

 若下拉选项选择采取措施组（对任一药物采取的措施、对单个药物采取的措施），会新增筛选框**选择关注的对药物采取的措施类型**。  
  <p align="center">
  <img src="../../images/Med采取措施组.png" style="width:70%;"/>
  </p>

若下拉选项选择其他组（若AESI(特别关注的不良事件)、AEIRAE(免疫相关的不良事件)、AEDLT(发生DLT)变量存在），会新增筛选框**选择下列中需要的筛选条件**。  
  <p align="center">
  <img src="../../images/Med其他组.png" style="width:70%;"/>
  </p>


此外，通过**首选术语PT呈现选择**选项，支持通过部分输入筛选需要的不良事件PT，可以多选。选择后生成的表格仅包含选择的PT信息及其SOC的汇总。  
  <p align="center">
  <img src="../../images/Med术语选项.png" style="width:70%;"/>
  </p>


在表格最上方下拉可以选择不同的表格类型。  
  <p align="center">
  <img src="../../images/Med表格选择.png" style="width:70%;"/>
  </p>


下拉可以选择表格3和4，分别汇总**按MedDRA首选术语分类汇总治疗后不良事件**和**按MedDRA系统器官类别、首选术语和最严重CTCAE级别/严重程度分类汇总治疗后不良事件**，分别如下图1、2所示。其中表格4新增加额外增加受试者最严重CTCAE分组，可以选择希望呈现的分组级别（如图3）。  
  <p align="center">
  <img src="../../images/Med表格3展示.png" style="width:70%;"/>
  </p>

  <p align="center">
  <img src="../../images/Med表格4展示.png" style="width:70%;"/>
  </p>

  <p align="center">
  <img src="../../images/Med表格4额外.png" style="width:70%;"/>
  </p>  