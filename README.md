# java-ee-specs

## Cloning
This project contains a number of submodules. In order to clone the repository and all the submodules in one go use the following command:

    git clone --recursive git@github.com:javaee-spec/java-ee-specs.git
   
This command will automatically clone and update all submodules as well.

## Pulling the latest changes
In order to pull the latest changes you can use the following command to automatically pull all changes for the submodules as well:

    git pull --recurse-submodules
    
However, if any new submodules are added, you also need to execute the following commands:

    git submodule init
    git submodule update
