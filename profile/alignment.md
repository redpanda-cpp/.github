# MinGW-w64 GCC Distribution Alignment<br>MinGW-w64 GCC 发行版阵营九宫格

## The alignment / 阵营九宫格

| | Lawful<br>守序 | Neutral<br>中立 | Chaotic<br>混乱 |
| :---: | :---: | :---: | :---: |
| Good<br>善良 | Lawful Good<br>守序善良<br>[niXman/mingw-builds](https://github.com/niXman/mingw-builds) | Neutral Good<br>中立善良 | Chaotic Good<br>混乱善良 |
| Neutral<br>中立 | Lawful Neutral<br>守序中立 | True Neutral<br>绝对中立<br>[redpanda-cpp/mingw-lite](https://github.com/redpanda-cpp/mingw-lite) | Chaotic Neutral<br>混乱中立<br>[redpanda-cpp/competitive-cross-gcc](https://github.com/redpanda-cpp/competitive-cross-gcc) |
| Evil<br>邪恶 | Lawful Evil<br>守序邪恶<br>[redpanda-cpp/mingw-builds](https://github.com/redpanda-cpp/mingw-builds) | Neutral Evil<br>中立邪恶 | Chaotic Evil<br>混乱邪恶 |

## Explanation / 解释

### Good vs. Evil / 善良对邪恶

> Good characters and creatures protect innocent life. Evil characters and creatures debase or destroy innocent life, whether for fun or profit.<br>
> 善良的角色和生物保护无辜的生命。邪恶的角色和生物为了乐趣或利润而贬低或破坏无辜的生命。

Good distributions keep ABI stable during large range of major versions.<br>
善良发行版在很多个大版本范围内保持 ABI 稳定。

Neutral distributions keep ABI stable in a major version.<br>
中立发行版在一个大版本内保持 ABI 稳定。

Evil distributions: ABI? What's that?<br>
邪恶的发行版：ABI 是什么？能吃吗？

### Law vs. Chaos / 守序对混乱

> Lawful characters tell the truth, keep their word, respect authority, honor tradition, and judge those who fall short of their duties. Chaotic characters follow their consciences, resent being told what to do, favor new ideas over tradition, and do what they promise if they feel like it.<br>
> 守序的角色诚实，守诺，尊重权威，遵守传统，并对那些未能履行职责的人进行评判。混乱的角色遵循他们的良心，讨厌被命令，喜欢新想法胜过传统，如果他们愿意，他们会履行他们的承诺。

Lawful distributions patch the toolchain to match the de facto standard, niXman's MinGW Builds.<br>
守序发行版修补工具链以匹配事实标准，niXman 的 MinGW Builds。

Neutral distributions patch as less as possible.<br>
中立发行版尽可能少地修补。

Chaotic distributions patch the toolchain for special purpose, violating the de facto standard.<br>
混乱发行版修补工具链以实现特殊目的，违反事实标准。
