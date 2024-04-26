# fabric-tenant-admin-semantic-models

A .pbip project file using the TMDL (preview) language to create a Direct Lake semantic model that sits on top of Delta tables created with the [Fabric Scanner API notebook](https://github.com/klinejordan/fabric-tenant-admin-notebooks/blob/main/Fabric%20Scanner%20API.ipynb)

Instructions
- Successfully run the above notebook with a full scan at least once
- Download the entire "Fabric Reporting Semantic Model" folder
- Open the expressions.tmdl file in Notepad or Visual Studio Code or any text editor
- Modify the DatabaseQuery expression to point to resources in your tenant
- Deploy to the Fabric workspace where your Lakehouse is

Future Work:
- Report templates to help get started visualizing tenant information
