# RestLy-Chrome-Extension-Docs
RestLy is a lightweight, user-friendly Chrome extension that simplifies REST API testing. It provides an intuitive interface to send API requests, manage headers, and save API collections for future use.

🔗 Chrome Web Store Link

RestLy Chrome Extension

✨ Features

📝 Send API Requests: Supports GET, POST, PUT, DELETE, PATCH, and more.
🔐 Authentication Options:
Basic Auth
API Key

Premium features:
OAuth 2.0 (Authorization Code, Client Credentials, Password Grant)
📂 Save and Manage API Collections: Save frequently used requests with headers and parameters.
📤 Export/Import Collections: Export API collections for backup or sharing.
🔄 Response Handling: View, format, and inspect API responses easily.
🛡️ Secure Token Management: Store OAuth tokens securely.
🛠️ Installation Instructions

🚀 Installing from Chrome Web Store
Go to RestLy on Chrome Web Store.
Click Add to Chrome and confirm the installation.


📦 Usage Guide

1. 📝 Sending a Request
Open RestLy from the Chrome toolbar.
Select the request method (GET, POST, etc.).
Enter the API endpoint.
Add headers, request body, and other parameters as needed.
Click Send to see the response.

2. 🔐 Authentication Types
RestLy supports multiple authentication types:

  - Basic Auth: Provide a username and password.
  - API Key: Add API keys in headers or query parameters.
  - OAuth 2.0: Configure OAuth with various grant types.

3. 📂 Saving and Managing Collections
Save frequently used API requests as collections.
View and organize saved collections.
Import or export collections for backup or sharing.

4. 📤 Exporting & Importing Collections
Export API requests to a .json file.
Import collections from an existing .json file.
⚙️ Configuration

📡 OAuth 2.0 Setup
Go to the Auth section.
Select OAuth 2.0.
Provide necessary credentials:
Client ID
Client Secret
Grant Type
Redirect URI
Click Get Token to authenticate.
📄 API Request Example

Sample POST Request
POST /api/v1/user
Host: api.example.com
Content-Type: application/json
Authorization: Bearer <your-token>

{
  "name": "John Doe",
  "email": "john.doe@example.com"
}
🔄 Managing API Responses

View raw responses.
Format responses for readability.
Inspect headers and status codes.
🔥 Contributing

We welcome contributions! To contribute:

Fork the repository.
Create a new branch.
Make your changes.
Submit a pull request.
📧 Contact Us

For any issues, suggestions, or feature requests, please contact:

Email: jyotihelkar@gmail.com
GitHub Issues: Report an Issue


🎉 Happy Testing!

RestLy is designed to simplify your API testing process. Enjoy!
