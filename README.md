# -{
    "queryName": "泰州",  // 查询的城市名字，如果无数据返回空
    "date": "2018-01-06",  // 第一天数据日期，缓存可以判断是否过期
    "weatherItems": [     // 天气情况数组，30天
        {
            "date": "01月06日",      // 日期
            "dayKind": "今天",        // 星期几，前三天是今天明天后天 
            "weather": "雪",           // 天气描述
            "weatherImg": "b15.png",   // 天气用什么图片表示
            "minTemperature": "-6",    // 最低温度 
            "maxTemperature": "4",     // 最高温度
            "wind": "东北风 3级"     // 风力描述
        },
        ...
    ]
}
