# GlobalDatabase
A global database used by all of our products.

# Folder descriptions
Here you'll find a description for every folder and file in this repository.
* `SimpleCoreAPI`: Files used by the [SimpleCoreAPI](https://github.com/TheProgramSrc/SimpleCoreAPI)
<details>
  <summary>File Descriptions</summary> 
  
  * `SimpleCoreAPI/modules-repository.json`: A file that contains all the available and supported modules.<br>
  Format: 
  ```json
  {
    "moduleid": {
      "display": "Display Name",
      "file_name": "FileName",
      "repository": "User/Repository"
    }
  }
  ```
  - `moduleid`: Stands for the module id, it must be something unique
  - `display`: Used when is needed to be displayed in any UI
  - `file_name`: Used when updating/downloading, this will tell the helper how the file name should be (just like the `moduleid`, it needs to be unique).
  - `repository`: (_Optional_) If specified must follow github format `User/Repo`. If not specified, the format `TheProgramSrc/SimpleCore-{moduleid}` will be used. For `tasksmodule` the formatted repo would be `TheProgramSrc/SimpleCore-tasksmodule`, since github is not case sensitive this won't cause any issues.
  
</details>
