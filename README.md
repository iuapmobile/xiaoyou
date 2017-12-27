# xiaoyou
# api
### 获取小友信息
* url
https://aiserver.yonyoucloud.com/xiaoyou/openapi/xy/api/getxiaoyouinfo?userid=demo2    
* 参数
    * userid:当前用户在IM注册的username，如果有该参数，则小友会自动为小友发送一条信息
    * autoSendMsg:是否自动为小友发送一条消息
    * msg:自动给小友发消息时的消息内容
    
    
# 搜索人员服务
    地址：https://aiserver.yonyoucloud.com/openapi/xy/api/searchyonyoustaff?q=姚 
    返回值如下：    
    
    {
      "response": {
            "result": [{
                "name": "姚博",
                "mobile": "13810558787",
                "id": "04167132-e2e4-4b9e-8aee-7abe9aaddf77",
                "email": "yaoboc@yonyou.com"
            },
            {
                "name": "姚磊",
                "mobile": "15801611227",
                "id": "e2ccc98f-1f92-4d11-87f0-2fcf59526f77",
                "email": "yaoleib@yonyou.com"
            },
            {
                "name": "姚鑫",
                "mobile": "18940923822",
                "id": "e6f04c86-e79c-4d6f-8b4f-8cf8cada973f",
                "email": "yaoxinc@yonyou.com"
            },
            {
                "name": "姚纬昊",
                "mobile": "15011050667",
                "id": "ff4631d7-a212-4e7c-825a-313a5b6f3d52",
                "email": "yaowh@yonyou.com"
            }]
        },
        "responseHeader": {
            "status": "0"
        }
    }
      
# 搜索原子服务
    地址：https://aiserver.yonyoucloud.com/xiaoyou/openapi/xy/api/searchyonyouatomservices?q=查    
    返回值如下：    
    
    {
        "response": {
            "result": [{
                "name": "查社保",
                "id": "094a14f0-a30a-49d1-a73f-78e019c5123d"
            },
            {
                "name": "凭证查询",
                "id": "1df619dc-fcdd-4a1c-9345-3f9600db806b"
            },
            {
                "name": "查薪资",
                "id": "ac5dd3f2-b1d8-412d-8be2-69d528706766"
            },
            {
                "name": "假勤档案查看",
                "id": "edfa5b5f-8735-4f7c-8bc6-c0c478c52a82"
            }]
        },
        "responseHeader": {
            "status": "0"
        }
    }
    
      
