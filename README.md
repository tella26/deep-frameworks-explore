## Forking a Repo & Setting up your workflow

1. Fork the repo
2. Clone your forked repo <br>
  `$git clone https://github.com/YOUR_USERNAME/YOUR_FORK.git`
3. Check your remote
      ``` 
      $ git remote -v
      # origin  https://github.com/YOUR_USERNAME/YOUR_FORK.git (fetch)
      # origin https://github.com/YOUR_USERNAME/YOUR_FORK.git (push)
      ```
4. Add the upstream  <br>
 ` $ git remote add upstream https://github.com/AISaturdaysLagos/deep-frameworks-explore.git`
5. Repeat step 3, now you should have
    ````
    $ git remote -v
    # origin    https://github.com/YOUR_USERNAME/YOUR_FORK.git (fetch)
    # origin    https://github.com/YOUR_USERNAME/YOUR_FORK.git (push)
    # upstream  https://github.com/AISaturdaysLagos/deep-frameworks-explore.git (fetch)
    # upstream https://github.com/AISaturdaysLagos/deep-frameworks-explore.git (push)
    ````

## Contributing to a Forked Repo

1. Fetch the upstream files - incase anyone has added anything <br>
    `git fetch upstream `
2. Checkout to Master <br>
    `git checkout master`
3. Merge the changes into your forked repo<br>
    `git merge upstream/master`
4. Add your folder or Changes. For Example, <br>
    `git add teamPyTorch`
5. Commit your changes <br>
    `git commit -m 'Classify two different black panther characters - shuri & okoye'`
6. Push your changes <br>
    `git push origin master`
7. Send a PR


#### Helpful Link 

1. https://help.github.com/articles/configuring-a-remote-for-a-fork/
