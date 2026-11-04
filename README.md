# 🥖 鲍师傅盲盒抢购助手

---

## 项目背景

Too Good To Go 上的鲍师傅盲盒，每次开售几秒内就没了，并且存在大量倒卖。

作者在又一场"22:47 开售、准时血战"的抢购中败北后，产生了这个项目

- 本工具的用途是**用你自己的真实账号、抢一份留着自己吃的盲盒**。
- **如果你打算用它来批量抢购倒卖——你正是这个项目想讲述的那个问题本身**。请直接关掉这个页面。

## 下载与使用

**v0.1.0 预发布版已上线**：在 [Releases](../../releases) 页下载 `MasterBunPastryGrabber-v0.1.0-x64.exe`（约 18 MB，Windows x64，单文件免安装），双击运行。

- 启动即菜单：首次运行引导 邮箱+验证码 登录（官方登录方式）；
- **建议先在菜单 1 完整录入一次支付信息（卡号/有效期/CVV，本地加密保存）**——此后支付全程自动化；菜单 2 开始抢购：到开售时刻自动出手；
- Ctrl+C 随时中止，停止后回到菜单。

**使用前提**：在菜单 1 录入支付信息即可（目前**无需**在官方 App 内预先绑卡）；触发银行验证时会提示输入短信验证码或自动打开浏览器完成。

**支持范围**：**中国银行外币卡（卓隽万事达系列）**支持全程自动完成（含短信验证码自动提示）；**其他银行卡**不限制卡号，会自动切换为浏览器验证方式完成支付。预发布版本，偶有粗糙在所难免。

## ⚠️ 免责声明

- **无任何关联**。本项目与 Too Good To Go、任何面包房、任何支付服务提供商均无关联。所有商标权利归各自所有者。"Master Bun Pastry"只是本工具的目标，并非商业关联。
- **非官方客户端**。本工具不通过官方 App、而是以自建客户端直接与平台通信。这明确违反 Too Good To Go 的用户条款。使用非官方客户端的现实风险包括限流、被标记、**账号被永久封禁**、订单被取消——风险自负。
- **风控对抗**。平台的反自动化保护可能随时变更且不会另行通知。任何请求、乃至整个工具，都可能随时失效；而失败请求可能进一步暴露你的账号。本项目不对可用性做任何承诺。
- **支付风险**。下单走的是真实支付流程（银行卡 / 3-D Secure）。因使用本工具造成的支付失败、重复扣款、扣款失败等后果及后续申诉均需自行承担。每次运行后请在官方 App 中核对订单状态。
- **设备与文件安全**。登录凭证等敏感数据保存于本机，请妥善保管你的设备与本地文件，避免凭证被他人获取。
- **无担保**。本项目按"现状"提供，不作任何明示或暗示的担保。对于封号、财产损失及其他一切因使用（或无法使用）本项目产生的后果，作者不承担任何责任。
- **地区合规**。自动化购买在你所在的地区可能受限制或属违法行为，运行前请自行了解当地法规。
- **仅供学习**。发布内容主要用于学习研究 App 安全、协议分析与自动化工程技术。请负责任地使用，并且请勿进行倒卖。

## 许可

本工具以二进制形式免费提供，不公开源码，采用
[CC BY-NC-ND 4.0](https://creativecommons.org/licenses/by-nc-nd/4.0/deed.zh) 许可：

- **你可以**：自由分享本工具的原始二进制文件（未经修改的 exe），但须保留作者署名；
- **你不能**：将其用于任何商业目的；修改或以此为基础创作衍生品后再分发。
- 源代码**不在此许可范围内**——不公开、不可取得、不接受代码贡献。
- 本声明不构成对 Too Good To Go 任何条款的挑战或许可。

---

## A note for Too Good To Go

If you are reading this as a member of the Too Good To Go team: this project was born out of a very specific frustration. On Chinese social media, bags from one particular store — Master Bun Pastry in London — are resold at considerable scale: every limited batch disappears within seconds, and much of it shows up for resale shortly after. This tool was written after losing yet another one of those timed battles to resellers.

To keep its footprint deliberate and minimal:

- It is **restricted to that single store**— it cannot be pointed at any other store;
- It is meant to help **one person buy one bag to eat themselves**, not to enable reselling (see the disclaimer above);
- It is **non-commercial**— nothing here is for sale;
- The author does not hide that this is an **unofficial client, which conflicts with your Terms of Service**— that risk is stated plainly to every user of this tool.

Weighing all of the above: if Too Good To Go still considers this repository inappropriate, please feel free to contact the repository owner through GitHub, and the repository will be taken down upon your request.
