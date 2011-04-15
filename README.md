Github Commands
===============

###Create folder, file, commit and push

    mkdir [dir_name]
    cd [dir_name]
    git init
    touch [file_name]   
    git add [file_name]     
    git commit -m '[message]'
    git remote add origin git@github.com:[user]/[dir_name].git
    git push -u origin master

###Commit and push local changes
git commit -a -m '[message]'
git push -u origin master

###Status (modifications, etc.)
git status

    var rpc = new easyXDM.Rpc({
        remote: "http://path.to/provider/" // the path to the provider
    }, 
    {
        local: {
            helloWorld: function(successFn, errorFn){
                // here we expose a simple method with no arguments
                // if we want to return a response, we can use `return ....`,
                // or we can use the provided callbacks if the operation is async
                // or an error occurred
            }
        },
        remote: {
            helloWorld:{
                // here we tell the Rpc object to stub a method helloWorld for us
            }
        }
    });
