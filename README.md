To start git -> git init (in cmd of vs code) or use the icon

git -> is a version control -> it tracks all the changes that you are doing

stage -> the files are ready to be committed -> Done using the (+) sign on the folder level or individual file level

unstaged -> I still neeed to do some changes -> Done using (-) sign from the Staged list of files

commit  -> Finalising the changes that I have done
        -> Pre requisite for the commit is to stage the changes 
        -> Done using entering the commit message and clicking the tick sign

first time -> moving a project to git -> stage everything and add an initial commit

local repository (vs code)      ->    github repo (github server)
    local                       ->           remote
    master                     <->           master
repository is like a tree where in you can have multiple branches

push changes from local to remote -> git remote add origin 'url'

check status -> git status

push the source to git -> git push -u origin master

git by default does not track empty folders

We only have to use the 'git push -u origin master' command once initially and then post that we can use the push option available from the three dots dropdown next to the commit option




# Salesforce DX Project: Next Steps

Now that you’ve created a Salesforce DX project, what’s next? Here are some documentation resources to get you started.

## How Do You Plan to Deploy Your Changes?

Do you want to deploy a set of changes, or create a self-contained application? Choose a [development model](https://developer.salesforce.com/tools/vscode/en/user-guide/development-models).

## Configure Your Salesforce DX Project

The `sfdx-project.json` file contains useful configuration information for your project. See [Salesforce DX Project Configuration](https://developer.salesforce.com/docs/atlas.en-us.sfdx_dev.meta/sfdx_dev/sfdx_dev_ws_config.htm) in the _Salesforce DX Developer Guide_ for details about this file.

## Read All About It

- [Salesforce Extensions Documentation](https://developer.salesforce.com/tools/vscode/)
- [Salesforce CLI Setup Guide](https://developer.salesforce.com/docs/atlas.en-us.sfdx_setup.meta/sfdx_setup/sfdx_setup_intro.htm)
- [Salesforce DX Developer Guide](https://developer.salesforce.com/docs/atlas.en-us.sfdx_dev.meta/sfdx_dev/sfdx_dev_intro.htm)
- [Salesforce CLI Command Reference](https://developer.salesforce.com/docs/atlas.en-us.sfdx_cli_reference.meta/sfdx_cli_reference/cli_reference.htm)



