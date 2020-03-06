```
Utilities to analyze python code
Tools for Python Doc Generation, Tool analysis, Package Auto Install, Converter




#### Install for dev
cd YourFolder
git clone  https://github.com/arita37/cli_code.git
cd cli_code
pip install -e .



############### CLI Command
    "cli_repo_docs        =  cli_code/cli_docs.py",    Auto generate Documentation fron source code    
    
    "cli_env_autoinstall  =  cli_code/cli_env_autoinstall.py",  Auto generate from parsing source code.

    "cli_convert_ipny     =  cli_code/cli_convert_ipny.py",     Convert a folder of notebook to python script

    "cli_repo_check       =  cli_code/cli_repo_check.py",       Check a repo.

    "cli_conda_merge      =  cli_code/cli_conda_merge.py",      Merge a repo.




############## cli_env_autoinstall 
cli_env_autoinstall 
      --folder_input  /home/ubuntu/aagit/aapackage/aapackage/batch  
      --python_version "3.6.7"
      --packages "tensorflow=1.14  scikit-learn numpy pandas scipy matplotlib"


















#### Tests:
  cd  cli_code\cli_code
  cli_code>python cli_docs.py --do test   







```




