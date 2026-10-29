# mkizilAI Privacy Policy

_Last updated: 29 October 2026 · Contact: mkizil916@gmail.com_

mkizilAI is an AI coding assistant plugin for JetBrains IDEs and VS Code.

## What the plugin sends
When you use the chat, the plugin sends the following to the mkizilAI service (a Cloudflare Worker operated by the vendor):
- the messages you type,
- code, files, images or screenshots that you select or attach, and, in agent mode, the file names and file contents the agent reads from your open project,
- your access code (to authenticate you), and the model you selected.

The plugin does **not** read files outside your project without asking, and it refuses to read common secret locations such as `.env` and `.ssh`.

## Who receives it
The service forwards your request to third-party language-model providers in order to generate an answer. These may include Cloudflare Workers AI, NVIDIA, Groq, Cerebras, Google, Mistral, OpenRouter, GitHub Models and others. Each provider processes the data under its own terms and privacy policy. Do not use the plugin with confidential, proprietary or personal data unless your organization allows it.

## Storage
- Chat history is stored locally on your computer (inside your IDE configuration).
- The service does not store your messages, code or images in a database. The Cloudflare Worker does not write request logs to long-term storage. Cloudflare may process and briefly retain standard request metadata (such as IP address, time and response status) for security, abuse prevention and reliability, normally for no more than a few days.
- Access codes are used only to authenticate requests and for rate limiting; they are not linked to the content of your conversations.

## Your choices
You decide what code is shared. You can stop using the plugin at any time and remove it from your IDE. To request deletion of any data held by the service, write to the contact address above.

## Changes
We may update this policy; the date above shows the latest version.
