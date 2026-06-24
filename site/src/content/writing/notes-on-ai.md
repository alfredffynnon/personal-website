---
title: "Notes on AI: From Tokens to Protocols"
description: "Plain definitions of the machinery behind modern AI systems: next-token prediction, context, system prompts, and the file formats, skills, agents, and protocols built on top of them."
date: 2026-06-21
---

These are short, deliberately plain definitions of concepts that recur whenever people talk about how modern AI systems work.

## Next-token prediction

Next-token prediction is the process by which large language models produce text. A model generates text by using prior context to estimate the most likely unit of text, known as a token, and then repeating that process.

## Context

The context is the information available to the model when it estimates the next token.

## System prompt

A system prompt is the broader prompt that tells the system how to respond to the user. The user prompt is appended to the system prompt.

## A .md file

A .md file is a simple text file that uses basic symbols to add formatting. A `#` turns a line into a heading, and asterisks make words bold. It reads well whether you see the raw symbols or the styled version.

## A skill

A skill is a written set of step-by-step instructions for how to perform a certain task. A model can hold a library of skills, retrieving and running the correct one when the task is referenced or needed in a chat.

## An agent

An AI agent completes tasks for a user. Unlike a standard AI chat, which primarily exchanges information with the user, an agent can identify the steps a task requires, execute them, and verify the results.

## MCP

MCP stands for Model Context Protocol. It allows a model to connect to other tools, such as email or files, so that it can use them to complete tasks. Previously, connections to tools had to be built manually; MCP is one standard plug that works everywhere.
