# Export Zammad Objects to Excel

This n8n workflow allows you to export data from Zammad, including **Users**, **Roles**, **Groups**, and **Organizations**, into individual Excel files. It provides a streamlined way to manage, analyze, and share your data.

## Features
- **Export Users**: Extract user details such as `email`, `firstname`, `lastname`, `role_ids`, and `group_ids`.
- **Export Organizations**: Export organization details including `organization_id` and `name`.
- **Export Roles**: Retrieve role data with identifiers and names.
- **Export Groups**: Save group information to an Excel file.
- **Excel File Conversion**: All data is converted into separate Excel files for convenience.

## Setup
1. **Import the Workflow**: Upload the `.json` workflow file into your n8n instance.
2. **Configure Credentials**: In the `Basic Variables` node, set:
   - `zammad_base_url`: Your Zammad instance URL.
   - `zammad_api_key`: Your Zammad API key.
3. **Run the Workflow**: Trigger the workflow to generate and download the Excel files.

## Contribution
We welcome contributions to improve this workflow. If you encounter bugs or have ideas for enhancements, please create an issue or submit a pull request.

## Issues and Suggestions
For any issues or suggestions, please use the [GitHub Issues page](https://github.com/Sirhexalot/n8n-Export-Zammad-Objects-Users-Roles-Groups-and-Organizations-to-Excel).

---

**Note**: Ensure you have the necessary API permissions in your Zammad instance to access the relevant data.