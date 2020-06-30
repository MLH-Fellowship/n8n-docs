---
permalink: /nodes/n8n-nodes-base.dropbox
---

# Dropbox

[Dropbox](https://dropbox.com) is a cloud-based file storage and sharing service, accessible through multiple devices.

::: tip 🔑 Credentials
You can find authentication information for this node [here](../../../credentials/Dropbox/README.md).
:::

## Basic Operations

- File
	- Copy a file
	- Delete a file
	- Download a file
	- Move a file
	- Upload a file
- Folder
	- Copy a file
	- Create a file
	- Delete a file
	- List files and folders in the folder
	- Move a folder

## Example Usage

This workflow shows you how to create a Dropbox folder. You can also find the [workflow](https://n8n.io/workflows/439) on this website. This example usage workflow uses the following two nodes.
- [Start](../../core-nodes/Start)
- [Dropbox]()

The final workflow should look like the following image.

![A workflow with the Dropbox node](./workflow.png)

### 1. Start node

The Start node exists by default when you create a new workflow.

### 2. Dropbox node

1. Click on the plus button, search for "Dropbox", select it and double-click on the new node.
2. Select "Create new" in the *Dropbox API* field.
3. Create a credential as shown in [this tutorial](../../../credentials/Dropbox/).
4. Enter the name of the new folder *Folder* field.
5. Click on *Execute Node* to run the workflow.
