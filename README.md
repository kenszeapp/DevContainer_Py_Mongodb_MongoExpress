# Python + mongodb devcontainer. The Python version 3.11. 

## Get Started
Open this folder with VS Code, 【Ctrl】 + 【Shift】 + P then select Open Folder in Container. 

## Run jupyter notebook test.ipynb.  
- VS Code prompts install ipykernel package, click Yes.
- Expect result 
    ```
        Inserted document with ID: 64db27b127fde1f3dd28be24
        Found document: {'_id': ObjectId('64db27b127fde1f3dd28be24'), 'name': 'Alice', 'age': 30}
        Modified 1 document(s)
        Deleted 1 document(s)
    ```
## If change project folder name 
- require volumes remote-name as your project folder name inside docker-compose.yml file.
    ```
        ... 
        volumes:
            - ..:/workspaces/<YOUR_FOLDER_NAME>:cached 
    ```

