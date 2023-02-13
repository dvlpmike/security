# PyPI

The Python Package (PyPI) is a vast repository of packages and libraries that can be used in Python projects. When working on a new project, you may need to verify the quality and reliability of the packages you are using. In this guide, we will discuss the steps you can take to verify the Python packages you are using.

## Check pypi packages
Steps to verify a python package:
1. Check releases
2. Check out the daily downloads package on https://pypistats.org/
3. Check out projects that use package on https://libraries.io/
4. You might download the package and check for below words:
   - system
   - popen
   - eval
   - exec
   - powershell
 
 **For windows**
 ```powershell
 # For a normal files
 Select-String -Path .\PACKAGE_NAME -Pattern "powershell" -Encoding Byte
 
 # For a big files
 Get-Content -Encoding Byte -ReadCount 0 -Path .\PACKAGE_NAME | Select-String "powershell"
 ```
**For linux**
```sh
# Command grep
grep -a -b -o 'powershell' PACKAGE_NAME

# Command strings
strings PACKAGE_NAME | grep "powershell"
```
## References

https://pypi.org/

https://pypistats.org/

https://libraries.io/
