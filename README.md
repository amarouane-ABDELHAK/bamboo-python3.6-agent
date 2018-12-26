# bamboo-python3.6-agent
An agent to be used with Atlassian Bamboo CI.

## How to use
I am using conda to easily install some data science libraries like numpy required by some projects.
1. in the task script start by activating python36 environement `$ conda activate python36`
2. Run conda to install your project dependencies `conda install --yes --file requirements.txt`
3. This agent come with pytest pre-installed to be used against your tests folder.
4. Generate Junit xml test report for Bamboo to display the test results.
