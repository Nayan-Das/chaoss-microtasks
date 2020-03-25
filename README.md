# CHAOSS Microtasks
This repository contains the microtask submissions for CHAOSS GSoC 2020. I want to work on the idea:
**{Open Source Health and Sustainability SSO Implementation with uPort}**


[X] **Microtask 0:** Familiarize yourself with augur by downloading and configuring the dev branch. For a little more context about what we are trying to accomplish with Augur's prototyping, checkout Augur's documentation at : https://oss-augur.readthedocs.io/en/dev/ Fork Augur into your own GitHub Account. Work in the dev branch.

![Augur ScreenShot 1](/image/1.png)

[X] **Microtask 1:** Using the Augur system, implement any SSO technology of your choosing. This is a completely "proof of concept" without any expectation of a finished work. Could be a social media or github based oauth. Does not need to "protect pages" (i.e., manage the entitlements part of sign on). Its enough to have to think through SSO in a Flask environment with something potentially as simple as a "mickey mouse" sign in (i.e., username and password of "mickey mouse", but processing it through an actual authentication system).

**Files Added**: I have added two file login.vue and secure.vue.


**Files Modified**: I have also changed the route.ts file to make login.vue file as home page.


**Functionality** : There is only facebook SSO implemented and one normal login with user name and password "nayan". After the login, it will navigate to the secure page.


![Microtask ScreenShot 1](/image/2.png)


![Microtask ScreenShot 2](/image/3.png)

[X] **Microtask 2:** Make a pull request to update the dev branch with the work from Microtask 1. If you have questions about getting started in the steps above, open an issue in the Augur repository.

**Pull request links**: https://github.com/chaoss/augur/pull/627
