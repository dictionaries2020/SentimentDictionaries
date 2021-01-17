

# 金融领域中文情绪词典

本项目构建了金融领域中文情绪词典。本词典分为正式文本情绪词典和非正式文本情绪词典。其中正式文本情绪词典适用于年报语调指标构建，非正式文本情绪词典适用于社交媒体情绪指标构建。读者如需使用该词典，请引用如下参考文献：

姚加权，冯绪，王赞钧，纪荣嵘，张维. 语调、情绪及其市场影响——基于金融领域中文情绪词典的研究. 管理科学学报，已接受待发表.

# 词典构建方法

（1）正式文本情绪词典构建

利用词典重组方法，在现有广泛使用词典的基础上提炼和构建了适用于金融领域正式文本研究的情绪词典。利用2003-2015年间所有中国上市公司年报文本（共计19970份），结合Engelberg et al.（2012）的语调判断方法区分单个年报的正负面情绪。对三份现有通用型中文情绪词典和Loughran & McDonald（2011）情绪词典的中文翻译版进行词语整合，并加入年报语料的分词结果去重得到初始词典，然后运用带惩罚机制词频法提取情绪词生成正式用语情绪词典。

（2）非正式文本情绪词典构建

利用2011-2016年间雪球论坛用户发帖以及2010-2017年间东方财富网股吧发帖（共计8130多万条发帖），以8789条带有情绪识别符号的股票论坛发帖为训练集，结合长短期记忆模型（Long Short-Term Memory, LSTM）的深度学习算法，并运用带惩罚机制词频法生成了非正式用语情绪词典。

更多词典构建细节请参考论文。

**参考文献**

[1]   姚加权，冯绪，王赞钧，纪荣嵘，张维. 语调、情绪及其市场影响——基于金融领域中文情绪词典的研究. 管理科学学报，已接受待发表.

[2]   Engelberg, J. E., A. V. Reed, and M. C. Ringgenberg. How Are Shorts Informed? Short Sellers, News, and Information Processing [J]. Journal of Financial Economics. 2012. 105(2), 260-278. 

[3]   Loughran, T., and B. McDonald. When Is A Liability Not A Liability? Textual Analysis, Dictionaries, and 10‐Ks [J]. Journal of Finance. 2011. 66(1), 35-65.

# 附录

<table class="tg">
    <tr>
        <th class="tg-0lax" colspan=15 align="left">部分正式用语情绪词汇：</th>
    </tr>
    <tr>
        <th class="tg-0lax" colspan=15>负面</th>
    </tr>
    <tr>
        <td class="tg-0lax">风险</td>
        <td class="tg-0lax">亏损</td>
        <td class="tg-0lax">违反</td>
        <td class="tg-0lax">损害</td>
        <td class="tg-0lax">舞弊</td>
        <td class="tg-0lax">严重</td>
        <td class="tg-0lax">约束</td>
        <td class="tg-0lax">手段</td>
        <td class="tg-0lax">坏帐</td>
        <td class="tg-0lax">负担</td>
    </tr>
    <tr>
        <td class="tg-0lax">越权</td>
        <td class="tg-0lax">不道德</td>
        <td class="tg-0lax">毁损</td>
        <td class="tg-0lax">异常</td>
        <td class="tg-0lax">谴责</td>
        <td class="tg-0lax">严峻</td>
        <td class="tg-0lax">委靡</td>
        <td class="tg-0lax">困顿</td>
        <td class="tg-0lax">失利</td>
        <td class="tg-0lax">守旧</td>
    </tr>
    <tr>
        <td class="tg-0lax">不健全</td>
        <td class="tg-0lax">仿造</td>
        <td class="tg-0lax">倒闭</td>
        <td class="tg-0lax">侮辱</td>
        <td class="tg-0lax">压制</td>
        <td class="tg-0lax">冒进</td>
        <td class="tg-0lax">刁难</td>
        <td class="tg-0lax">危害</td>
        <td class="tg-0lax">压迫</td>
        <td class="tg-0lax">低迷</td>
    </tr>
    <tr>
        <th class="tg-0lax" colspan=15>正面</th>
    </tr>
    <tr>
        <td class="tg-0lax">平稳</td>
        <td class="tg-0lax">崛起</td>
        <td class="tg-0lax">精神</td>
        <td class="tg-0lax">和谐</td>
        <td class="tg-0lax">突出</td>
        <td class="tg-0lax">合格</td>
        <td class="tg-0lax">力争</td>
        <td class="tg-0lax">透明</td>
        <td class="tg-0lax">成熟</td>
        <td class="tg-0lax">迅速</td>
    </tr>
    <tr>
        <td class="tg-0lax">倾心</td>
        <td class="tg-0lax">保密</td>
        <td class="tg-0lax">清晰</td>
        <td class="tg-0lax">积极性</td>
        <td class="tg-0lax">严正</td>
        <td class="tg-0lax">丰硕</td>
        <td class="tg-0lax">乐观</td>
        <td class="tg-0lax">从优</td>
        <td class="tg-0lax">信誉</td>
        <td class="tg-0lax">充实</td>
    </tr>
    <tr>
        <td class="tg-0lax">不屈</td>
        <td class="tg-0lax">威信</td>
        <td class="tg-0lax">完备</td>
        <td class="tg-0lax">创新</td>
        <td class="tg-0lax">勇气</td>
        <td class="tg-0lax">飙升</td>
        <td class="tg-0lax">富余</td>
        <td class="tg-0lax">干劲</td>
        <td class="tg-0lax">庆祝</td>
        <td class="tg-0lax">强悍</td>
    </tr>
    <tr>
        <th class="tg-0lax" colspan=15 align="left">部分非正式用语情绪词汇：</th>
    </tr>
    <tr>
        <th class="tg-0lax" colspan=15>负面</th>
    </tr>
    <tr>
        <td class="tg-0lax">垃圾</td>
        <td class="tg-0lax">下跌</td>
        <td class="tg-0lax">回调</td>
        <td class="tg-0lax">割肉</td>
        <td class="tg-0lax">套牢</td>
        <td class="tg-0lax">风险</td>
        <td class="tg-0lax">减持</td>
        <td class="tg-0lax">抛售</td>
        <td class="tg-0lax">可悲</td>
        <td class="tg-0lax">低迷</td>
    </tr>
    <tr>
        <td class="tg-0lax">向下</td>
        <td class="tg-0lax">跌破</td>
        <td class="tg-0lax">无耻</td>
        <td class="tg-0lax">狗屎</td>
        <td class="tg-0lax">利空</td>
        <td class="tg-0lax">困顿</td>
        <td class="tg-0lax">可笑</td>
        <td class="tg-0lax">跳空</td>
        <td class="tg-0lax">倒霉</td>
        <td class="tg-0lax">赔钱</td>
    </tr>
    <tr>
        <td class="tg-0lax">烂股</td>
        <td class="tg-0lax">小人</td>
        <td class="tg-0lax">绝望</td>
        <td class="tg-0lax">卑鄙</td>
        <td class="tg-0lax">压制</td>
        <td class="tg-0lax">不值</td>
        <td class="tg-0lax">草包</td>
        <td class="tg-0lax">担心</td>
        <td class="tg-0lax">丢脸</td>
        <td class="tg-0lax">烦心</td>
    </tr>
    <tr>
        <th class="tg-0lax" colspan=15>正面</th>
    </tr>
    <tr>
        <td class="tg-0lax">涨停</td>
        <td class="tg-0lax">崛起</td>
        <td class="tg-0lax">胜利</td>
        <td class="tg-0lax">献花</td>
        <td class="tg-0lax">发财</td>
        <td class="tg-0lax">暴涨</td>
        <td class="tg-0lax">战斗机</td>
        <td class="tg-0lax">稳赚</td>
        <td class="tg-0lax">过瘾</td>
        <td class="tg-0lax">幸运</td>
    </tr>
    <tr>
        <td class="tg-0lax">黑马</td>
        <td class="tg-0lax">赚翻天</td>
        <td class="tg-0lax">爽歪歪</td>
        <td class="tg-0lax">止跌</td>
        <td class="tg-0lax">恭喜</td>
        <td class="tg-0lax">开心</td>
        <td class="tg-0lax">舒服</td>
        <td class="tg-0lax">漂亮</td>
        <td class="tg-0lax">牛股</td>
        <td class="tg-0lax">完美</td>
    </tr>
    <tr>
        <td class="tg-0lax">赚大</td>
        <td class="tg-0lax">期待</td>
        <td class="tg-0lax">好样</td>
        <td class="tg-0lax">创新</td>
        <td class="tg-0lax">勇气</td>
        <td class="tg-0lax">神奇</td>
        <td class="tg-0lax">明智</td>
        <td class="tg-0lax">成功</td>
        <td class="tg-0lax">飙升</td>
        <td class="tg-0lax">支持</td>
    </tr>
</table>

