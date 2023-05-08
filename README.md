See the wiki @ https://github.com/alex-aleyan/git_howto/wiki

- Updated git from https://repo.ius.io:
    ```
    yum remove git
    sudo rpm -U  https://repo.ius.io/ius-release-el7.rpm 
    sudo yum --disablerepo="base,updates"  install git
    ```
