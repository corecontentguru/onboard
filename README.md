# onboard
1. In order to check in code to this repository, you need create a github account, then send your username to admin. Admin will add you as collaborator.

2. project structure

  2.1 create content directory
  
        /codebase/corecontent
        
  2.2 clone code from git hub
    
      git init
      git clone git clone https://github.com/corecontentguru/dataaccess.git
      git clone git clone https://github.com/corecontentguru/common.git
      ....
  2.3 check in code
      after you modify code or create new file, you can check in your code.
  
      git add [filename]   /* for example git add README.md  */
      git commit -m "first commit"
      
    at this point your ocde only commit to local repository, to check in code into github, ....
      
      git remote add origin https://github.com/corecontentguru/common.git   /* or dataaccess.git... */
      git push -u origin master     /* you may need check in different branch */
    
3. thirdpaty open source jar
     
    /thirdparty/
    
    add third party jar, example: 
    
    /thirdparty/lucene-4.0.0/core/lucene-core-4.0.0.jar
    

