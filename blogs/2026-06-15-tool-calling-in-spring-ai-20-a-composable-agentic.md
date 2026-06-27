---
title: "Tool Calling in Spring AI 2.0: A Composable, Agentic Architecture"
url: "https://spring.io/blog/2026/06/15/spring-ai-composable-tool-calling"
date: "2026-06-15"
author: "tzolov"
feed_url: "https://spring.io/blog.atom"
---
Spring AI 2.0 redesigns tool calling by lifting the tool loop into the advisor chain as a first-class, composable ToolCallingAdvisor, replacing the model-specific internals of Spring AI 1.x. New patterns include a ToolSearchToolCallingAdvisor offering progressive tool disclosure that cuts token usage 34-64% across OpenAI, Anthropic, and Gemini for 30+ tool scenarios, plus MCP integration, tool argument augmentation, and breaking migration changes such as FunctionToolCallback beans and immutable options.
