[![Next.js 13 and app template Router-ready AI chatbot.](https://chat.vercel.ai/opengraph-image.png)](https://chat.vercel.ai/)

# Science Olympiad Next.js AI Chatbot

An open-source AI chatbot app template built with Next.js, the Vercel AI SDK, OpenAI, and Supabase Auth and Postgres DB.

- [Features](#features)
- [Model Providers](#model-providers)
- [Deploy Your Own](#deploy-your-own)
- [Running locally](#running-locally)
- [Authors](#authors)

## Features

- [Next.js](https://nextjs.org) App Router
- React Server Components (RSCs), Suspense, and Server Actions
- [Vercel AI SDK](https://sdk.vercel.ai/docs) for streaming chat UI
- Support for OpenAI (default), Anthropic, Hugging Face, or custom AI chat models and/or LangChain
- Edge runtime-ready
- [shadcn/ui](https://ui.shadcn.com)
  - Styling with [Tailwind CSS](https://tailwindcss.com)
  - [Radix UI](https://radix-ui.com) for headless component primitives
  - Icons from [Phosphor Icons](https://phosphoricons.com)
- Chat History with [Supabase Postgres DB](https://supabase.com)
- [Supabase Auth](https://supabase.com/auth) for authentication

## Model Providers

This template ships with OpenAI `gpt-3.5-turbo` as the default. However, thanks to the [Vercel AI SDK](https://sdk.vercel.ai/docs), you can switch LLM providers to [Anthropic](https://anthropic.com), [Hugging Face](https://huggingface.co), or using [LangChain](https://js.langchain.com) with just a few lines of code.

## Authors

This library is created by [Vercel](https://vercel.com) and [Next.js](https://nextjs.org) team members, with contributions from:

- Will Blair ([@jaredpalmer](https://twitter.com/willjblair07)) - [LinkedIn](https://linkedin.com/in/willblair1)
