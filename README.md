# pypi
this is making for download pypi on my desktop.
 pip install pypi-install
 from pypi_install import pypi_install as PI
pypirc_username="my_pypi_username" # for e.g. "new_john"
pypirc_password= "my_pypi_password" # for e.g. "john123"
directory_of_new_folder = "path_new_directory" # for e.g. "/home/USER/New_Folder"
version_number="your_project_version_no" # for e.g. "0.0.2"
author_name_full="full_author_name" # for e.g. "John Smith"
author_email="author_email" # for e.g. johnsmith123@hotmail.com
short_description="short_description" # for e.g. "My first PyPi project"
github_url="your_code_github_url" # for e.g. https://github.com/USER/my_respistory
python_version="python_version_in_your_computer" for e.g. "3" or "2"
name_of_project="name_of_pypi_project" for e.g. "my_pypi_code"
directory_of_python_files=["PATH/my_python_file_1.py","PATH/my_python_file_2.py"] # Include all the python files here
make_pypi_folders(pypirc_username,pypirc_password,directory_of_new_folder,name_of_project,directory_of_python_files,version_number,author_name_full,author_email,short_description,github_url,python_version,invoke_python_by_name='python',license_type="MIT License",operating_system="OS Independent") # There, your code is uploaded on pypi! It's that easy!
