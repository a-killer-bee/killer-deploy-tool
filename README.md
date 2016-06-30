# killer-deploy-tool
deploy-tool based on pssh

  Built by a-killer-bee at 2016/04/11
  Version deploy-1.0.1
  for deployment of applications
  Note: We shall not be responsible for any loss, damages and troubles.

  History
    2016/04/11 version deploy-1.0.1
     first revision is released.

  How to use
    1. SSH connect
      user: test
      password: testpasswd

    2. Substitute user
      $ su root

    3. How to Deploy
      # deploy test_app normal // Not always necessary to add option "normal"
      # deploy test_api
      ...

    4. How to rollback
      # deploy test_app rollback
      # deploy test_api
      ...
