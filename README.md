# Poetry

非常全的古诗词数据，收录了从先秦到现代的共计85万余首古诗词。

## 统计信息

| 朝代                   | 诗词数  | 作者数  |
|-----------------------|--------|--------|
| 宋                    | 287114 |   9446 |
| 明                    | 236957 |   4439 |
| 清                    |  90089 |   8872 |
| 唐                    |  49195 |   2736 |
| 元                    |  37375 |   1209 |
| 近现代                |  28419 |    790 |
| 当代                  |  28219 |    177 |
| 明末清初               |  17700 |    176 |
| 元末明初               |  15736 |     79 |
| 清末民国初             |  15367 |     99 |
| 清末近现代初           |  12464 |     48 |
| 宋末元初              |  12058 |     41 |
| 南北朝                |   4586 |    434 |
| 近现代末当代初         |   3426 |     23 |
| 魏晋                  |   3020 |    251 |
| 金末元初              |   3019 |     17 |
| 金                    |   2741 |    253 |
| 民国末当代初           |   1948 |      9 |
| 隋                    |   1170 |     84 |
| 唐末宋初              |   1118 |     44 |
| 先秦                  |    570 |      8 |
| 隋末唐初              |    472 |     40 |
| 汉                    |    363 |     83 |
| 宋末金初              |    234 |      9 |
| 辽                    |     22 |      7 |
| 秦                    |      2 |      2 |
| 魏晋末南北朝初          |      1 |      1 |
| 总和                  | 853385 |  29377 |

## 数据说明

古诗词数据按朝代存储于多个 csv 文件中，有“题目”、“朝代”、“作者”和“内容”共四个字段。分成多个文件是为了避免单个文件大于 30M。

古诗词中有一些生僻字，这些生僻字属于 utf8mb4 字符，在许多设备中无法显示，故而使用“?”来替代。

## 相关应用

这里收集了使用此数据的有趣应用，欢迎补充。

### [以诗之名](https://poem.werner.wiki/)

搜索你的名字源于哪句古诗词。

![以诗之名二维码](image/poem2.png)

只做了手机版，扫码打开：

![以诗之名二维码](image/poem1.png)

## License

[MIT](https://github.com/werner-wiki/Poetry/blob/master/LICENSE) 许可证。
