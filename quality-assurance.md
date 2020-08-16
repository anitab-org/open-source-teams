<h1>Pre-requisites for contributing towards Quality Assurance</h1>

1. Join #quality-assurance stream on Zulip. Tag @admins on Zulip to add you under the @qa-team tag.
2. Choose a [project](https://github.com/anitab-org)
   * Join the respective Zulip stream for that project
3. Setting up the environment of the project

   a. If testing dev environment (stage), you can use deployed versions. You need not setup up the dev environment locally.
      * [Mentorship Android](https://github.com/anitab-org/mentorship-android/tree/apk)
      * [Mentorship Flutter](https://github.com/anitab-org/mentorship-flutter/tree/apk)
      * [Mentoship Backend](https://mentorship-backend-temp.herokuapp.com/)
      * [Volunteer Management System](http://ec2-52-53-177-18.us-west-1.compute.amazonaws.com/en-us/)
      * [Portal](http://ec2-54-215-223-241.us-west-1.compute.amazonaws.com/)
      * [AnitaB.org Open Source Web](https://anitab-org.github.io/)
      * [STEM Diverse TV](https://github.com/anitab-org/stem-diverse-tv/wiki/Quality-Assurance)
      * [Bridge in Tech Backend](https://bridgeintech-bit-heroku-psql.herokuapp.com/)
      * [Bridge in Tech Web]
      * [Opensource Programs Backend]
      * [Opensource Programs Web]
      
   b. If testing PRs, you have to setup the dev environment.
      * [How to test a PR?]
      * Mentorship Android:
        * [Dev Env Setup demo](https://anitab.zoom.us/rec/share/2uNHIJT-5EVJS7PzxVrWfK0oQtS1eaa81HdP-vVcyoErlalT9Mv00cK-ZvtOiMk?startTime=1589124944000)
        * [Dev Env Setup demo notes](https://docs.google.com/document/d/12D8356IenScM5DSRAITgg5X18tPZkRweXm_P-qmoQGY/edit)
        * [PR testing demo](https://anitab.zoom.us/rec/play/tJctd7j5rDk3SNWRtwSDUPUtW9XoJqis0iVL_fYFyBm1UyEKN1GmMrIaZ7RtkSCpQ2h7N8MOIMZc5wCD?startTime=1591118799000&_x_zm_rtaid=YOJgJH4BSZ65HhkWHNkhzg.1592773256165.ad77a44e5d4c2e726317ba090ee629b9&_x_zm_rhtaid=385)
      * Mentorship Flutter:
        * [Dev Environemnt Setup demo](https://anitab.zoom.us/rec/share/6MNVAO7pzE9OfNLP1m6EcJQrT6TgX6a81iRIrqAExUzyft37kQpq80KDeueJJKjY?startTime=1589108623000)
        * [Dev Environment Setup Notes](https://docs.google.com/document/d/1cLznYyN5VfVraN3swl81Yum1IXG3cyLyIdD85QOuGrY/edit?usp=sharing)
        * [PR testing demo](https://anitab.zoom.us/rec/play/vsEpIe2rpj03T9aSuQSDA_94W9W0J62shnAXqPINnUnmUXEHMAf0MOEVMOt-f8i1epVN8HeS5BurDHjH?startTime=1593537676000&_x_zm_rtaid=bRSfMzm_T4G4tNo7nBPtXQ.1593605707752.e181143531eb9176c6de82c23bf4f24a&_x_zm_rhtaid=490)
      * Mentorship Backend:
        * Dev Env Setup demo - [Recoreding 1](https://anitab.zoom.us/rec/share/2uNHIJT-5EVJS7PzxVrWfK0oQtS1eaa81HdP-vVcyoErlalT9Mv00cK-ZvtOiMk?startTime=1589121214000), [Recording 2](https://anitab.zoom.us/rec/share/2uNHIJT-5EVJS7PzxVrWfK0oQtS1eaa81HdP-vVcyoErlalT9Mv00cK-ZvtOiMk?startTime=1589121947000), [Recording 3](https://anitab.zoom.us/rec/share/2uNHIJT-5EVJS7PzxVrWfK0oQtS1eaa81HdP-vVcyoErlalT9Mv00cK-ZvtOiMk?startTime=1589122325000)
        * [Setup Notes](https://docs.google.com/document/d/1cOhwTMyo25n0sJLUfOjWTntzZwLTUTvCfL3fKJlKKmY/edit)
        * [Testing PR](https://github.com/anitab-org/mentorship-backend/blob/develop/docs/test-pr-guide.md#steps-to-test-a-pr)
      * VMS:
        * [Dev env setup demo](https://anitab.zoom.us/rec/share/xp1sE72v81xLRI3N81_VAa4ONZW8aaa81nBMq_UExE0n8GF03G1ifH1QShZHCvE7?startTime=1589115801000)
        * [Setup Notes](https://docs.google.com/document/d/1eJRmsf5lznb6Klym23P05qEb7vVLB9PWOlMm2ErRmXg/edit)
      * Portal:
        * [Dev env setup instructions](https://docs.google.com/document/d/1nL5c1xxse_ulHbjTgaHHv7XTIf41lQV0msYB7xesJGU/edit)
        * [Setup Notes](https://docs.google.com/document/d/1nL5c1xxse_ulHbjTgaHHv7XTIf41lQV0msYB7xesJGU/edit?usp=drivesdk)
      * AnitaB.org Open Source Web:
        * [Setup](https://github.com/anitab-org/anitab-org.github.io/blob/develop/README.md)
      * STEM Diverse TV:
        * [Setup](https://github.com/anitab-org/stem-diverse-android-tv/blob/master/README.md)
    
4. Signup on the test management tool [TestQuality](https://anitab-org.testquality.com/signup). Ask on Zulip under #quality-assurance stream tagging @qa-team, to set up your account with the right permission to the project you have chosen.

<h1>Quality Assurance Guidelines</h1>

1. Choose a test scenario in the project you’ve chosen and execute it on either the PR or deployed version that is being tested.
   * Manual Testing: Manually running the test scenario on the project.
   * Automated Testing: Writing a piece of code to execute the test and running that code.

2. Manual Testing Worksflow:

3. Automated Testing Workflow: