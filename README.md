# n8n-nodes-sharepoint-plus

This is an n8n community node for **Microsoft SharePoint** with full document library (drives) support.

## Features

### Resources

- **File** — Download, Upload, Update files in SharePoint document libraries
- **Item** — Create, Read, Update, Delete, Upsert items in SharePoint lists
- **List** — Get and list SharePoint lists

### Document Library Support

Unlike the built-in SharePoint node, this community node includes a **Document Library** selector that lets you browse and select from all available document libraries (drives) within a SharePoint site. This includes:

- Searchable document library dropdown
- Folder browser within each library (including root folder option)
- File browser within folders

## Installation

### In n8n (Community Nodes)

1. Go to **Settings > Community Nodes**
2. Select **Install a community node**
3. Enter `n8n-nodes-sharepoint-plus`
4. Click **Install**

### Manual Installation

```bash
cd ~/.n8n
npm install n8n-nodes-sharepoint-plus
```

## Credentials

This node uses **Microsoft SharePoint OAuth2** authentication. You will need:

1. An Azure AD app registration with SharePoint permissions
2. Your SharePoint subdomain (e.g., `tenant123` from `https://tenant123.sharepoint.com`)

See the [n8n Microsoft credentials documentation](https://docs.n8n.io/integrations/builtin/credentials/microsoft/) for setup instructions.

## Compatibility

- Requires n8n version 1.0.0 or later
- Node.js 20.15 or later

## License

[MIT](LICENSE.md)
