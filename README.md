Jenkins Job Builder hidden parameter
===================================

Installation:
------------

`pip install jenkins-jobs-hidden-param`


JJB configuration:
-----------------

    parameters:
      - hidden:
          name: ENV_NAME
          default: 'develop'
          description: "Environment name"
