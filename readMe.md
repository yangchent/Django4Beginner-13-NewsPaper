# News

![post_new_article](https://user-images.githubusercontent.com/72544887/147855630-0cd25d87-e130-41bf-afcd-0fd63c2c430a.png)


![newspaperDjango4Begginers](https://user-images.githubusercontent.com/72544887/147855632-6212b74b-1846-4dd6-aba4-9e1cd2497127.png)


- skipped : chapter 12 Email
- doing now : chapter 16 deploying to heroku Error
- precommit : clean all test passed
- heroku trouble :
  $ heroku -version
  bash: heroku: command not found

  heroku: The term 'heroku' is not recognized as a name of a cmdlet, function, script file, or executable program.
  Check the spelling of the name, or if a path was included, verify that the path is correct and try again.

- deployment in heroku 2nd trouble:

ERROR: Cannot install arrow==1.2.1 and python-dateutil==2.5.1 because these package versions have conflicting dependencies.

The conflict is caused by:

    The user requested python-dateutil==2.5.1
    
    arrow 1.2.1 depends on python-dateutil>=2.7.0

To fix this you could try to:

1. loosen the range of package versions you've specified

2. remove package versions to allow pip attempt to solve the dependency conflict


ERROR: ResolutionImpossible: for help visit https://pip.pypa.io/en/latest/user_guide/#fixing-conflicting-dependencies
