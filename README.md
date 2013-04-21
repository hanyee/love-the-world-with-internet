love-the-world-with-internet
============================

    love-the-world-with-internet 是一个民间的公益性质的基于互联网的亲人寻找服务标准，
    适用于各家大型互联网公司提供以此标准共同协助，帮助有困难的人来寻找自己没有音讯的亲人，
    希望做到的是各家提供服务的机构或组织可以做到信息数据互通，
    使得需要帮助的人们无论走到哪个家的寻人入口都可以得到统一的数据信息，在公益事业上互联网的力量是凝聚在一起的！

- - -

标准说明:
============================
>* 此标准提供了完整的人员信息数据字段的定义 `person.json`， 所有人员信息相关的定义都在此描述。



>* 此标准提供了 `who-is-lost.json` 信息用于定义失去联系的人员的信息，其信息数据字段完全根据`person.json`来制定，是 `person.json` 的子集。

>* 此标准提供了 `who-is-finding.json` 信息用于定义正在寻人的人员的信息，其信息数据字段完全根据`person.json`来制定，是 `person.json` 的子集。

>*  `提供服务的组织或机构`请按照标准的数据字段来定义自己寻人服务的数据便于为于他人提供统一的数据接口。


>*  `提供服务的组织或机构`提供的服务请统一返回此标准定义的`json`结构的数据。


>* `提供服务的组织或机构`可以根据其他`提供服务的组织或机构`提供的服务来整合自己的服务，使得数据能够统一。


>*  `提供服务的组织或机构`需要提供至少两个服务接口：

        /path/to/people-who-is-lost.json
        /path/to/people-who-is-finding.json






标准维护机制:
============================
>* 这是一个公共的、公开的、民间的、公益性质的、基于互联网的、寻人服务通用标准。

>* 任何一个有爱心的人士都可以参与共同定制标准。

>* 希望标准渐成熟时可以交给专业公益组织的负责人进行标准的代码维护。`*`


个人隐私和安全问题:
============================
>* 目前出于公益目的，对在互联网上暴露的个人隐私信息的范围和尺度尚未能够做到充分分析和考虑，希望更多有爱心有能力的人士共同加入讨论，建立标准。`*`

>* 此标准第一稿参考了目前互联网寻人服务的

>* 对于公开寻人者留下的联系方式是否可信，是否诈骗性质的信息，希望能够得到各地公安机关的支持，对于信息进行验证，人员信息中提供了 `"certified" : "yes"` 的字段用于标识，对于信息认证的方式，相关标准有待进一步制定。

如何加入:
============================
>* 您可以自由的fork代码改动后提交pull request请求合并。

>* 维护人员第一时间处理合并请求。

>* 是否合并的标准将进一步制定。

