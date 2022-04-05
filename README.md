![tsa](https://cloud.githubusercontent.com/assets/8536299/9762459/eaa8f8a0-5703-11e5-9c47-d89b8d40b115.jpg)

3D TSA "Travel Sentry" 主钥匙
=========
最近，《华盛顿邮报》和 TravelSentry 网站上托管的 [PDF](https://www.travelsentry.org/security/pdf/passkeys.pdf) 泄露了 TSA 主行李钥匙的图片。此 repo 是 [复制尝试](https://twitter.com/InfoSecJesus/status/641662669758574593)

安全研究人员已经 [长期警告](http://www.crypto.com/masterkey.html) 使用 [master-keyed locks] (https://twitter.com/J0hnnyXm4s/status/642123709311008768) 的危险

TSA 发布了一份官方声明，表明 [他们甚至不在乎我们已经这样做了](https://theintercept.com/2015/09/16/tsa-doesnt-really-care-luggage- locks-hacked/)，因为现在毫无意义的锁会影响防盗，而不是航空公司的安全。

> **[!] 重要**：这些键尚未经过广泛测试，尽管我们确实有报告称许多 [确实有效](https://twitter.com/bernard/status/641662069427847168) 至少来自 [来源]（http://arstechnica.com/security/2015/09/video-3d-printed-tsa-travel-sentry-keys-really-do-open-tsa-locks/）。 006 可能永远无法工作，因为我们不确定“坑”的深度，而且消费级 3D 打印机可能无法完成如此精细的任务。

> 添加了 [MS3FGX](https://github.com/MS3FGX) 的密钥的粗短版本，这似乎 [仍然可以正常工作！](https://twitter.com/JimyLongs/status/641820527892414464)

### Thanks:
- 特别感谢 [@darksim905](https://twitter.com/darksim905) 和 [@irongeek_adc](https://twitter.com/irongeek_adc/status/640907196197404672) 以及一些匿名的其他人，他们都向我们发送了关于这些钥匙的图像和信息。 此外，[@j0hnnyXm4s](https://twitter.com/J0hnnyXm4s) 提供他的钥匙大小比率和问题管理/建议。


3D TSA "Safe Skies" 主钥匙
=========
Safe Skies 按照自己的标准生产 TSA 批准的锁具，与 Travel Sentry 竞争，甚至起诉 Travel Sentry 侵犯专利权。 他们的市场份额比 Travel Sentry 小得多。 这些锁可以通过注意键槽旁边的“安全天空”字样来识别，位于与Safe Skies“TSA00N”符号类似的位置。 所有可用信息都表明其整个系统仅存在一个覆盖/主密钥。 有了这些知识和一把大锤子（不，真的），[@darksim905](https://twitter.com/darksim905) 和 [Nite0wl](https://twitter.com/nite0wl_2600) 对万能钥匙进行了逆向工程，并创建适合打印的 3D 文件。 他们于 2016 年 7 月在纽约市举行的第 11 届地球黑客大会上与 [@j0hnnyXm4s](https://twitter.com/J0hnnyXm4s) 一起展示了他们的发现。


问题报告
=========

如果您打印密钥但它不起作用：

* 首先，使用卡尺或其他高精度设备确保您打印的钥匙与模型准确无误。湿度、膨胀和环境室温会对打印尺寸精度产生严重影响。

* 如果准确，请在 github 上打开一个问题，指定问题文件，以及存在哪些问题（即“键槽太宽”、“键槽太高”等）。

* 上传您锁的钥匙槽的图片。

* 如果您有锁的原始钥匙，请提供钥匙从肩部到顶端的尺寸、肩部的总高度和宽度。 （即刀片的 X、Y 和 Z 轴）。有些钥匙只有一个肩部。



执照
=========
这个项目是在知识共享署名-非商业性 3.0 未移植许可下发布的。

![](https://upload.wikimedia.org/wikipedia/commons/9/99/Cc-by-nc_icon.svg)

您可以自由：

* 分享——以任何媒介或格式复制和重新分发材料
* 适应——重新混合、转换和构建材料
* 只要您遵守许可条款，许可方就不能撤销这些自由。

根据以下条款：

* [!]Attribution — 您必须对本项目的所有贡献者给予适当的评价，提供许可证链接，并说明是否进行了更改。您可以以任何合理的方式这样做，但不得以任何方式暗示许可人认可您或您的使用。

* [!]NonCommercial — 您不得将资料用于商业目的。
没有额外的限制——您不得应用法律条款或技术措施来合法地限制他人做许可允许的任何事情。

注意事项：

对于公共领域中的材料元素或适用的例外或限制允许您使用的情况，您不必遵守许可。

不提供任何保证。

有关此许可证的全文，请参阅 [LICENSE.md](https://github.com/Xyl2k/TSA-Travel-Sentry-master-keys/blob/master/LICENSE.md)。
