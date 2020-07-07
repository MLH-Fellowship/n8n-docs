---
permalink: /nodes/n8n-nodes-base.telegram
---

# Telegram

[Telegram](https://telegram.org) is a cloud-based instant messaging and voice-over-IP service.

::: tip 🔑 Credentials
You can find authentication information for this node [here](../../../credentials/Telegram/README.md).
:::

## Basic Operations

- Chat
	- Get up-to-date information about a chat
	- Leave a group, supergroup or channel
	- Get the member of a chat
	- Set the description of a chat
	- Set the title of a chat
- Callback
	- Send an answer to a callback query sent from the inline keyboard
- Message
	- Edit a text message
	- Send an audio file
	- Send a chat action
	- Send a document
	- Send a text message
	- Send a group of photos or videos to an album
	- Send a photo
	- Send a sticker
	- Send a video

## Example Usage

This workflow shows you how to send a message to a Telegram channel. You can also find the [workflow](https://n8n.io/workflows/451) on this website. This example usage workflow uses the following two nodes.
- [Start](../../core-nodes/Start/README.md)
- [Telegram]()

The final workflow should look like the following image.

![A workflow with the Telegram node](./workflow.png)

### 1. Start node

The Start node exists by default when you create a new workflow.

### 2. Telegram node

1. Create a credential as shown [here](../../../credentials/Telegram/).
2. Select *Message* in the *Resource* field.
3. Select *Send Message* in the *Operation* field.
4. Enter the target channel name prefixed by "@" in *Chat ID*. Example: `@n8ntest`.
5. Write the content of your message in *Text*.
6. Click on *Execute Node* to run the workflow.
