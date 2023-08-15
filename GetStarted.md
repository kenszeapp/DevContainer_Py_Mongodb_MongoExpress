## If change project folder name 
- require change docker-compose.yml volumes remote-name as your project folder name. 
 """
 volumes:
        - ..:/workspaces/<YOUR_FOLDER_NAME>:cached 
 """

## Run jupyter notebook test.ipynb.  
    - install ipykernel package, click Yes.
    - Expect result 
    """
        Inserted document with ID: 64db27b127fde1f3dd28be24
        Found document: {'_id': ObjectId('64db27b127fde1f3dd28be24'), 'name': 'Alice', 'age': 30}
        Modified 1 document(s)
        Deleted 1 document(s)
    """
## 