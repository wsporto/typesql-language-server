
# TypeSQL Language Server

We’re thrilled to introduce the preview release of the **TypeSQL Language Server** extension! This extension aims to enhance your [TypeSQL](https://github.com/wsporto/typesql) experience by providing autocompletion for raw SQL statements, allowing you to write SQL queries with greater ease and accuracy.

![TypeSQL Language Server Demo](https://raw.githubusercontent.com/wsporto/typesql/main/typesql-language-server.gif)

**Database Compatibility:** 
- The extension supports SQLite only.

**Key Features:**

- **Autocompletion:** Get intelligent suggestions for SQL statements, streamlining your query writing process and minimizing errors.
- **Type-Safe SQL Execution:** Write and execute type-safe SQL queries with confidence, thanks to the integration with TypeSQL.

**Important Considerations:**

- **Preview Status:** This is an early version of the extension and may contain bugs or incomplete features.

- **Known Issues:** Some features may not work as expected. For details on known issues, please refer to the release notes or our issue tracker.

- **Feedback:** We value your feedback! Please report any issues or provide suggestions to help us improve the extension.

**Configuration:**

1. In your project’s root directory, create a file named `typesql.json`. This file should contain the database URI for your SQLite database. The configuration should look like this:

```json
{
  "databaseUri": "path/to/your/database.sqlite"
}
```
If you are already using TypeSQL, you might already have a `typesql.json` configuration file in your project. 

\
Thank you for using the TypeSQL VSCode extension. We hope it enhances your SQL development experience!

Best regards,\
The TypeSQL Team