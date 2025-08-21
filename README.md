# **Y-Agent Studio**

一个企业级Agent框架套件，包含了：

Y-Agent：Ai工作流框架

Y-Training：训练框架

Y-DocExt：文本处理框架

Y-DocRetrieve：文档召回框架

# **Y-Agent**

AI工作流，为了追求超高运行效率和应对高度复杂业务场景而设计。

特点：工作流和角色混合编排，支持企业自由API无缝接入，最大程度简化Agent开发流程。并且支持测试集训练集管理。

## **实现了以下功能：**

● 复杂流程编排（有向有环图）：如多路并行、循环依赖执行、多级上游依赖、自动选择下游节点、流程嵌套、自动处理结束等，确保AI工作流程的高效运行。

● 复杂消息传递：支持全局变量传递、单节点变量传递、消息聊天室、工具结果传递

● RAG：内置文档库和参数库

● ReAct：内置多轮推理

● 并发支持：多任务分身、批处理等功能

● 流程日志：完整的流程数据流记录

● 测试：支持单元测试、流程测试

● 训练：语料生产

● 训练：预训练、SFT、强化学习

Click the green **Use this template** button at the top of this repo to copy the Mintlify starter kit. The starter kit contains examples with

- Guide pages
- Navigation
- Customizations
- API reference pages
- Use of popular components

[**Follow the full quickstart guide**](https://starter.mintlify.com/quickstart)

## Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mint) to preview your documentation changes locally. To install, use the following command:

```
npm i -g mint
```

Run the following command at the root of your documentation, where your `docs.json` is located:

```
mint dev
```

View your local preview at `http://localhost:3000`.

## Publishing changes

Install our GitHub app from your [dashboard](https://dashboard.mintlify.com/settings/organization/github-app) to propagate changes from your repo to your deployment. Changes are deployed to production automatically after pushing to the default branch.

## Need help?

### Troubleshooting

- If your dev environment isn't running: Run `mint update` to ensure you have the most recent version of the CLI.
- If a page loads as a 404: Make sure you are running in a folder with a valid `docs.json`.

### Resources

- [Mintlify documentation](https://mintlify.com/docs)
- [Mintlify community](https://mintlify.com/community)