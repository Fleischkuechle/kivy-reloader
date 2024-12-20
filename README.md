# Kivy Reloader

a fork from here:
https://github.com/kivy-school/kivy-reloader

# i just added a requirements txt so it also can be used without poetry 
I am used to work with miniconda and not so familar with poetry
i install it using this batch script repo:

https://github.com/Fleischkuechle/standalone_env_in_parent_python_310


to clone the repo including its sub module 

git clone --recurse-submodules https://github.com/Fleischkuechle/kivy-reloader.git

for those who are not familar with the 
#.gitmodules

.gitmodules is a convinient way to add other repos as a sub module of your repo

this is how it looks like for this repo:

[submodule "standalone_env_in_parent_python_310"]
    path = standalone_env_in_parent_python_310
    url = https://github.com/Fleischkuechle/standalone_env_in_parent_python_310.git